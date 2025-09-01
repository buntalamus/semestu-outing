# SEMESTU-Outing Backend

## Setup
1. Install dependencies
   ```bash
   npm install
2. Copy .env.example → .env and fill in Railway MySQL credentials.
3. CREATE TABLE users (
  id INT AUTO_INCREMENT PRIMARY KEY,
  name VARCHAR(100) NOT NULL,
  email VARCHAR(120) NOT NULL UNIQUE,
  password VARCHAR(255) NOT NULL,
  role ENUM('pelajar','warden','admin') DEFAULT 'pelajar',
  created_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP
);
4.npm run dev
