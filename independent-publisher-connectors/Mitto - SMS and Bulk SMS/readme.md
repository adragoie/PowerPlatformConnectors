# Mitto SMS & Bulk SMS

Mitto’s SMS and Bulk SMS connector allows you to send individual or bulk SMS messages securely and efficiently. It supports message customization and usage reporting by country—making it ideal for marketing, alerts, and transactional messaging.

## Publisher: Alessandro Drago, Impresoft Engage

## Prerequisites
You must have an active Mitto account. To get started, visit [Mitto](https://www.mitto.ch/) and request API access. Some features may require activation by your account manager.

## Obtaining Credentials
Once your account is active, you can retrieve your API key from the Mitto dashboard. All API requests must include the `X-Mitto-API-Key` header for authentication.

## Supported Operations

### Send SMS
Send a single SMS message to a recipient. Supports long messages, Unicode, flash SMS, test mode, and reference tagging.

### Send Bulk SMS
Send the same SMS message to multiple recipients in one API call. Each recipient receives a unique message ID.

### Usage by Country
Retrieve usage statistics by country for a specified date range and account name.

## Known Issues and Limitations
There are no known issues at this time. Some advanced features may require prior activation by Mitto support.