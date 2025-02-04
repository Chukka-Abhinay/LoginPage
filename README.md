# LoginPage
login page with password encrypted

here we started!!..

Resouces : 

PHP : https://youtu.be/zZ6vybT1HQs?si=A4nmuqF9Dx-S0vLQ

login-system/
│
├── public/                     # Publicly accessible files (front-end)
│   ├── index.html              # Main login/registration page
│   ├── login.html              # Login page (optional, if separate from index.html)
│   ├── register.html           # Registration page (optional, if separate from index.html)
│   ├── css/                    # CSS files
│   │   └── styles.css          # Styles for the login/registration pages
│   ├── js/                     # JavaScript files
│   │   ├── validation.js       # Client-side validation (email, password, context)
│   │   ├── encryption.js       # Client-side encryption logic (R1, R2, key, SK1, SK2)
│   │   └── api.js              # Handles API calls to the server
│   └── assets/                 # Static assets (e.g., images, icons)
│       └── logo.png            # Example logo
│
├── server/                     # Server-side PHP code
│   ├── index.php               # Main entry point for the server
│   ├── register.php            # Handles user registration
│   ├── login.php               # Handles user login
│   ├── db.php                  # Database connection and utilities
│   ├── encryption.php          # Server-side encryption/decryption logic
│   └── validation.php          # Server-side validation logic
│
├── database/                   # Database-related files
│   └── users.sql               # SQL file to create the `users` table
│
└── README.md                   # Project documentation