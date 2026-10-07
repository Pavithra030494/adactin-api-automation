# Adactin Hotel Platform - Core API Automation Repo

## 📌 Project Overview
This repository contains the functional test suites, baseline security assertions, and execution artifacts tracking the stability of the **Adactin Hotel Core Web Services Platform**. 

## 🗺️ External Management Integration Anchors
* **Test Case Repository (TestRail):** `Adactin Hotel API Testing Project`
* **Defect Backlog Tracking (Jira):** `adactin API (Project Key: API)`

## 📊 Core API Test Execution Dashboard Matrix

| API Folder Module | Evaluated Scenarios | Passed Loops | Failed Breaks | Operational Defect Identifiers |
| :--- | :---: | :---: | :---: | :--- |
| **Login API** | 12 | 10 | 2 | `API-1` (Auth Bypass), `API-2` (Casing Defect) |
| **Logout API** | 7 | 6 | 1 | `API-3` (HTTP Transport Error Masking) |
| **Search Hotel API** | 5 | 5 | 0 | _None (All functional baselines match criteria)_ |
| **Book Hotel API** | 10 | 7 | 3 | `API-4` (Price Fraud), `API-5` (CVV Breach), `API-6` (Double Billing) |
| **TOTAL METRICS** | **34** | **28** | **6** | **Overall Platform Pass Stability Rate: 82.35%** |

## 🛠️ Local Environment Verification Loop Setup
1. Clone this automation engine directory safely to your local verification node:
   ```bash
   git clone https://github.com
   ```
2. Open your choice API testing core client software wrapper application framework (e.g., **SoapUI** / **Postman**).
3. Select **Import** and target the centralized collection asset files located inside the `/collections` path tracking folder.
