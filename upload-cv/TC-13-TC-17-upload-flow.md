
# Upload CV Test Cases

| Test ID | Test Title | Description | Steps | Expected Output | Status |
|--------|------------|-------------|-------|----------------|--------|
| TC-13 | File Upload | Upload PDF/DOCX | 1. Upload file 2. Extract data | File should upload and extract correctly | Passed |
| TC-14 | Invalid File Type | Reject unsupported files | 1. Upload PNG/TXT | Upload should be blocked | Passed |
| TC-15 | Drag and Drop | Drag and drop upload | 1. Drag file into area | File should upload successfully | Passed |
| TC-16 | Interrupted Upload | Interrupt upload process | 1. Start upload 2. Disconnect | Upload should stop safely | Passed |
| TC-17 | Loading State | Check upload loading UI | 1. Upload file | Loading indicator should appear | Failed |
