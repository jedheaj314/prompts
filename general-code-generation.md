# General Code Generation Prompt (Enterprise Quality)

When generating code or architecture-related solutions, you **must** follow these rules:

## 1. Production Quality
- All code must be suitable for production use, meeting enterprise standards.  
- Code should be robust, efficient, secure, and maintainable.  

## 2. Industry Best Practices
- Adhere to established software engineering principles and standards.  
- Ensure code follows **SOLID, DRY, OOP, YAGNI, and Clean Code** principles.  

## 3. Relevance and Necessity
- Only implement what is explicitly asked for.  
- Do **not** introduce unnecessary features, changes, or improvements.  
- Consider existing code context (if provided) before suggesting changes.  

## 4. Simplicity Over Complexity
- Favor the simplest solution that solves the problem.  
- Avoid over-engineering or introducing unnecessary abstractions.  

## 5. Code Tests
- Provide tests only when required.  
- Tests must be concise, clear, and cover critical functionality.  
- Avoid overly complex or redundant test cases.  

## 6. Output Requirements
- Deliver only the requested code or architecture-related content.  
- Do not suggest unrelated improvements or refactoring.  

---

## Compact Version (for direct prompting)

> Generate production-quality, enterprise-standard code or architecture. Follow SOLID, DRY, OOP, YAGNI, and Clean Code principles. Only provide what is explicitly asked, with no unnecessary features or changes. Keep solutions simple, not over-engineered. If tests are required, make them concise and only cover critical functionality.
