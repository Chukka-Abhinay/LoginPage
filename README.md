# LoginPage
login page with password encrypted

here we started!!..

Resouces : 

PHP : https://youtu.be/zZ6vybT1HQs?si=A4nmuqF9Dx-S0vLQ

login-system/</br>
│</br>
├── public/                     # Publicly accessible files (front-end)</br>
│   ├── index.html              # Main login/registration page</br>
│   ├── login.html              # Login page (optional, if separate from index.html)</br>
│   ├── register.html           # Registration page (optional, if separate from index.html)</br>
│   ├── css/                    # CSS files</br>
│   │   └── styles.css          # Styles for the login/registration pages</br>
│   ├── js/                     # JavaScript files</br>
│   │   ├── validation.js       # Client-side validation (email, password, context)</br>
│   │   ├── encryption.js       # Client-side encryption logic (R1, R2, key, SK1, SK2)</br>
│   │   └── api.js              # Handles API calls to the server</br>
│   └── assets/                 # Static assets (e.g., images, icons)</br>
│       └── logo.png            # Example logo</br>
│</br>
├── server/                     # Server-side PHP code</br>
│   ├── index.php               # Main entry point for the server</br>
│   ├── register.php            # Handles user registration</br>
│   ├── login.php               # Handles user login</br>
│   ├── db.php                  # Database connection and utilities</br>
│   ├── encryption.php          # Server-side encryption/decryption logic</br>
│   └── validation.php          # Server-side validation logic</br>
│</br>
├── database/                   # Database-related files</br>
│   └── users.sql               # SQL file to create the `users` table</br>
│</br>
└── README.md                   # Project documentation</br>