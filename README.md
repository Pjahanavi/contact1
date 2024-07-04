<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us</title>
    <link rel="stylesheet" href="C:\Users\jaanu\Desktop\contact.css">
</head>
<body>
    <div class="container">
        <h1>Contact Us</h1>
        <form id="contactform">
            <div class="form-group">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
            </div>
            <div class="form-group">
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
            </div>
            <div class="form-group">
                <label for="subject">Subject:</label>
                <input type="text" id="subject" name="subject" required>
            </div>
            <div class="form-group">
                <label for="message">Message:</label>
                <textarea id="message" name="message" required></textarea>
            </div>
            <button type="submit">Submit</button>
        </form>
        <div id="confirmationMessage" class="hidden">
            Thank you for your message. We'll get back to you soon!
        </div>
    </div>
    <script src="C:\Users\jaanu\Desktop\script.js"></script>s
</body>
</html>
