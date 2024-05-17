# RetroTexter

RetroTexter is a vintage-themed SMS client inspired by the nostalgic look of AIM (AOL Instant Messenger). Built with Python and Tkinter, it allows users to send and receive text messages using email. This application provides a simple and retro user interface for messaging, combining the charm of old-school chat with modern email functionality. Integration with Windows Live Messenger is a work in progress.
## How It Works

    Sending Messages:
        Enter Phone Number and Carrier: Users input the recipient's phone number and select their carrier from a dropdown list. This is necessary to format the email address correctly for sending SMS.
        Compose Message: Users type their message into the input field.
        Send Email: RetroTexter converts the phone number and carrier information into the appropriate email format (e.g., 1234567890@txt.att.net for AT&T) and sends the message via SMTP.

    Receiving Messages:
        Check Inbox: RetroTexter periodically checks the configured email inbox for new messages using IMAP.
        Display Messages: Incoming messages are displayed in the chat window with a retro aesthetic, indicating the sender's phone number.

## Supported Carriers

RetroTexter supports major US carriers, allowing SMS messages to be sent via email-to-SMS gateways. Users can select from a list of carriers such as:

    AT&T
    Verizon
    T-Mobile

This selection ensures that messages are correctly formatted and delivered to the recipient's phone.


## Installation and Setup

    Install Requirements:
        Ensure you have Python installed.
        Install the tkinter library if not already available.

    Configure Email:
        Enter your email credentials in the code.
        For Gmail users, enable "Less secure app access" or use an app-specific password.

    Run the Application:
        Run the Python script to launch RetroTexter.
        Use the retro-themed interface to send and receive messages.
