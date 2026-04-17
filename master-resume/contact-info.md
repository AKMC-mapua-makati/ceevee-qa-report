# Contact Info Test Cases

| Test ID | Test Title | Description | Steps | Expected Output | Status |
|--------|------------|-------------|-------|----------------|--------|
| TC-01 | Email Check | Validate email format | 1. Enter email abc@ 2. Save | Should block invalid email or show validation message | Failed |
| TC-02 | Phone Field | Validate phone input | 1. Enter asd123 2. Save | Only numeric input should be accepted | Failed |
| TC-03 | URL Field | Validate URL format | 1. Enter github/test 2. Save | Must accept valid URL format only | Passed |
