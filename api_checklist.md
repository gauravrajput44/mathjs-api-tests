# API Testing Checklist for [mathjs](https://api.mathjs.org/)
This file provides a high-level checklist for API testing of the [mathjs](https://api.mathjs.org/) service.

## 1. Basic Health Checks
- [ ] API base URL accessibility
- [ ] Response time validation (< 1000ms)
- [ ] Content-type headers verification (application/json)

## 2. Functional Testing

### Basic Operations
- [ ] Simple arithmetic (+, -, *, /, ^)
- [ ] Order of operations [PEMDAS](https://www.mathsisfun.com/operation-order-pemdas.html)
- [ ] Parentheses handling
- [ ] Variable assignments and references

### Advanced Mathematical Functions
- [ ] Trigonometric (sin, cos, tan)
- [ ] Logarithmic (log, ln)
- [ ] Constants (pi, e)
- [ ] Matrix operations
- [ ] Unit conversions
- [ ] Complex numbers

### Input Validation
- [ ] URL encoding
- [ ] Precision parameter handling
- [ ] Special characters (%,$,&)
- [ ] Array of expressions
- [ ] Variable persistence across expressions

### Edge Cases
- [ ] Very large numbers
- [ ] Very small numbers (near zero)
- [ ] Negative numbers
- [ ] Division by zero
- [ ] Invalid expressions
- [ ] Floating-point precision

## 3. Error Handling
- [ ] Invalid syntax (unclosed parentheses)
- [ ] Unsupported operations
- [ ] Invalid data types
- [ ] HTTP status codes verification
- [ ] Error message clarity

## 4. Performance Testing
- [ ] Response time for varying complexity
- [ ] Concurrent request handling
- [ ] Recovery from high load

## 5. Security
- [ ] Input sanitization
- [ ] Rate limiting
- [ ] CORS policy validation
