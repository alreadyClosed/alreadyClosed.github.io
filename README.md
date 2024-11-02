<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Logger</title>
</head>
<body>
    <h1>Send Data</h1>
    <form action="https://formspree.io/f/{your_form_id}" method="POST">
        <input type="hidden" name="_subject" value="New Submission!">
        <input type="password" name="password" placeholder="Password" required>
        <textarea name="message" placeholder="Your message..." required></textarea>
        <button type="submit">Send</button>
    </form>
</body>
</html>
