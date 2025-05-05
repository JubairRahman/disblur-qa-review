# 🧪 Test Cases – UI/UX for Discord™ Blur Chrome Extension

## 🎨 UI Layout and Design

| Test Case ID | Test Scenario        | Steps                                 | Expected Result                                      | Status |
|--------------|----------------------|---------------------------------------|------------------------------------------------------|--------|
| TC-UIUX-001  | Check Extension Icon | 1. Look at extension icon             | Icon should be clear and recognizable                 | ✅     |
| TC-UIUX-002  | Settings Page Layout  | 1. Open extension > Go to settings    | Settings page should be well-organized and readable   | ✅     |
| TC-UIUX-003  | Consistency in Design | 1. Check colors, fonts, and spacing  | Consistent design elements across settings           | ✅     |

## 🎮 User Interaction

| Test Case ID | Test Scenario        | Steps                                 | Expected Result                                     | Status |
|--------------|----------------------|---------------------------------------|-----------------------------------------------------|--------|
| TC-UIUX-004  | Button Functionality  | 1. Click "Save" button                | Button should show clear feedback (change color, text) | ⚠️ Save button visibility is poor |
| TC-UIUX-005  | Accessibility        | 1. Navigate settings with keyboard    | All settings should be accessible via keyboard       | ✅     |
| TC-UIUX-006  | Tooltip Visibility   | Hover over buttons and options        | Tooltips should be visible for clarity               | ✅     |

## 🧑‍💻 User Feedback

| Test Case ID | Test Scenario        | Steps                                 | Expected Result                                      | Status |
|--------------|----------------------|---------------------------------------|------------------------------------------------------|--------|
| TC-UIUX-007  | Save Confirmation    | 1. Modify a setting > Click "Save"    | Visual confirmation or message appears after save    | ⚠️ Missing feedback after save |

---

## 🧪 Additional Notes

- The extension’s UI is user-friendly, but feedback on certain actions (like saving settings) is unclear.
- The Save button needs improvement in visibility and feedback.
