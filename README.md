# Playwright User Management Automation

This repository contains **Playwright Python automation scripts** for testing **User Management** functionality in the OrangeHRM demo site.

---

### Project Setup

Instructions on how to get a copy of the project and running on your local machine.

### 1. Clone the repository

```bash
git clone https://github.com/Subasree2484/playwright-user-management.git
cd playwright-user-management
```

### 2. Create a virtual environment


```bash
python -m venv .venv
```

### 3. Activate the virtual environment
Linux / Mac
```bash
source .venv/bin/activate
```
Linux / Mac
```bash
.venv\Scripts\activate
```
### 4. Install dependencies

```bash
pip install -r requirements.txt
```
### 5. Install Playwright browsers

```bash
playwright install
```



## Running the Test Cases

### Run in headed mode (browser visible)
```bash
pytest --headed
```
### Run in headless mode (browser invisible)
```bash
pytest
```

### Test Cases Included
#### 1. Create User

Adds a new user and verifies it appears in search.

#### 2. Edit User Status

Updates the status of an existing user and validates it.

#### 3. Password Mismatch Validation

Attempts to create a user with mismatched password and verifies the error message.

#### 4. Delete User

Deletes the user and confirms they are removed from the list.

##  Project Structure

The project has the following structure:


``` 
playwright-user-management/
├── tests/
│   └── user_management_test.py
├── requirements.txt
├── pytest.ini
├── .gitignore
└── README.md
```

