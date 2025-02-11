# CSV-Testing-Report-for-Hackathon

# Test Cases

Below is the list of test cases for the application:

| Test Case ID | Description               | Steps                                      | Expected Result          | Actual Result            | Status  | Severity Level        | Remarks                  |
|--------------|---------------------------|--------------------------------------------|--------------------------|--------------------------|---------|-----------------------|--------------------------|---------
| TC001        | Validate product listing  | Open product page > verify products        | Products displayed       | Products displayed       | Passed  | Medium                | No issues found          |
| TC002        | Test API error handling   | Grouq Querry > Refresh page                | Show fallback message    | Fallback message shown   | Passed  | Low                   | Handled gracefully       |
| TC003        | Check cart functionality  | Add item to cart > verify cart             | Cart updates correctly   | Cart updates correctly   | Passed  | Medium                | Works as expected        |
| TC004        | Test responsiveness layout| Resize window layout > browser check       | Layout adjusts properly  | Layout adjusts properly  | Passed  | Medium                | Responsive verified      | 
