# Senior Backend Engineer Test

## Banking Transactions API (Ledger System)

### Overview

Build a banking ledger system that handles financial transactions with ACID compliance and double-entry accounting using MongoDB transactions.

### Core Requirements

1. **Account Management**

   - Create and manage user accounts (It doesn't need to be sophisticated, no need for verifications)
   - Track account balances
   - Support multiple currencies (NGN and USD is fine)
   - Maintain transaction history

2. **Transaction Operations**

   - Handle deposits (CREDIT)
   - Process withdrawals (DEBIT)
   - Support account-to-account transfers
   - Ensure double-entry accounting

3. **Technical Requirements**
   - Use NodeJS, Express, Typescript, MongoDB, and any other libraries of your choice
   - Ensure ACID compliance using MongoDB transactions
   - Implement token-based authentication
   - Fully document all endpoints on Postman
   - Write unit tests for all functionalities
   - Containerize the API using Docker (optional)

## Evaluation Criteria

1. Database design - scalability and query efficiency
2. Clean code - redundancy and documentation
3. Code quality - use of best practices and efficient algorithms
4. Error handling - Appropriate error codes and messages
5. Security - Input validation and/or sanitization
6. Clean commit history

## Submission

Reply with the following:

1. Link to Github repository
2. Link to live API
3. Link to Postman documentation
