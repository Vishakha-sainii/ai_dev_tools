---
source: https://github.com/hamzafer/cursor-commands/blob/main/.cursor/commands/add-error-handling.md
---

# Code Review

## Objective

Perform a comprehensive code review for a Spring Boot application.

Review functionality, architecture, maintainability, security, performance, testing, and adherence to project standards.

Provide findings categorized as:

- Critical
- High
- Medium
- Low
- Suggestions

---

## Review Process

### 1. Functional Review

Verify:

- Requirements are implemented correctly
- Business logic is accurate
- Edge cases are handled
- Error scenarios are covered
- Logging is meaningful

---

### 2. Architecture Review

Verify:

- Layered architecture is respected
- Controllers contain no business logic
- Services contain business logic
- Repositories contain data access logic only
- Proper separation of concerns

Check for:

- High cohesion
- Low coupling
- SOLID principles

---

### 3. Spring Boot Review

Verify:

- Constructor injection is used
- No field injection
- Proper use of annotations
- Proper transaction boundaries
- Proper validation using @Valid
- Configuration externalized in application.yml

Check:

- Spring Boot best practices
- Dependency injection patterns
- Bean lifecycle considerations

---

### 4. API Review

Verify:

- REST conventions followed
- Correct HTTP methods
- Proper status codes
- DTO usage
- Consistent request/response structures
- Pagination where required

---

### 5. Persistence Review

Verify:

- JPA mappings are correct
- Queries are optimized
- N+1 query risks identified
- Indexes exist where needed
- Proper transaction handling

Check:

- Lazy vs eager loading
- Repository method efficiency

---

### 6. Security Review

Verify:

- Input validation
- Sensitive data protection
- No credentials in code
- Proper exception handling
- No information leakage

Check:

- Injection vulnerabilities
- Authentication/authorization concerns
- Data exposure risks

---

### 7. Performance Review

Verify:

- No unnecessary database calls
- No duplicate computations
- Efficient collection usage
- Proper pagination

Identify:

- Bottlenecks
- Scalability risks
- Memory concerns

---

### 8. Testing Review

Verify:

- Unit tests exist
- Happy paths covered
- Validation scenarios covered
- Exception scenarios covered
- Edge cases covered

Review:

- Test readability
- Mocking strategy
- Coverage gaps

---

### 9. Documentation Review

Verify:

- API documentation updated
- Design decisions documented
- README updated where required

---

## Output Format

For every finding provide:

### Severity

Critical | High | Medium | Low | Suggestion

### Location

Class / Method / File

### Issue

Describe the problem.

### Impact

Explain why it matters.

### Recommendation

Provide a concrete fix.

---

## Final Summary

Provide:

- Overall Assessment
- Key Risks
- Recommended Improvements
- Production Readiness Score (1-10)