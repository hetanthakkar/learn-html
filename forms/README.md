## Getting Started

- Install the version of Node JS for your OS https://nodejs.org/en/download
- From a terminal run the following commands to check if the installation was successful:
  - `$ node -v`
  - `$ npm -v`
  - Set PATH environment variable to path/to/bin/node and path/to/bin/npm if the above commands failed to return the version number.
- In the terminal install dependencies using the command:
    `$ npm install`
- In the terminal run the local server using the command:
  - `node form-server.js`
- Open "form.html" in a browser. Enter username and password and click "Submit".

## Questions for you to answer
1. What is the purpose of the _action_ attribute in the _form_ tag?
The action attribute in the form tag serves the purpose of specifying the destination to which the form data should be sent upon submission. In other words, it determines the page responsible for processing the form.
2. What is the purpose of the _method_ attribute in the _form_ tag?
The method attribute within an HTML form indicates the chosen HTTP method for form submission. The two frequently used methods are "GET" and "POST".
3. What is the purpose of the _name_ attribute in the _input_ tag?
The name attribute is used to make references to elements or to access form data following the submission of a form. Only form elements containing a name attribute will transmit their values during the form submission process.
4. What is the purpose of the _type_ attrbute in the _input_ tag?
The type attribute specifies the type of input that will be taken for eg. Text, checkbox etc.
5. What is the purpose of the _label_ tag?
The label tag is used to assign different labels to the form elements.
6. What is the purpose of the _required_ attribute?
The required attribute ensures that an input field must be filled out before submitting the form.

