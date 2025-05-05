# 🧪 Test Cases – Installation and User Flow for Discord™ Blur Chrome Extension

## 🔍 Extension Discovery and Installation

| Test Case ID | Test Scenario | Steps | Expected Result | Status |
|--------------|---------------|-------|------------------|--------|
| TC-INSTALL-001 | Search in Google | 1. Open Google  
2. Search "Discord Blur Chrome Extension" | Top result should show Chrome Web Store link for "Discord Blur" | ✅ |
| TC-INSTALL-002 | Open Chrome Web Store page | Click the link from search results | Extension page loads with title, overview, and "Add to Chrome" button | ✅ |
| TC-INSTALL-003 | Install Extension | Click "Add to Chrome" > Confirm in popup | Extension installs successfully and appears in Chrome Extensions bar | ✅ |

## ⚙️ Initial Setup and Configuration

| Test Case ID | Test Scenario | Steps | Expected Result | Status |
|--------------|---------------|-------|------------------|--------|
| TC-SETUP-001 | Launch Extension | Click on extension icon > Select "Disblur" | Settings page loads with options checklist | ✅ |
| TC-SETUP-002 | Toggle options | Check/uncheck "Blur Server Icons", etc. | Checkbox states reflect changes | ✅ |
| TC-SETUP-003 | Save Settings | Modify an option > Click Save | Settings saved and confirmed | ⚠️ Save button visibility is poor |
