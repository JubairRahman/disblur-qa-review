# 🧪 Test Cases – Functional Test Suite for Discord™ Blur Chrome Extension

## 🔍 Extension Core Functionality

| Test Case ID | Test Scenario        | Steps                                | Expected Result                                 | Status |
|--------------|----------------------|--------------------------------------|-------------------------------------------------|--------|
| TC-FUNC-001  | Enable Extension     | 1. Click on the extension icon       | Extension icon becomes highlighted and active    | ✅     |
| TC-FUNC-002  | Blur Server Icons    | 1. Launch Discord 2. Enable "Blur Server Icons" | Server icons should be blurred                   | ✅     |
| TC-FUNC-003  | Toggle Extension     | 1. Click on extension icon > Toggle  | Extension should be toggled off and on correctly | ✅     |
| TC-FUNC-004  | Check Option Persistence | 1. Modify settings > Close browser 2. Reopen extension | Last saved settings should persist                 | ⚠️     |

## ⚙️ Extension Settings Functionality

| Test Case ID | Test Scenario         | Steps                                 | Expected Result                                  | Status |
|--------------|-----------------------|---------------------------------------|--------------------------------------------------|--------|
| TC-FUNC-005  | Reset Settings        | 1. Open settings 2. Click "Reset"     | Settings should revert to default values         | ✅     |
| TC-FUNC-006  | Apply Settings        | 1. Modify settings 2. Click "Save"    | Settings should apply without issues             | ✅     |

---

## 🧪 Additional Notes

- Functional tests ensure the extension’s core features work as expected.
- No critical failures were found in core functionality.
