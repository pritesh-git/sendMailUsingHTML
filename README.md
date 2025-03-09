# SendMails: A Simple HTML Email Sender

This project provides a basic HTML page with JavaScript that uses the `smtpjs` library to send emails to multiple recipients.

## Project Overview

This project demonstrates a simple way to send emails from a web page using client-side JavaScript. It includes:

* An HTML form with a button to trigger the email sending process.
* A JavaScript function that uses `smtpjs` to send emails.
* A predefined list of email recipients.
* Basic error handling and alerts.

## Technologies Used

* **HTML:** For creating the basic structure of the web page.
* **JavaScript:** For handling the email sending logic.
* **smtpjs:** A client-side JavaScript library for sending emails using SMTP.

## Getting Started

1.  **Save the code:** Save the provided HTML code as an `.html` file (e.g., `send_mails.html`).
2.  **Open in browser:** Open the saved HTML file in a web browser.
3.  **Configure email credentials:**
    * In the JavaScript code, replace `'myName@gmail.com'` with your Gmail username.
    * Replace `'*******'` with your Gmail password.
    * Replace `'myEmail@gmail.com'` with the sender's email address.
4.  **Modify recipient list (optional):**
    * Update the `mailList` array in the JavaScript code with the desired recipient email addresses.
5.  **Send email:** Click the "Send Email" button on the page.
6.  **Check network tab:** Open the browser's developer tools and go to the "Network" tab to see the status of the email sending request.

## Notes

* This project uses `smtpjs` for sending emails, which relies on client-side JavaScript.
* For security reasons, it's not recommended to hardcode your email password directly in the code. Consider using environment variables or other secure methods for handling sensitive information.
* This is a basic example and may not be suitable for production environments. For more robust email sending solutions, consider using server-side technologies.
* Ensure that your Gmail account has "Less secure app access" enabled, or use an App Password for more security.
* The provided code is configured for Gmail. If you're using a different email provider, you'll need to update the SMTP settings accordingly.

## Contributing

Feel free to contribute to this project by submitting pull requests.

## License

This project is open-source and available under the MIT License.
