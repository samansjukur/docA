# docA - DOcument on Algorand blockchain
Is an android app for create and verify document on Algorand blockchain.
docA store the encrypted field value of the document on the blockchain, restore it back on the verification process.
Develop with LiveCode, docA is an implementation example of Algorand simple design into real App.


# Details
Documents are pre-designed on the app, when user create a document it will generate a PDF file for send by email to the document owner and encrypt all fields value, store it on the Algorand blockchain. The transaction ID from the block will use for generate QR code and display on the PDF file.
This QR will be scan by the verify function to query the block from Algorand blockchain, decrypt it and generate the specific document base on the document type when it created.

docA is develop using LiveCode and Algorand javascript SDK.
The source code file : doca.livecode

For security reason, it is recommend to write your own function to generate a encryption key.
the code is on the function "getCipherKey" at the stack script


# Requirements
LiveCode 9.x
https://livecode.org/


# Demo
https://play.google.com/store/apps/details?id=io.docamobileapp.app
