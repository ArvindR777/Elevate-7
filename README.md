# 🛡️ Browser Extension Security Check – README

## 📌 Task Overview

**Task Name:** Task 7 – Extension Security Audit
**Objective:** Identify and assess browser extensions for potential security risks.

---

## 🔧 Tools Used

* **Browser:** Brave (Chromium-based)

---

## 🔍 Procedure

1. **Opened the browser and navigated to the extensions management page (`brave://extensions/`).**

2. **Identified all currently installed extensions.**

3. **Reviewed each extension based on the following criteria:**

   * Description and purpose
   * Version number and size
   * Permissions requested
   * Site access rights
   * Public reviews or known risks
   * Relevance and usage frequency

---

## 📄 Extension Audit Summary

### 1. ✅ **Return YouTube Dislike**

* **Purpose:** Restores the YouTube dislike count feature.
* **Version:** 3.0.0.18
* **Size:** < 1 MB
* **Permissions:** Read and change data on YouTube domains.
* **Security Review:** Open-source, widely trusted, reasonable permissions.
* **Action:** **Kept**
* **Status:** ✅ Safe

---

### 2. ⚠️ **Ultimate Car Driving Game**

* **Purpose:** In-browser car driving game.
* **Version:** 2
* **Size:** 85.2 MB (unusually large for an extension)
* **Permissions:** None
* **Security Review:** No direct malicious behavior observed, but large size raises concerns.
* **Action:** **Kept (under review)**
* **Status:** ⚠️ Review suggested

---

## ✅ General Recommendations

* Regularly **review installed extensions**.
* Avoid extensions with **vague descriptions** or **high memory usage**.
* Prefer **open-source** or **well-reviewed** extensions.
* **Remove unused** or rarely used extensions.
* Always verify **permissions requested** before installation.

---

## 📝 Summary

No harmful extensions were found.

* **One safe extension** (`Return YouTube Dislike`)
* **One extension under observation** (`Ultimate Car Driving Game`) due to its size.
