# Secure Web Application

## Security Measures Implemented

### Authentication
- JWT with 1-hour expiry
- BCrypt password hashing
- AES encryption for sensitive data

### Headers
- CSP, X-Frame-Options, XSS Protection
- HSTS (via HTTPS)

### Validation
- Input validation on all endpoints
- Output encoding

## Deployment

1. Clone repository
2. Set environment variables:
   - `JWT_SECRET` - 32+ character secret
   - `DB_CONNECTION` - Database connection string
3. Run `dotnet run`

## Threat Model
See [docs/STRIDE_Threat_Model.md](docs/STRIDE_Threat_Model.md)

## Risk Assessment
See [docs/DREAD_Risk_Assessment.md](docs/DREAD_Risk_Assessment.md)