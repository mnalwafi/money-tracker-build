# Money Tracker - Build & Test Artifacts

Automated build output and test verification repository for **[Money Tracker (Buckwheat)](https://github.com/mnalwafi/money-tracker)**.

---

### Latest Build Summary

| Parameter | Details |
| :--- | :--- |
| **Source Commit** | [`f37bcb8`](https://github.com/mnalwafi/money-tracker/commit/f37bcb83e8de7e08e659e7860d1356f45c0a5151) |
| **Commit Message** | fix(notification): support BRImo QRIS expense parsing and whitelist Indonesian banking packages |
| **Author** | nashih.definite <nashih@definite.co.id> |
| **Build Timestamp** | 2026-09-28 03:06:18 UTC |
| **Unit Tests Status** | **Passed (All local unit tests + verification passed)** |
| **Build Status** | **Compiled successfully (Debug APK available)** |

---

### Deliverables & Artifacts

- **Android APK**:
  - Direct Download: [app-debug.apk](./apks/app-debug.apk) *(Available when compiled)*
  - Source Code: [mnalwafi/money-tracker](https://github.com/mnalwafi/money-tracker)
- **Automated Verification**:
  - Notification parser unit tests verify amount, currency format, and non-expense filters.
  - Cloud builds and releases run on each push to the main repository.

---

*Updated automatically on every commit.*
