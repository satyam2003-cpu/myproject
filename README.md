Image Steganography with Python

This project demonstrates how to conceal and retrieve secret messages within images using Python's OpenCV library. It employs the Least Significant Bit (LSB) technique to embed text into an image, ensuring minimal alteration to the original visual content.

Features

Message Embedding: Hide a secret message within an image by modifying its pixel values.

Password Protection: Secure the hidden message with a user-defined passcode.

Message Extraction: Retrieve and display the concealed message from the image using the correct passcode.


Requirements

Python 3.13.2

OpenCV (opencv-python)

NumPy


Installation

1. Clone the repository:

https://github.com/satyam2003-cpu/myproject.git


2. Install the required packages:

pip install opencv-python numpy



Usage

1. Prepare an Image:

Place the image (e.g., mypic.jpg) in the script's directory.



2. Run the Script:

python stego.py


3. Follow the Prompts:

Encoding: Enter the secret message and a passcode to embed the message into the image, which will be saved as encryptedImage.jpg.

Decoding: Provide the correct passcode to retrieve and display the hidden message.




Methodology

The script utilizes the Least Significant Bit (LSB) technique for steganography. This method involves modifying the least significant bits of the image's pixel values to embed the secret message. By altering these bits, the visual changes to the image are imperceptible to the human eye, ensuring the hidden message remains concealed.

Limitations

Message Length: Ensure the image size is sufficient to embed the entire message.

Security: While the script includes basic password protection, for enhanced security, consider implementing more advanced encryption methods.


License

This project is licensed under the MIT License.


