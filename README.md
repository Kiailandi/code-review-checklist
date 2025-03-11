# **Condensed Code Review Checklist**

## **Implementation & Design**
- [ ] Does the code accomplish its intended purpose effectively?  
- [ ] Is the solution simple, modular, and maintainable?  
- [ ] Does it reuse existing functionality instead of duplicating code?  
- [ ] Is it at the right abstraction level and adheres to design principles (SOLID, DRY, KISS)?  

## **Logic & Error Handling**
- [ ] Can you think of any cases where the code might fail or behave unexpectedly?  
- [ ] Are edge cases and unexpected inputs handled properly?  
- [ ] Is error handling appropriate and logging sufficient for debugging?  

## **Security & Privacy**
- [ ] Does the code introduce security vulnerabilities (e.g., XSS, SQL injection)?  
- [ ] Is user input validated, sanitized, and escaped?  
- [ ] Are authentication and authorization handled securely?  
- [ ] Does it expose sensitive data (e.g., passwords, API keys)?  

## **Performance & Dependencies**
- [ ] Could the code negatively impact performance? Are there obvious optimizations?  
- [ ] Does it introduce unnecessary dependencies or external services?  
- [ ] Are there potential compatibility or backward compatibility issues?  

## **Testing & Readability**
- [ ] Is the code covered by automated tests (unit, integration, system)?  
- [ ] Are there additional test cases that should be added?  
- [ ] Is the code easy to read and understand?  
- [ ] Do function and variable names clearly describe their purpose?  
- [ ] Are comments helpful, necessary, and up to date?  

## **Ethics & Usability**
- [ ] Does the change raise privacy, fairness, or ethical concerns?  
- [ ] Is the API/UI intuitive, accessible, and well-documented?  

## **Final Review**
- [ ] Should a domain expert (e.g., security, UX) review this code?  
- [ ] Could this change impact other teams or systems?  
