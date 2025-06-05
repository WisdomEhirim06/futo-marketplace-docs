# FUTO Marketplace API Documentation

🚀 **Live Documentation**: [View API Docs](https://yourusername.github.io/futo-marketplace-api-docs)

## Quick Links
- **Base URL**: `https://api.futomarketplace.com/v1`
- **Authentication**: JWT Bearer Token
- **Postman Collection**: [Download](./postman/futo-marketplace.json)

## Getting Started

### 1. Authentication
```bash
curl -X POST https://api.futomarketplace.com/v1/auth/login/ \
  -H "Content-Type: application/json" \
  -d '{"username": "your_username", "password": "your_password"}'

  curl -X POST https://api.futomarketplace.com/v1/listings/ \
  -H "Authorization: Bearer YOUR_JWT_TOKEN" \
  -H "Content-Type: application/json" \
  -d '{"title": "iPhone 13", "price": 250000, "type": "product", "category": "Electronics"}'
```

### Changelog
    v1.0.0 (2025-06-05)

    Initial API specification
    Auth, Listings, Orders, Chat, Payments endpoints
    Admin functionality