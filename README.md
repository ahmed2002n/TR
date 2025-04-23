# Travel Policy Chatbot

This repository contains a chatbot for validating travel requests against the company's travel policy.

## Features
- OCR integration to extract details from travel request screenshots.
- Policy compliance checks for flights, hotels, and approvals.
- Automated testing and deployment using GitHub Actions.

## Deployment
1. Clone the repository.
2. Install dependencies: `pip install -r requirements.txt`
3. Run the app: `python backend/app.py`

## Example Usage
1. Upload a travel request screenshot via the `/check-travel-request` API.
2. Receive a compliance report with issues flagged.
