# Changelog — HealthShield

## [v1.3.0] — Final Submission Build

### Changed
- **User Profile:** Now shows only Name, Mobile, Email, Address/City (removed DOB & Blood Group)

### Security — Enhanced
- **User Login Wrong Password → Admin Live Alert** ✅
  - CRITICAL popup alert fires on Admin side on wrong user password
  - Logged as [AUTH_FAILURE] in AI Log terminal, Failed Logins counter increments

- **PDF Download Wrong PIN → Admin Live Alert** ✅
  - CRITICAL popup alert fires on Admin side when wrong PIN entered
  - Logged as [PIN_FAILURE] in AI Log terminal, Suspicious counter increments

- All alert popup messages standardized to English

---

## [v1.2.0] — Security Layer
- PIN-protected PDF downloads, excess download detection, AI Log terminal, PHI scanner

## [v1.1.0] — Dual Interface
- User + Admin login with live alert popup system

## [v1.0.0] — Initial Build
- Full user portal + Admin SOC dashboard
