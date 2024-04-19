
# Twilio Scheduled Call

This Python script enables you to schedule a call using Twilio to deliver a recorded message at a specific date and time.

## Prerequisites

- Python 3.x installed on your system.
- Twilio account SID and auth token.
- A Twilio phone number that is capable of making voice calls.

## Setup

1. Install the required Python packages:
    ```
    pip install twilio
    ```

2. Update the following variables in the script with your Twilio account SID, auth token, and Twilio phone number:
    - `account_sid`: Your Twilio Account SID.
    - `auth_token`: Your Twilio Auth Token.
    - `twilio_phone_number`: Your Twilio Phone Number.

3. Run the script and follow the prompts to schedule a call:
    ```
    python scheduled_call.py
    ```

## Usage

1. Enter the phone number you want to call when prompted.
2. Enter the date and time you want to schedule the call in the format `YYYY-MM-DD HH:MM:SS`.
3. The script will schedule the call and print a confirmation message.

Note: The call will be initiated at the specified date and time, and a recorded message will be delivered.
