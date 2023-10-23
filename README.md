# Exams in Bangladesh

This repository provides a JSON-like data structure containing a list of exam options. The data is organized to include exam labels and numerical IDs. You can use this data in your projects as a reference or for any other purpose.

## JSON Data Structure

The JSON-like data structure is organized as follows:

```json
{
  "exam_options": [
    {
      "id": 1,
      "value": "ssc",
      "label": "SSC/Dakhil/Equivalent"
    },
    {
      "id": 2,
      "value": "jsc",
      "label": "JSC/JDC"
    },
    // ... (other exam options)
  ]
}
```
Each exam option is represented as an object with a unique numerical ID and a label describing the exam type.
# Usage
You are free to use this data in your projects under the terms of the open-source license (if applicable). To use the data, you can clone or download this repository, and then access the `exam_options.json` file for the data.
# Example Usage
Here's an example of how to access the data using JavaScript:
```
// Load the exam options data
const examOptions = require('./exam_options.json');

// Access exam options
examOptions.exam_options.forEach(option => {
  console.log(`ID: ${option.id}, Value: ${option.value}, Label: ${option.label}`);
});
```
# Contributing
If you have additional exam options to add or any improvements to suggest, please feel free to contribute to this repository. You can create a pull request with your changes.

# License
This project is open-source and available under the Apache License 2.0. Please review the license file for detailed terms and conditions.

# Acknowledgments
//
# Collected by
Tahmeedul Islam
