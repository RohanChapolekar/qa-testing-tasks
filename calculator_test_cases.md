# Test Cases for Simple Calculator Application

---

## TC-001: Addition of Two Positive Integers

**Test Case ID:** TC-001  
**Test Description:** Verify that the calculator correctly adds two positive integers.  
**Preconditions:** Calculator application is open and ready for input.

**Test Steps:**
1. Enter `5` as the first number
2. Select the `+` (Add) operator
3. Enter `3` as the second number
4. Press `=`

**Expected Result:** Output displays `8`

---

## TC-002: Addition of Two Negative Numbers

**Test Case ID:** TC-002  
**Test Description:** Verify that the calculator correctly adds two negative numbers.  
**Preconditions:** Calculator application is open and ready for input.

**Test Steps:**
1. Enter `-4` as the first number
2. Select the `+` (Add) operator
3. Enter `-6` as the second number
4. Press `=`

**Expected Result:** Output displays `-10`

---

## TC-003: Addition of Positive and Negative Number

**Test Case ID:** TC-003  
**Test Description:** Verify that the calculator correctly adds a positive and a negative number.  
**Preconditions:** Calculator application is open and ready for input.

**Test Steps:**
1. Enter `10` as the first number
2. Select the `+` (Add) operator
3. Enter `-4` as the second number
4. Press `=`

**Expected Result:** Output displays `6`

---

## TC-004: Subtraction of Two Positive Numbers

**Test Case ID:** TC-004  
**Test Description:** Verify that the calculator correctly subtracts two positive numbers.  
**Preconditions:** Calculator application is open and ready for input.

**Test Steps:**
1. Enter `9` as the first number
2. Select the `-` (Subtract) operator
3. Enter `4` as the second number
4. Press `=`

**Expected Result:** Output displays `5`

---

## TC-005: Subtraction Resulting in Negative Value

**Test Case ID:** TC-005  
**Test Description:** Verify that the calculator correctly handles subtraction that results in a negative number.  
**Preconditions:** Calculator application is open and ready for input.

**Test Steps:**
1. Enter `3` as the first number
2. Select the `-` (Subtract) operator
3. Enter `8` as the second number
4. Press `=`

**Expected Result:** Output displays `-5`

---

## TC-006: Subtraction with Decimal Numbers

**Test Case ID:** TC-006  
**Test Description:** Verify subtraction works correctly with decimal values.  
**Preconditions:** Calculator application is open and ready for input.

**Test Steps:**
1. Enter `9.5` as the first number
2. Select the `-` (Subtract) operator
3. Enter `4.2` as the second number
4. Press `=`

**Expected Result:** Output displays `5.3`

---

## TC-007: Multiplication of Two Positive Integers

**Test Case ID:** TC-007  
**Test Description:** Verify that the calculator correctly multiplies two positive integers.  
**Preconditions:** Calculator application is open and ready for input.

**Test Steps:**
1. Enter `6` as the first number
2. Select the `×` (Multiply) operator
3. Enter `7` as the second number
4. Press `=`

**Expected Result:** Output displays `42`

---

## TC-008: Multiplication with Zero

**Test Case ID:** TC-008  
**Test Description:** Verify that multiplying any number by zero returns zero.  
**Preconditions:** Calculator application is open and ready for input.

**Test Steps:**
1. Enter `999` as the first number
2. Select the `×` (Multiply) operator
3. Enter `0` as the second number
4. Press `=`

**Expected Result:** Output displays `0`

---

## TC-009: Multiplication of Two Negative Numbers

**Test Case ID:** TC-009  
**Test Description:** Verify that multiplying two negative numbers returns a positive result.  
**Preconditions:** Calculator application is open and ready for input.

**Test Steps:**
1. Enter `-5` as the first number
2. Select the `×` (Multiply) operator
3. Enter `-3` as the second number
4. Press `=`

**Expected Result:** Output displays `15`

---

## TC-010: Division of Two Positive Numbers

**Test Case ID:** TC-010  
**Test Description:** Verify that the calculator correctly divides two positive integers.  
**Preconditions:** Calculator application is open and ready for input.

**Test Steps:**
1. Enter `20` as the first number
2. Select the `÷` (Divide) operator
3. Enter `4` as the second number
4. Press `=`

**Expected Result:** Output displays `5`

---

## TC-011: Division Resulting in Decimal

**Test Case ID:** TC-011  
**Test Description:** Verify that division producing a decimal result is handled correctly.  
**Preconditions:** Calculator application is open and ready for input.

**Test Steps:**
1. Enter `7` as the first number
2. Select the `÷` (Divide) operator
3. Enter `2` as the second number
4. Press `=`

**Expected Result:** Output displays `3.5`

---

## TC-012: BODMAS / Order of Operations

**Test Case ID:** TC-012  
**Test Description:** Verify that the calculator follows BODMAS rules (multiplication before addition).  
**Preconditions:** Calculator supports expression input.

**Test Steps:**
1. Enter the expression `2 + 3 × 4`
2. Press `=`

**Expected Result:** Output displays `14` (not `20` — multiplication is performed before addition)

---

## TC-013: Division by Zero (Invalid Input)

**Test Case ID:** TC-013  
**Test Description:** Verify the calculator handles division by zero gracefully without crashing.  
**Preconditions:** Calculator application is open and ready for input.

**Test Steps:**
1. Enter `10` as the first number
2. Select the `÷` (Divide) operator
3. Enter `0` as the second number
4. Press `=`

**Expected Result:** An error message is displayed such as `"Cannot divide by zero"` or `"Error"`. The application does not crash.

---

## TC-014: Non-Numeric Input — Alphabetic Characters (Invalid Input)

**Test Case ID:** TC-014  
**Test Description:** Verify the calculator rejects alphabetic characters as input.  
**Preconditions:** Calculator application is open and ready for input.

**Test Steps:**
1. Try typing `abc` into the number input field
2. Press `=`

**Expected Result:** Input is blocked or an error message is shown such as `"Invalid Input"`. The application does not crash.

---

## TC-015: Non-Numeric Input — Special Characters (Invalid Input)

**Test Case ID:** TC-015  
**Test Description:** Verify the calculator rejects special characters as input.  
**Preconditions:** Calculator application is open and ready for input.

**Test Steps:**
1. Try typing `@#$` into the number input field
2. Press `=`

**Expected Result:** Input is blocked or an error message is shown such as `"Invalid Input"`. The application does not crash.

---

## TC-016: Large Number Multiplication

**Test Case ID:** TC-016  
**Test Description:** Verify the calculator handles large numbers without overflow or crash.  
**Preconditions:** Calculator application is open and ready for input.

**Test Steps:**
1. Enter `999999` as the first number
2. Select the `×` (Multiply) operator
3. Enter `999999` as the second number
4. Press `=`

**Expected Result:** Output displays `999998000001` correctly without overflow or application crash.

---

## TC-017: Decimal Addition

**Test Case ID:** TC-017  
**Test Description:** Verify that the calculator correctly adds two decimal numbers.  
**Preconditions:** Calculator application is open and ready for input.

**Test Steps:**
1. Enter `1.5` as the first number
2. Select the `+` (Add) operator
3. Enter `2.5` as the second number
4. Press `=`

**Expected Result:** Output displays `4.0` or `4`

---

## TC-018: Repeated Operations (Chaining)

**Test Case ID:** TC-018  
**Test Description:** Verify that the calculator can perform multiple consecutive operations correctly.  
**Preconditions:** Calculator application is open and ready for input.

**Test Steps:**
1. Enter `5`
2. Select `+`
3. Enter `3`
4. Press `=` (Result: `8`)
5. Select `×`
6. Enter `2`
7. Press `=`

**Expected Result:** Output displays `16`

---

## Summary Table

| TC ID  | Operation        | Input            | Expected Result        | Input Type |
|--------|------------------|------------------|------------------------|------------|
| TC-001 | Addition         | 5 + 3            | 8                      | Valid      |
| TC-002 | Addition         | -4 + (-6)        | -10                    | Valid      |
| TC-003 | Addition         | 10 + (-4)        | 6                      | Valid      |
| TC-004 | Subtraction      | 9 - 4            | 5                      | Valid      |
| TC-005 | Subtraction      | 3 - 8            | -5                     | Valid      |
| TC-006 | Subtraction      | 9.5 - 4.2        | 5.3                    | Valid      |
| TC-007 | Multiplication   | 6 × 7            | 42                     | Valid      |
| TC-008 | Multiplication   | 999 × 0          | 0                      | Valid      |
| TC-009 | Multiplication   | -5 × -3          | 15                     | Valid      |
| TC-010 | Division         | 20 ÷ 4           | 5                      | Valid      |
| TC-011 | Division         | 7 ÷ 2            | 3.5                    | Valid      |
| TC-012 | BODMAS           | 2 + 3 × 4        | 14                     | Valid      |
| TC-013 | Division by Zero | 10 ÷ 0           | Error message          | Invalid    |
| TC-014 | Non-Numeric      | abc + 1          | Invalid input error    | Invalid    |
| TC-015 | Special Chars    | @#$ + 1          | Invalid input error    | Invalid    |
| TC-016 | Large Numbers    | 999999 × 999999  | 999998000001           | Valid      |
| TC-017 | Decimal Addition | 1.5 + 2.5        | 4                      | Valid      |
| TC-018 | Chained Ops      | (5+3) × 2        | 16                     | Valid      |

---

*Test Cases prepared for: Simple Calculator Application*  
*Covers: Addition, Subtraction, Multiplication, Division, BODMAS, Valid & Invalid Inputs*
