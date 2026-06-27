DigiEtebar-MVP-Final/
│
├── README.md
│
├── docs/
│   ├── SRS_Fa.pdf
│   ├── Database_Schema.png
│   ├── API_Collection_Postman.json
│   └── Deployment_Guide.md
│
├── backend/
│   ├── app/
│   │   ├── Models/
│   │   │   ├── User.php
│   │   │   ├── CreditRequest.php
│   │   │   ├── DigitalContract.php
│   │   │   ├── TokenTransaction.php
│   │   │   └── SystemConfig.php
│   │   ├── Http/
│   │   │   ├── Controllers/
│   │   │   │   ├── AuthController.php
│   │   │   │   ├── CreditController.php
│   │   │   │   └── PaymentController.php
│   │   │   └── Middleware/
│   │   │       └── VerifyApiKey.php
│   │   ├── Services/
│   │   │   ├── InterestCalculator.php
│   │   │   ├── KycService.php
│   │   │   ├── SmsService.php
│   │   │   └── ContractPdfGenerator.php
│   │   └── Jobs/
│   │       └── SendContractToMainHost.php
│   ├── config/
│   │   ├── app.php
│   │   ├── database.php
│   │   └── services.php
│   ├── database/
│   │   ├── migrations/
│   │   │   ├── 2025_01_01_000000_create_users_table.php
│   │   │   ├── 2025_01_01_000001_create_credit_requests_table.php
│   │   │   ├── 2025_01_01_000002_create_digital_contracts_table.php
│   │   │   ├── 2025_01_01_000003_create_token_transactions_table.php
│   │   │   ├── 2025_01_01_000004_create_installments_table.php
│   │   │   ├── 2025_01_01_000005_create_payment_transactions_table.php
│   │   │   ├── 2025_01_01_000006_create_system_configs_table.php
│   │   │   ├── 2025_01_01_000007_create_api_audit_logs_table.php
│   │   │   └── 2025_01_01_000008_create_system_health_checks_table.php
│   │   └── seeders/
│   │       ├── SystemConfigSeeder.php
│   │       └── UsersTableSeeder.php
│   ├── routes/
│   │   ├── api.php
│   │   └── web.php
│   ├── .env.example
│   ├── .gitignore
│   ├── composer.json
│   ├── artisan
│   └── phpunit.xml
│
├── frontend/
│   ├── public/
│   │   └── index.html
│   ├── src/
│   │   ├── api/
│   │   │   └── axios.js
│   │   ├── components/
│   │   │   ├── Header.jsx
│   │   │   ├── Footer.jsx
│   │   │   └── SignaturePad.jsx
│   │   ├── pages/
│   │   │   ├── LandingPage.jsx
│   │   │   ├── Register.jsx
│   │   │   ├── Dashboard.jsx
│   │   │   ├── CreditCalculator.jsx
│   │   │   └── ContractSign.jsx
│   │   ├── styles/
│   │   │   └── tailwind.css
│   │   ├── App.jsx
│   │   ├── index.jsx
│   │   └── routes.jsx
│   ├── .env.example
│   ├── .gitignore
│   ├── package.json
│   ├── package-lock.json
│   ├── tailwind.config.js
│   └── vite.config.js
│
├── scripts/
│   ├── setup.sh
│   └── generate_encryption_key.php
│
├── license/
│   ├── Copyright_Notice.txt
│   └── NDA_Template.docx
│
└── .gitignore
