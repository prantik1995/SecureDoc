# SecureDoc
This is a document/certificate issue and verification system designed in PHP and signed with digital signature. 

SecureDoc Project (SD Lab)
Prantik Panja
M.Tech in CSE
Reg No 2018MTCSE004
prantikpanja@gmail.com
Central University of Rajasthan — November 22, 2018


1 Summary of the Project

SecureDoc Project is a web-based project where mainly two types of user present. A Verifier can lunch
a certificate and upload certificate details of a candidate and into that particular certificate table. The
validity of the certificate for the candidate is the lifetime.
A user (candidate) can log in into his/her account. After login he can search is certificate and view in.
He can also share his document with a SecureDoc user (User/Verifier) with a validity period ( maximum
30 days). The shared document access link automatically mailed to the shared person.


2 Tools and Technologies Used:

The tools and technologies that are used in this project are listed below.
• Programming Language: PHP 7.2.10-0ubuntu0.18.04.1, HTML, CSS.
• Database: mysql Ver 14.14 Distrib 5.7.24
• Administration Tool for MySQL: phpMyAdmin 4.8.3
• IDE for code edit: Bluefish
• Web Server: Apache 2
• Other Code Library: PHPMailer


3 How did you plan module and structure

The different modules are
• Registration Page and Login page for two different type of user ( Common User and Certificate Verifier)
• OTP Verification portal before the first-time successful login.
• Portal for the verifier to add a new certificate.
• Portal for the verifier to add a new record into a certificate.
• Portal for the user for view his own certificate.
• Portal for the user for share certificate with another user.
• Module for handle shared the link and show the certificate to the authorised user only.

Please read "main.pdf" for more. 
