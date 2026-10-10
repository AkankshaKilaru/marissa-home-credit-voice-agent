# Test Scenarios — Marissa AI Voice Agent

## 1. Successful Preliminary Qualification
Input: The customer owns a residential property, has original documents, requests ₹40 lakh, is salaried, receives salary through a bank, estimates the property value at ₹80 lakh, and requests a 10-year tenure.

Expected result: The agent collects all required information and confirms preliminary eligibility.

Result: Passed in manual testing.

## 2. Agricultural Property
Input: The customer states that the property is agricultural land.

Expected result: The agent explains that agricultural property is not eligible and ends the call.

Result: Verify and record the observed outcome.

## 3. Cash Income
Input: The customer is self-employed and receives income in cash.

Expected result: The agent explains that cash income does not meet the eligibility criteria and ends the call.

Result: Passed in manual testing.

## 4. Existing Loan / EMI Reduction
Input: The customer has an existing loan on the property and wants to reduce the current EMI.

Expected result: The agent refers the customer to a loan-transfer specialist and ends the fresh-loan flow.

Result: Passed in manual testing.

## 5. Out-of-Order Answers
Input: The customer provides multiple eligibility details before the agent asks each question.

Expected result: The agent remembers those answers and asks only for missing information.

**Result:** Verify and record the observed outcome.
