# onehouse-website
Audio Video Steganography integrated Machine Learning

OneHouse is a project to design a website in the real estate field, developed by me - [Nguyen Cuong](https://github.com/leansevenuteen) and colleagues: [Hoang Minh](https://github.com/theluckiest1912), [Gia Lac](https://github.com/peanut20114), [Doan Duc](https://github.com/doanmanhducz), and [Duong Dat](https://github.com/NMFKos).

## Introduction
OneHouse is a website for renting service apartments that offers a variety of features ranging from basic to advanced as follows:

**Customer-side:**
- Login and registration
- Google account sign-in
- Password recovery (send verification code via email)
- Search for rental rooms using a search bar with four criteria (which can be adjusted): room type, area, price, and size
- Online payment
- Post ads and pay for advertisements
- Respond to posts for admins
- Comment and rate posts with star ratings
- Change password and personal information
- AI chatbot (OpenAI API)

**Admin-side:**
- Approve posts
- Review user feedback
- View newly registered users and transaction volume

## Interfaces
### Customer Interface
- Home page: Displays a list of available rental rooms.

![56bb075d-d416-4da2-9af1-eb9f46ffdfa2](https://github.com/user-attachments/assets/8c7c2135-7c91-4260-a49b-8b10c64c36be)

- Login, Register: User-friendly login and registration interface.

![4fd85dcc-f176-43ac-a2bd-0ee3895544aa](https://github.com/user-attachments/assets/73ec3a5e-b358-4a57-98e7-5b6aa187b437)

![05222228-bc4f-4768-8afe-86e779addfd5](https://github.com/user-attachments/assets/3ec49a28-b1b5-473c-9e3f-2041e2a6f280)

- Ad details: The detailed ad interface allows users to view information about the rental room more closely, with options to respond, comment, or rate the ad.

![710d6bbb-ecd7-41ad-9871-9dc3b968b8b6](https://github.com/user-attachments/assets/15d37cf1-ba94-41ef-9e22-d2411987c101)

- Posting page, ad management: Easy to use, convenient payment, fast confirmation, and many offers for VIP package users.
- Information management, password management page: User-friendly interface that allows users to change their information and passwords securely in just 5 seconds.
### Admin Management Interface
- Home page: Manages statistics and user engagement.

![dd2a348d-7717-4faa-8ab1-3bc5f4ffeeef](https://github.com/user-attachments/assets/c28f695f-d99a-4c01-a2c1-c289d6303c75)

- Post approval, user feedback approval page: Easy-to-adjust interface suitable for management.

![fdf037ed-b091-48c6-aa0d-d7ffd36a8c2d](https://github.com/user-attachments/assets/3d24f36f-1ecc-4666-a414-f5d1026ae33d)

![51aef7a7-c221-4cf7-bbe6-d2a23a989841](https://github.com/user-attachments/assets/9bb6163c-ad73-4a25-8bdc-3d6d14e5cf0e)

## Usage
Make sure you have installed the following extensions for VSCode, including `Live Server` to run the website in the browser, `JavaScript E56` to run JavaScript scripts, and `Bootstrap 4`.

**Dependencies:**
- @google/generative-ai: 0.11.4
- @payos/node: 1.0.6
- atlas: 1.0.0-alpha.0
- bcrypt: 5.1.1
- connect-flash: 0.1.1
- dotenv: 16.4.5
- express: 4.19.1
- express-handlebars: 7.1.2
- express-session: 1.18.0
- firebase: 10.11.0
- fs: 0.0.1-security
- jsonwebtoken: 9.0.2
- method-override: 3.0.0
- mongodb: 6.5.0
- mongoose: 8.4.0
- multer: 1.4.5-lts.1
- nodemailer: 6.9.13
- passport: 0.7.0
- passport-google-oauth: 2.0.0
- passport-google-oauth2: 0.2.0
- passport-jwt: 4.0.1”

Install [NodeJS](https://nodejs.org/en/download/prebuilt-installer) version 20.11.1 and necessary dependencies:
  ```sh
  npm install @google/generative-ai @payos/node atlas bcrypt connect-flash dotenv express express-handlebars express-session firebase fs jsonwebtoken method-override mongodb mongoose multer nodemailer passport passport-google-oauth passport-google-oauth2 passport-jwt
  ```
Run project using the following code:
  ```sh
  npm start
  ```
  or
  ```sh
  node src/index.js
  ```
