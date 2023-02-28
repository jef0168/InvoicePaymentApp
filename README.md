# InvoicePaymentApp
Application
This app can generate, send, and receive invoices, as well as send automated follow-up reminders about overdue payments.

Requirements
Users can save client information in the app.
Users can quickly generate a new invoice for a saved client.
Users can send invoices to clients from within the app.
The following image shows one way to implement the UI. Feel free to interpret the requirements however you'd like!
Invoicing and payment reminder mobile app project demo

For an extra challenge

Send automated follow-up reminders via email or text for overdue invoices.
Track whether invoice emails have been opened, and when.
Add reporting on clients, invoices, and monthly earnings.
Give clients the ability to pay invoices directly using a link in your invoice emails.
For invoices paid in a foreign currency, display the value of the invoice in your local currency.
Suggested Implementation
You can use a library like jsPDF to programmatically generate PDF invoices based on dynamic inputs. Use this library to populate invoices with information from your database, such as your business info and information about the client.
You can use SendGrid to send automated email reminders and Twilio to send automated texts.
Use Stripe to allow clients to pay your invoices immediately with a convenient link included in your invoice email.
You can use an email tracking pixel to track whether your invoice email has been opened.
References
Have your invoicing app also generate a Stripe invoice that clients can pay via the invoice email you send them.
Use the Foreign Exchange Rates API provided by the European Central Bank to predict the value of foreign currency invoices in your local currency.
Check out our tutorial on converting HTML/CSS content to a sleek multi-page PDF with jsPDF.