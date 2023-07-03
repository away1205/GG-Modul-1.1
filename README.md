# GENERASI GIGIH 3.0 -- MODUL 1.1

The provided code is an HTML code snippet that represents a simple login form with form validation. Let's break down the code and explain its components:

- `<!DOCTYPE html>`: This is the doctype declaration, which specifies that the document is an HTML5 document.

- `<html>...</html>`: This is the root element of the HTML document. All the content of the web page is contained within these tags.

- `<head>...</head>`: This section contains metadata and other information about the web page, such as the title, character encoding, linked stylesheets, and scripts. In this case, it includes the title "Form Validation".

- `<title>Form Validation</title>`: This element specifies the title of the web page, which is displayed in the browser's title bar or tab.

- `<body>...</body>`: This section contains the visible content of the web page, such as text, forms, images, and other elements.

- `<form action="/" method="POST">...</form>`: This is a `<form>` element that represents a form in HTML. It contains input fields and buttons for users to enter and submit data. It has two attributes:
  - `action="/"`: Specifies the URL or path where the form data will be submitted. In this case, it is set to "/" (root URL), indicating that the form will be submitted to the current page itself.
  - `method="POST"`: Specifies the HTTP method used to submit the form data. In this case, it is set to "POST", which is commonly used for submitting sensitive information like passwords.

- `<label for="email">Email:</label>`: This is a `<label>` element that associates with the email input field. The `for` attribute specifies which input field it is associated with using the matching `id`.

- `<input type="email" id="email" name="email" required>`: This is an `<input>` element with `type="email"`, which creates an email input field. It has several attributes:
  - `id="email"`: Specifies a unique identifier for the input field. It should match the `for` attribute of the corresponding `<label>` element.
  - `name="email"`: Specifies the name of the input field, which is used when the form is submitted.
  - `required`: Specifies that the input field must be filled in before the form can be submitted.

- `<label for="password">Password:</label>`: This is a `<label>` element associated with the password input field, similar to the email label.

- `<input type="password" id="password" name="password" minlength="6" required>`: This is an `<input>` element with `type="password"`, which creates a password input field. It has attributes similar to the email input field, with an additional attribute:
  - `minlength="6"`: Specifies the minimum number of characters required for the password. In this case, it is set to 6 characters.

- `<button type="submit">Login</button>`: This is a `<button>` element that represents a submit button. When clicked, it triggers the form submission. In this case, it displays the text "Login" as the button label.

Overall, this code snippet creates a basic login form with email and password input fields. The form enforces basic validation rules such as requiring both fields to be filled, ensuring the email is in the correct format, and requiring a minimum password length of 6 characters.
