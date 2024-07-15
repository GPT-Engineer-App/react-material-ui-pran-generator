# react-material-ui-pran-generator

I need a pran generation component in react js. 
Use material UI for design.
Page 1 - personal Details
page 2 - personal details
page 3 - PRAN details
page 4 - bank details
page 5 - document upload.


Let me know if you need more details.

Pages schema- 
{
  "page1": {
    "phone": "9068158213",
    "email": "string",
    "dob": "string",
    "gender": "string",
    "countryOfBirth": "indian",
    "nationality": "indian",
    "residentFlag": "string",
    "USCitizen": "boolean",
    "indianTaxResidance": "boolean"
  },
  "page2": {
    "title": "shri",
    "firstName": "Tushar",
    "middleName": "string",
    "lastName": "string",
    "cityOfBirth": "string",
    "maritalStatus": "string",
    "familyDetails": {
      "father": {
        "firstName": "string",
        "middleName": "string",
        "lastName": "string"
      },
      "mother": {
        "firstName": "string",
        "middleName": "string",
        "lastName": "string"
      }
    },
    "communicationDetails": {
      "ownership": "string",
      "address1": "string",
      "address2": "string",
      "street": "",
      "city": "string",
      "state": "string",
      "country": "string",
      "pincode": "string",
      "area": "",
      "landmark": ""
    }
  },
  "page3": {
    "nameTobePrintedOnPRANCard": "Father",
    "pranPrintHindi": "boolean",
    "physicalPan": "boolean",
    "nomineeDetails": [
      {
        "firstName": "string",
        "middleName": "string",
        "lastName": "string",
        "relation": "string",
        "age": "string",
        "above18": "boolean",
        "dob": "string",
        "nomineeShare": "string",
        "guardianName": "string"
      }
    ]
  },
  "page4": {
    "annualIncome": "string",
    "occupation": "string",
    "bankDetails": {
      "bankIfscCode": "",
      "bankAccountType": "",
      "bankAccountNumber": "",
      "bankName": ""
    }
  },
  "page5": {
    "signature": "file",
    "photo": "file",
    "panCard": "file",
    "aadharCard": "file",
    "idProof": "file"
  }
}




## Collaborate with GPT Engineer

This is a [gptengineer.app](https://gptengineer.app)-synced repository 🌟🤖

Changes made via gptengineer.app will be committed to this repo.

If you clone this repo and push changes, you will have them reflected in the GPT Engineer UI.

## Tech stack

This project is built with .

- Vite
- React
- shadcn-ui
- Tailwind CSS

## Setup

```sh
git clone https://github.com/GPT-Engineer-App/react-material-ui-pran-generator.git
cd react-material-ui-pran-generator
npm i
```

```sh
npm run dev
```

This will run a dev server with auto reloading and an instant preview.

## Requirements

- Node.js & npm - [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating)
