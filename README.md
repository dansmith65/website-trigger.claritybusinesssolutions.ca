System to handle link's emailed to users, which should trigger a webhook. If said webhook url is directly included in an email to users, mail server's validation routines often visit link's to verify they are not malicious. This project is intended to filter out those visits by mail servers and only trigger the webhook when a user clicks the link in their email.
