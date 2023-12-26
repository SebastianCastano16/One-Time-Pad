# One-Time Pad Decryption


One-Time Pad Decryption
Overview
This Python script provides a simple implementation of a one-time pad decryption method. The one-time pad is a cryptographic technique that involves the use of a random and secret key that's as long as the message. It XORs the message with the key to produce ciphertext and decrypts it by XORing it again with the same key.

Requirements
Python 3.x
How to Use
Setup:

Ensure you have Python installed on your system.
Run the Script:

Open the script in a Python environment or terminal.
Modify the timestamp_str and encrypted_message_base64 variables with your own values.
Execute:

Run the script.
It will attempt to decrypt the provided encrypted message for all 60 seconds of the specified minute within the given timestamp.
Code Explanation
generate_one_time_pad(seed, length): Generates a one-time pad of specified length using the provided seed.
decrypt_message(encrypted_base64, one_time_pad): Decrypts the given base64 encoded message using the provided one-time pad.
timestamp_str: The timestamp without seconds used as a basis for decryption.
encrypted_message_base64: The encrypted message in base64 format to be decrypted.
Example
The provided code demonstrates how to decrypt a message encrypted using a one-time pad with a specific timestamp. It iterates through all 60 seconds of a given minute to attempt decryption and prints the decrypted message for each second.

Note: Ensure the accuracy of the timestamp and message for successful decryption.

Disclaimer
This code is for educational purposes only and should not be used for secure communications as it's a basic illustration and might not cover all security considerations.
