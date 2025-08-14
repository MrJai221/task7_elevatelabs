# Browser Extension Audit

**Objective:** To identify and remove suspicious, malicious, or unnecessary browser extensions to enhance security and privacy.

**Date of Audit:** August 15, 2025

## Summary

This audit involves a manual review of all installed extensions in the web browser(s) to ensure each one is legitimate, necessary, and has appropriate permissions. Malicious browser extensions are a significant security threat, capable of stealing passwords, tracking user activity, injecting advertisements, and redirecting web traffic. This proactive audit helps to minimize that risk.

## How to Spot a Suspicious Browser Extension

During the audit, each extension was evaluated against the following criteria. An extension is considered suspicious if it meets one or more of these red flags:

### 🚩 Key Red Flags

1.  **Excessive Permissions:** Does the extension ask for more access than it needs? A simple note-taking app should not need to "read and change all your data on all websites." This is a major warning sign.
2.  **Unrecognized Installation:** Do you remember installing it? If you don't recognize an extension, it should be removed immediately.
3.  **Changes Browser Behavior:** Does the extension change your search engine, inject ads, or redirect you without permission? This is a clear sign of malware or adware.
4.  **No Longer in Official Store:** If the extension has been removed from the official Chrome Web Store or Firefox Add-ons site, it has likely been flagged as malicious.

### 🤔 Other Warning Signs

*   **Generic Names:** Be wary of extensions with generic names like "Video Downloader" or "AdBlock" that are not from a well-known, reputable developer.
*   **Poor Reviews:** Look for reviews that mention data theft, excessive ads, or other unexpected behavior.
*   **No Developer Information:** Legitimate extensions are typically linked to a developer with a public profile or website.

## Audit and Removal Process

### 1. Locate Your Extensions

*   **Google Chrome:** Navigate to `chrome://extensions`
*   **Mozilla Firefox:** Navigate to `about:addons`

### 2. Review Each Extension

Go through the list of installed extensions one by one. For each extension, ask:
*   "Do I know what this is and do I still use it?"
*   "Are its permissions reasonable for its function?" (Click "Details" or "Permissions" to check)
*   "Is the developer reputable?"

### 3. Remove or Report

*   **For Unnecessary Extensions:** If you no longer use it, **Remove** it. Every extension is a potential security risk.
*   **For Suspicious Extensions:** If an extension raises any red flags, **Remove** it immediately. Use the **"Report abuse"** option if you believe it is malicious.

## Deliverable: Audit Results

*   **[ ] Audit Completed:** All browsers (Chrome, Firefox, Edge, etc.) have been checked.
*   **[ ] Suspicious Extensions Found:** (Yes/No)
*   **[ ] Action Taken:** (List of extensions removed and the reason for removal)

---
### Example Log:

*   **Extension Removed:** `Super Ad Blocker`
    *   **Reason:** Did not recognize this extension. It requested permission to "read and change all data on websites." This is highly suspicious.
    *   **Action:** Removed and Reported.

*   **Extension Removed:** `Flash Player Plus`
    *   **Reason:** Adobe Flash Player is obsolete and no longer supported. Any extension claiming to be Flash is unnecessary and a security risk.
    *   **Action:** Removed.

*   **Extension Kept:** `Bitwarden - Free Password Manager`
    *   **Justification:** Essential and trusted password manager. Its permissions are appropriate for its function of filling in passwords.
---
