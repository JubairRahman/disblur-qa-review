# 👁 Usability Review – Disblur Chrome Extension

## 🔍 Overview
This document reviews the **user experience (UX)** and **usability** of the Disblur Chrome Extension, based on real usage during testing and screen sharing scenarios.

---

## 🧩 1. Confusing Settings UI

### ❌ Problem:
The settings page presents multiple toggle options like:

```yaml

However:
- It's unclear whether toggles are active or not (no visual confirmation).
- The **"Save" button** is barely visible due to styling.
- No feedback or message is shown after clicking "Save".

### ✅ Suggestions:
- Use clearer **toggle states** (e.g., ON/OFF labels, checkmarks, or switches).
- Improve **"Save" button styling**: use contrasting background, hover effects.
- Show **a toast message** like: _“Settings Saved Successfully”_.

---

## 👁 2. Preview/Live Feedback Issues

### ❌ Problem:
- Changes in settings are not reflected in real time.
- User has to guess if a setting is applied.

### ✅ Suggestions:
- Add **live preview pane** or reload Discord tab automatically after saving.
- Show temporary labels like _“Channel names are now blurred”_.

---

## 🎨 3. Visual Design Concerns

| Area | Issue | Suggestion |
|------|-------|------------|
| UI Font | Looks default/system font | Use consistent typography |
| Layout | Spacing is inconsistent | Use margins between sections |
| Icons | No icons used | Add small icons for each option to help identify |

---

## 📱 4. Accessibility Suggestions

- Add **hover tooltips** explaining each setting
- Improve **keyboard navigation** (Tab key navigation)
- Use **ARIA roles** and labels for screen readers

---

## 📌 Summary of Key Issues

| ID | Issue | Severity | Recommendation |
|----|-------|----------|----------------|
| UX-001 | Save button not visible | High | Improve styling + add feedback |
| UX-002 | No toggle clarity | High | Use visual ON/OFF indicators |
| UX-003 | No real-time feedback | Medium | Add toast or preview |
| UX-004 | Accessibility missing | Medium | Add keyboard and ARIA support |

---

📌 Overall, while the extension **does its job**, it lacks a **polished and accessible UI**, which makes it hard to trust and use comfortably.


```
