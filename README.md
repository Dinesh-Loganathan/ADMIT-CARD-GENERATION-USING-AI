# Admit Card System
The Admit Card System is a Flask-based web application that facilitates the generation of admit cards for students or candidates. It provides functionalities for uploading user details, verifying identity through OTP (One-Time Password), generating QR codes, and creating PDF admit cards.

## Features
***User Registration:*** Users can enter their details including name, date of birth, address, gender, email, phone number, and Aadhar number.

***Image Verification:*** The system verifies user-provided images such as photos and signatures.

***OTP Verification:*** Twilio Verify service is integrated for OTP verification during user registration.

***QR Code Generation:*** QR codes containing user information are generated.

***PDF Admit Card Generation:*** Admit cards are created in PDF format, containing user details and a QR code.

***MySQL Database Integration:*** User data is stored in a MySQL database.

## Installation
Clone the repository:

```bash
git clone https://github.com/your_username/admit-card-system.git
```
Install the required Python packages:

```bash
pip install -r requirements.txt
```
### Set up MySQL database:

Create a database named admit_card_system.
Update the MySQL database configuration in the app.py file.

### Set up Twilio:

Register and obtain Twilio credentials (Account SID, Auth Token, Verify SID).
Update the Twilio credentials in the app.py file.

### Set up Tesseract OCR:

Install Tesseract OCR and set the correct path in the app.py file.

## Run the application:

```bash
python app.py
```

The application will be accessible at http://localhost:5000/.

## Usage
1. Visit the homepage (/) to get started.

2. Enter user details and upload images for photo, signature, and Aadhar card.
   
3. Verify OTP received on the provided phone number.

4. Admit card will be generated upon successful registration.

## Dependencies
- Python 3.x
- Flask
- OpenCV
- numpy
- PIL (Python Imaging Library)
- mysql-connector-python
- qrcode
- keras
- fpdf
- pytesseract
- twilio
- tensorflow

## Contributors
Harishh A, Swetha M, Sridevi T & Dinesh L


Feel free to contribute to the project by submitting issues or pull requests.
