# Exercise 2 - HubSpot API Integration with Error Handling

## Overview

This project demonstrates a production-ready WordPress API integration with:

- HubSpot CRM API
- Input validation & sanitization
- Rate limiting
- Honeypot spam protection
- Backup lead storage in MySQL
- Error logging
- REST API endpoint
- UTM tracking support

---

## Features

### Form Fields
- Full Name
- Email
- Phone
- Company Name
- Message
- UTM Source
- UTM Medium
- UTM Campaign

---

## Security Features

- XSS prevention using sanitization
- SQL injection prevention using `$wpdb`
- Honeypot spam protection
- IP-based rate limiting
- Safe error logging
- API token isolation

---

## API Endpoint

```http
POST /wp-json/custom/v1/lead-submit
