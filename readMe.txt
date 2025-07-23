
# Identeefi: Anti-Counterfeit Product Identification System

This project is an innovative **anti-counterfeit product identification system** that leverages **blockchain technology** to create a secure and transparent platform for verifying and tracking product authenticity across various industries.

Developed with a full-stack architecture, the system integrates **Solidity** smart contracts, a **React.js** frontend, a **Node.js** backend, and a **PostgreSQL** database for robust **role-based access control**. The smart contract is deployed on the **Ethereum Sepolia Testnet**.

---

## Technologies Used

- **Solidity** – Smart contract development
- **React.js** – Frontend development
- **Node.js** – Backend API and access control
- **PostgreSQL** – Database for user and role management
- **Ethereum (Sepolia Testnet)** – Blockchain deployment
- **MetaMask** – Wallet integration for smart contract interaction

---

## Project Structure

```bash
identeefi/
├── identeefi-postgres-database/      # PostgreSQL schema and data
├── identeefi-backend-node/           # Node.js backend with role-based access
├── identeefi-frontend-react/         # React.js frontend
└── identeefi-smartcontract-solidity/ # Solidity smart contract (Sepolia)
````

---

## Getting Started

### 1. PostgreSQL Database Setup

Navigate to the `identeefi-postgres-database` folder:

```bash
cd identeefi-postgres-database
```

* Create tables:

  * Run the SQL statements in `create_table.txt` using your preferred SQL client.
* Populate tables:

  * Use the provided CSV files to insert initial data into the database.

---

### 2. Backend (Node.js) Setup

Navigate to the backend folder:

```bash
cd identeefi-backend-node
```

* Install dependencies:

  ```bash
  npm install
  ```
* Run the backend server:

  ```bash
  node postgres
  ```

---

### 3. Frontend (React.js) Setup

Navigate to the frontend folder:

```bash
cd identeefi-frontend-react
```

* Install dependencies:

  ```bash
  npm install
  ```
* Start the frontend application:

  ```bash
  npm start
  ```

The application should now be running locally at `http://localhost:3000`.

---

### 4. Smart Contract (Solidity)

The smart contract source code is located in the `identeefi-smartcontract-solidity` folder.

* It has been deployed to the **Ethereum Sepolia Testnet**.
* Make sure you have a **MetaMask** wallet connected to Sepolia Testnet to interact with the smart contract.
* The code is included for reference and demonstration purposes only.

---

## Credits

This project was developed as part of a Final Year Project (FYP).

**Student Developer:** Lo Yen Xuan

---

## 📄 License

This project is intended for academic and research purposes. Please add an appropriate license if used in production or distributed publicly.
