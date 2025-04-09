

## Mental Health Chatbot Project
### Role: Quality Assurance Tester

#### Name: Vipin Vishwakarma

### Overview:
The QA Tester ensures the chatbot functions correctly and meets the functional and non-functional requirements. They are critical for delivering a stable and user-friendly experience.

### Key Responsibilities:
- Create test plans and strategies
- Execute manual and automated test cases
- Validate user inputs and chatbot responses
- Log defects with detailed reproduction steps
- Perform regression testing
- Coordinate with the developer for bug resolution

### Testing Types:
- Functional Testing
- Usability Testing
- Load and Stress Testing
- Security Testing
- Accessibility Testing

### Tools Used:
- Selenium, Cypress
- Postman
- JIRA for bug tracking
- TestRail or Google Sheets for test case documentation

### Example Test Case:

| Test ID | Description              | Input           | Expected Output                                       | Status |
|--------|--------------------------|------------------|--------------------------------------------------------|--------|
| TC01   | Test anxiety message     | "I'm anxious"    | "I'm here for you. Would you like to talk about it?"  | Pass   |
| TC02   | Test unsupported command | "/helpme"        | "Sorry, I didn’t understand that. Try rephrasing."     | Pass   |

### Sample Bug Report:

- **Title**: Chatbot crashes when user inputs emoji string
- **Steps to Reproduce**:
  1. Open chatbot
  2. Type in multiple emojis (e.g., "🙂🙂🙂🙂🙂🙂")
  3. Observe crash or unhandled exception
- **Expected Result**: Chatbot should respond gracefully
- **Actual Result**: Application crashes
- **Severity**: High

### Success Metrics:
- 100% coverage of major features
- <5% of critical bugs post-release
- High user satisfaction scores
- Minimal production issues

### Best Practices:
- Test early and often (shift-left testing)
- Automate regression tests
- Document thoroughly and clearly
- Collaborate closely with development

### Daily Workflow:
- Review build updates and change logs
- Run regression suites
- Log bugs and verify fixes
- Participate in daily stand-ups
- Update test documentation and status reports

### Accessibility Considerations:
- Ensure keyboard navigation support
- Verify screen reader compatibility
- Check color contrast and text scaling
