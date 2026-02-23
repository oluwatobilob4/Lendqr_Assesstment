Here’s a clean, styled, professional **GitHub-ready README description** you can paste directly into your repository:

---

# 🚀 Capital Credit – Adjutor API Automation (Task 2)

This repository contains automated API test scripts developed as part of the QA assessment of the **Adjutor platform** for integration into the **Capital Cash** application.

The automation was built using **Postman** and validates:

* ✅ HTTP status codes
* ✅ Response messages
* ✅ Basic response structure integrity

The goal of this automation is to ensure endpoint reliability, response consistency, and readiness for production integration.

---

# 🛠 Setup Guide

## Step 1: Import the Collection

1. Open **Postman**
2. Click **Import**
3. Upload the file:

```
NIGERIAN COUNTRY SPECIFIC ENDPOINT.postman_collection.json
```

---

## Step 2: Configure Collection Variables

Navigate to:

```
Collection → Variables
```

Ensure the following variables are properly configured:

| Variable   | Description                       |
| ---------- | --------------------------------- |
| `base_url` | Base API URL                      |
| `token`    | API token used for authentication |

⚠️ The `token` must be a valid API key generated from the app created on Adjutor.

---

## Step 3: Run the Collection

1. Select the collection
2. Click **Run**
3. Click **Run NIGERIAN COUNTRY SPECIFIC ENDPOINT.postman_collection**

---

# 📊 Expected Output

Upon execution, the runner will display:

* ✔ Validation of HTTP status codes
* ✔ Validation of response messages
* ✔ Assertion results per endpoint
* ✔ Execution summary showing:

  * Total tests
  * Passed tests
  * Failed tests

---

# 📌 Automation Coverage

The collection includes:

* Authentication handling (via token variable)
* Automated assertions per request
* Structured validation for multiple Nigerian country-specific endpoints
* Error response verification where applicable

---

# 🔍 Purpose of This Automation

This automation demonstrates:

* API response correctness
* Error handling classification
* Stability of external endpoints
* Integration readiness for Capital Cash

---

