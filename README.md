DigiEtebar-MVP-Final/
â”‚
â”œâ”€â”€ README.md
â”‚
â”œâ”€â”€ docs/
â”‚   â”œâ”€â”€ SRS_Fa.pdf
â”‚   â”œâ”€â”€ Database_Schema.png
â”‚   â”œâ”€â”€ API_Collection_Postman.json
â”‚   â””â”€â”€ Deployment_Guide.md
â”‚
â”œâ”€â”€ backend/
â”‚   â”œâ”€â”€ app/
â”‚   â”‚   â”œâ”€â”€ Models/
â”‚   â”‚   â”‚   â”œâ”€â”€ User.php
â”‚   â”‚   â”‚   â”œâ”€â”€ CreditRequest.php
â”‚   â”‚   â”‚   â”œâ”€â”€ DigitalContract.php
â”‚   â”‚   â”‚   â”œâ”€â”€ TokenTransaction.php
â”‚   â”‚   â”‚   â””â”€â”€ SystemConfig.php
â”‚   â”‚   â”œâ”€â”€ Http/
â”‚   â”‚   â”‚   â”œâ”€â”€ Controllers/
â”‚   â”‚   â”‚   â”‚   â”œâ”€â”€ AuthController.php
â”‚   â”‚   â”‚   â”‚   â”œâ”€â”€ CreditController.php
â”‚   â”‚   â”‚   â”‚   â””â”€â”€ PaymentController.php
â”‚   â”‚   â”‚   â””â”€â”€ Middleware/
â”‚   â”‚   â”‚       â””â”€â”€ VerifyApiKey.php
â”‚   â”‚   â”œâ”€â”€ Services/
â”‚   â”‚   â”‚   â”œâ”€â”€ InterestCalculator.php
â”‚   â”‚   â”‚   â”œâ”€â”€ KycService.php
â”‚   â”‚   â”‚   â”œâ”€â”€ SmsService.php
â”‚   â”‚   â”‚   â””â”€â”€ ContractPdfGenerator.php
â”‚   â”‚   â””â”€â”€ Jobs/
â”‚   â”‚       â””â”€â”€ SendContractToMainHost.php
â”‚   â”œâ”€â”€ config/
â”‚   â”‚   â”œâ”€â”€ app.php
â”‚   â”‚   â”œâ”€â”€ database.php
â”‚   â”‚   â””â”€â”€ services.php
â”‚   â”œâ”€â”€ database/
â”‚   â”‚   â”œâ”€â”€ migrations/
â”‚   â”‚   â”‚   â”œâ”€â”€ 2025_01_01_000000_create_users_table.php
â”‚   â”‚   â”‚   â”œâ”€â”€ 2025_01_01_000001_create_credit_requests_table.php
â”‚   â”‚   â”‚   â”œâ”€â”€ 2025_01_01_000002_create_digital_contracts_table.php
â”‚   â”‚   â”‚   â”œâ”€â”€ 2025_01_01_000003_create_token_transactions_table.php
â”‚   â”‚   â”‚   â”œâ”€â”€ 2025_01_01_000004_create_installments_table.php
â”‚   â”‚   â”‚   â”œâ”€â”€ 2025_01_01_000005_create_payment_transactions_table.php
â”‚   â”‚   â”‚   â”œâ”€â”€ 2025_01_01_000006_create_system_configs_table.php
â”‚   â”‚   â”‚   â”œâ”€â”€ 2025_01_01_000007_create_api_audit_logs_table.php
â”‚   â”‚   â”‚   â””â”€â”€ 2025_01_01_000008_create_system_health_checks_table.php
â”‚   â”‚   â””â”€â”€ seeders/
â”‚   â”‚       â”œâ”€â”€ SystemConfigSeeder.php
â”‚   â”‚       â””â”€â”€ UsersTableSeeder.php
â”‚   â”œâ”€â”€ routes/
â”‚   â”‚   â”œâ”€â”€ api.php
â”‚   â”‚   â””â”€â”€ web.php
â”‚   â”œâ”€â”€ .env.example
â”‚   â”œâ”€â”€ .gitignore
â”‚   â”œâ”€â”€ composer.json
â”‚   â”œâ”€â”€ artisan
â”‚   â””â”€â”€ phpunit.xml
â”‚
â”œâ”€â”€ frontend/
â”‚   â”œâ”€â”€ public/
â”‚   â”‚   â””â”€â”€ index.html
â”‚   â”œâ”€â”€ src/
â”‚   â”‚   â”œâ”€â”€ api/
â”‚   â”‚   â”‚   â””â”€â”€ axios.js
â”‚   â”‚   â”œâ”€â”€ components/
â”‚   â”‚   â”‚   â”œâ”€â”€ Header.jsx
â”‚   â”‚   â”‚   â”œâ”€â”€ Footer.jsx
â”‚   â”‚   â”‚   â””â”€â”€ SignaturePad.jsx
â”‚   â”‚   â”œâ”€â”€ pages/
â”‚   â”‚   â”‚   â”œâ”€â”€ LandingPage.jsx
â”‚   â”‚   â”‚   â”œâ”€â”€ Register.jsx
â”‚   â”‚   â”‚   â”œâ”€â”€ Dashboard.jsx
â”‚   â”‚   â”‚   â”œâ”€â”€ CreditCalculator.jsx
â”‚   â”‚   â”‚   â””â”€â”€ ContractSign.jsx
â”‚   â”‚   â”œâ”€â”€ styles/
â”‚   â”‚   â”‚   â””â”€â”€ tailwind.css
â”‚   â”‚   â”œâ”€â”€ App.jsx
â”‚   â”‚   â”œâ”€â”€ index.jsx
â”‚   â”‚   â””â”€â”€ routes.jsx
â”‚   â”œâ”€â”€ .env.example
â”‚   â”œâ”€â”€ .gitignore
â”‚   â”œâ”€â”€ package.json
â”‚   â”œâ”€â”€ package-lock.json
â”‚   â”œâ”€â”€ tailwind.config.js
â”‚   â””â”€â”€ vite.config.js
â”‚
â”œâ”€â”€ scripts/
â”‚   â”œâ”€â”€ setup.sh
â”‚   â””â”€â”€ generate_encryption_key.php
â”‚
â”œâ”€â”€ license/
â”‚   â”œâ”€â”€ Copyright_Notice.txt
â”‚   â””â”€â”€ NDA_Template.docx
â”‚
â””â”€â”€ .gitignore
