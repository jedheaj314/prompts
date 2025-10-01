# Testing Strategy Prompt

Create comprehensive tests following this strategy:

## Test Levels

1. **Unit Tests**:
   - Test individual functions/methods in isolation
   - Mock external dependencies
   - Cover edge cases and error conditions
   - Aim for high code coverage (80%+)

2. **Integration Tests**:
   - Test interactions between components
   - Verify data flow between modules
   - Test with real dependencies where appropriate

3. **End-to-End Tests**:
   - Test complete user workflows
   - Verify system behavior from user perspective
   - Test critical business paths

## Test Principles

- **AAA Pattern**: Arrange, Act, Assert
- **Clear Test Names**: Should describe what is being tested and expected outcome
- **Independent Tests**: Each test should run independently
- **Fast Execution**: Tests should run quickly
- **Deterministic**: Tests should produce consistent results
- **One Assertion per Test**: Focus on testing one thing at a time (when practical)

## Coverage Goals

- Critical path: 100% coverage
- Business logic: 90%+ coverage
- Overall codebase: 80%+ coverage

## Test Data

- Use meaningful test data
- Include boundary values
- Test with both valid and invalid inputs
- Consider security implications

## Usage

Use this prompt when planning testing approach for new features or improving existing test coverage.
