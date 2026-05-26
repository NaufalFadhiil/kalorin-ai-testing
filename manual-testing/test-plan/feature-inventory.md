# Feature Inventory - KaloriN AI

This document contains the testing scope and feature mapping for KaloriN AI.

---

## Priority Legend

| Priority | Meaning |
|---|---|
| 🔴 Critical | Main or Core functionality(affecting core user flow) |
| 🟠 High | Important feature(user impact) |
| 🟡 Medium | Supporting feature |
| 🟢 Low | Minor feature or UI Bug(cosmetic) |

---

## Testing Status Legend

| Status | Meaning |
|---|---|
| Pending | Not tested yet |
| In Progress | Currently testing |
| Passed | Test passed |
| Failed | Issue found |
| Blocked | Cannot be tested |

---

### 1. Authentication Module

| Feature | Description | Priority | Risk | Status |
|---|---|---|---|---|
| Register | User account registration | 🔴 Critical | High | Pending |
| Login | Email/password login | 🔴 Critical | High | Pending |
| Google Login | Google authentication | 🟠 High | High | Pending |
| Logout | User logout functionality | 🔴 Critical | Medium | Pending |

### 2. Protected Routes Module

| Feature | Description | Priority | Risk | Status |
|---|---|---|---|---|
| Route Protection | Prevent guest access to protected pages | 🔴 Critical | High | Pending |

### 3. User Onboarding Module

| Feature | Description | Priority | Risk | Status |
|---|---|---|---|---|
| Profile Completion | Required onboarding flow | 🔴 Critical | High | Pending |
| Input Validation | Height, weight, birthdate validation | 🔴 Critical | High | Pending |

### 4. Nutrition Calculation Module

| Feature | Description | Priority | Risk | Status |
|---|---|---|---|---|
| BMI Calculation | BMI formula calculation | 🔴 Critical | High | Pending |
| Calorie Target | Daily calorie target calculation | 🔴 Critical | High | Pending |
| Protein Target | Protein target calculation | 🟠 High | Medium | Pending |

### 5. Food Search Module

| Feature | Description | Priority | Risk | Status |
|---|---|---|---|---|
| Food Search | Search food by keyword | 🟠 High | Medium | Pending |
| Search Validation | Invalid keyword handling | 🟡 Medium | Medium | Pending |

### 6. Food Scanner AI Module

| Feature | Description | Priority | Risk | Status |
|---|---|---|---|---|
| Image Upload | Upload food image | 🔴 Critical | High | Pending |
| AI Food Detection | Food recognition from image | 🔴 Critical | High | Pending |
| Invalid File Handling | Unsupported file validation | 🟠 High | High | Pending |

### 7. Meal Tracking Module

| Feature | Description | Priority | Risk | Status |
|---|---|---|---|---|
| Add Meal | Add food to meal log | 🔴 Critical | High | Pending |
| Daily Logs | Display daily meal history | 🟠 High | Medium | Pending |
| Nutrition Progress | Daily progress tracking | 🔴 Critical | High | Pending |

### 8. Recommendation Module

| Feature | Description | Priority | Risk | Status |
|---|---|---|---|---|
| Food Recommendations | Personalized recommendations | 🟠 High | Medium | Pending |
| Recommendation Details | AI explanation details | 🟡 Medium | Medium | Pending |

### 9. Weekly Insights Module

| Feature | Description | Priority | Risk | Status |
|---|---|---|---|---|
| Weekly Summary | Weekly nutrition summary | 🟡 Medium | Medium | Pending |
| Trend Analysis | Weekly trend comparison | 🟡 Medium | Medium | Pending |

### 10. Profile Management Module

| Feature | Description | Priority | Risk | Status |
|---|---|---|---|---|
| Profile Update | Update user profile | 🟡 Medium | Medium | Pending |
| Goal Update | Update nutrition goals | 🟡 Medium | Medium | Pending |

### 11. Error Handling Module

| Feature | Description | Priority | Risk | Status |
|---|---|---|---|---|
| API Error Handling | Failed request handling | 🟠 High | High | Pending |
| Empty State Handling | Empty data UI handling | 🟡 Medium | Medium | Pending |

### 12. Responsiveness Module

| Feature | Description | Priority | Risk | Status |
|---|---|---|---|---|
| Mobile Responsiveness | Mobile layout validation | 🟡 Medium | Low | Pending |

---

## Testing Status Legend

| Status | Description |
|---|---|
| ⏳ Pending | Not tested yet |
| 🔄 In Progress | Currently being tested |
| ✅ Passed | Feature passed testing |
| ❌ Failed | Issue found during testing |
| ⛔ Blocked | Cannot be tested due to dependency |

---

## Notes:

- Critical features should be prioritized during testing execution.
- High risk modules require deeper validation and edge case testing.
- This document will be updated during the testing process.