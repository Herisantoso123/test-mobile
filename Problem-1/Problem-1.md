# Dynamic Form

## Instruction
Create an Android App that renders a form based on a question list. The question list is downloaded from a server and available in JSON format. Upon form submission, App should show the answers in a "[key]: [value]" format.

## Language
Kotlin

## Important Notes
1. The App should download the question list from [here](https://raw.githubusercontent.com/amarthaid/test-mobile/master/Problem-1/question.json). Storing the question list as a static file is not acceptable.
2. Please do validation for each question based on what is stated in the JSON file. You may add your own validation, but conforming to the given validation is a must.
3. Show the answers in different screen in "[key]: [value]" format. E.g.
```
email: habib@email.com
name: Habib Ridho
...
```