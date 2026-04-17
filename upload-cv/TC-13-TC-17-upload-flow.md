# Upload CV Flow Test Cases

| Test ID | Test Title | Description | Steps | Expected Output | Status |
|--------|------------|-------------|-------|----------------|--------|
| TC-13 | File Upload Functionality | Verify successful upload of supported file types | 1. Upload PDF/DOCX 2. Extract data | File should upload and data should be extracted correctly |  |
| TC-14 | Invalid File Type Handling | Verify rejection of unsupported file formats | 1. Upload PNG/TXT | System should reject unsupported file types |  |
| TC-15 | Drag and Drop Upload | Verify drag-and-drop upload functionality | 1. Drag file into upload area | File should upload successfully |  |
| TC-16 | Interrupted Upload Handling | Verify system behavior on upload interruption | 1. Start upload 2. Disconnect | Upload should fail safely without system crash |  |
| TC-17 | Loading State Indicator | Verify upload loading UI behavior | 1. Upload file | Loading indicator should appear during upload |  |
