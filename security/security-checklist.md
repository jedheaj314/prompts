# Security Best Practices Prompt

Ensure the code follows security best practices:

## Input Validation

- Validate and sanitize all user inputs
- Use parameterized queries to prevent SQL injection
- Validate file uploads (type, size, content)
- Implement proper input length restrictions

## Authentication & Authorization

- Use strong authentication mechanisms
- Implement proper session management
- Follow principle of least privilege
- Use role-based access control (RBAC)
- Implement multi-factor authentication where appropriate

## Data Protection

- Encrypt sensitive data at rest and in transit
- Use HTTPS/TLS for all communications
- Never store passwords in plain text
- Use secure hashing algorithms (bcrypt, Argon2)
- Implement proper key management

## Common Vulnerabilities (OWASP Top 10)

Protect against:
1. Injection attacks (SQL, NoSQL, OS command)
2. Broken authentication
3. Sensitive data exposure
4. XML External Entities (XXE)
5. Broken access control
6. Security misconfiguration
7. Cross-Site Scripting (XSS)
8. Insecure deserialization
9. Using components with known vulnerabilities
10. Insufficient logging and monitoring

## Secrets Management

- Never commit secrets to version control
- Use environment variables or secret management services
- Rotate credentials regularly
- Implement proper access controls for secrets

## Error Handling

- Don't expose sensitive information in error messages
- Log security events appropriately
- Implement proper error handling without revealing system details

## Dependencies

- Keep dependencies up-to-date
- Regularly scan for known vulnerabilities
- Use only trusted and maintained libraries

## Usage

Use this prompt when implementing security features or reviewing code for security vulnerabilities.
