# Scanner App by NextEleven - App Store Connect Links Reference

**Last Updated: December 2025**

This document provides all links needed for App Store Connect configuration and metadata compliance.

## 🔗 Quick Copy-Paste Links

### For App Store Connect Fields

Use these **raw GitHub URLs** for App Store Connect form fields:

#### Privacy Policy URL
```
https://raw.githubusercontent.com/seanebones-lang/NextEleven-App-Documents-/main/ScannerApp_Privacy_Policy.md
```

#### Support URL
```
https://github.com/seanebones-lang/NextEleven-App-Documents-
```

#### Marketing URL (Optional)
```
https://github.com/seanebones-lang/NextEleven-App-Documents-
```

### For App Description

Add these **formatted GitHub web links** to your App Description:

```
Terms of Use: https://github.com/seanebones-lang/NextEleven-App-Documents-/blob/main/ScannerApp_EULA.md

Privacy Policy: https://github.com/seanebones-lang/NextEleven-App-Documents-/blob/main/ScannerApp_Privacy_Policy.md

Subscription Terms: https://github.com/seanebones-lang/NextEleven-App-Documents-/blob/main/ScannerApp_Subscription_Terms.md
```

## 📋 App Store Connect Configuration Guide

### Step 1: App Information Page

Navigate to: **App Store Connect → Your App → App Information**

**Fill in these fields:**

1. **Privacy Policy URL:**
   ```
   https://raw.githubusercontent.com/seanebones-lang/NextEleven-App-Documents-/main/ScannerApp_Privacy_Policy.md
   ```

2. **End User License Agreement (EULA):**
   - **Option A (Recommended):** Select "Use Custom EULA"
     - Copy entire content from `ScannerApp_EULA.md`
     - Paste into EULA text field
   
   - **Option B:** Use Standard Apple EULA
     - Keep default selected
     - Add EULA link to App Description (see Step 2)

3. **Contact Information:**
   - **Email:** info@mothership-ai.com
   - **Phone:** (Optional)

### Step 2: App Store Page

Navigate to: **App Store Connect → Your App → App Store → Version 1.3**

**Update App Description:**

At the end of your existing description, add:

```
---

Legal Information

Terms of Use: https://github.com/seanebones-lang/NextEleven-App-Documents-/blob/main/ScannerApp_EULA.md

Privacy Policy: https://github.com/seanebones-lang/NextEleven-App-Documents-/blob/main/ScannerApp_Privacy_Policy.md

Subscription Terms: https://github.com/seanebones-lang/NextEleven-App-Documents-/blob/main/ScannerApp_Subscription_Terms.md

Support: https://github.com/seanebones-lang/NextEleven-App-Documents-
```

### Step 3: App Privacy Page

Navigate to: **App Store Connect → Your App → App Privacy**

**Data Collection Declaration:**

| Data Type | Collected? | Linked to User? | Used for Tracking? |
|-----------|------------|-----------------|-------------------|
| Purchase History | Yes (via Apple) | No | No |
| User ID | Yes (device only) | No | No |
| Product Interaction | Yes (on-device) | No | No |
| Crash Data | Yes (on-device) | No | No |
| Other Data | No | No | No |

**Data Not Collected:**
- Name, Email, Phone
- Physical Address
- Photos or Videos
- Files and Documents
- Browsing History
- Search History
- Identifiers
- Usage Data
- Diagnostics
- Other Data Types

## 🔍 Link Testing

Before submitting to App Store, verify all links work:

### Test in Private/Incognito Browser

1. **EULA Link:**
   https://github.com/seanebones-lang/NextEleven-App-Documents-/blob/main/ScannerApp_EULA.md
   - Should open without login
   - Should display formatted markdown

2. **Privacy Policy Link:**
   https://github.com/seanebones-lang/NextEleven-App-Documents-/blob/main/ScannerApp_Privacy_Policy.md
   - Should open without login
   - Should display formatted markdown

3. **Terms of Use Link:**
   https://github.com/seanebones-lang/NextEleven-App-Documents-/blob/main/ScannerApp_Terms_of_Use.md
   - Should open without login
   - Should display formatted markdown

4. **Subscription Terms Link:**
   https://github.com/seanebones-lang/NextEleven-App-Documents-/blob/main/ScannerApp_Subscription_Terms.md
   - Should open without login
   - Should display formatted markdown

### Test on Mobile Device

Open each link on iPhone/iPad to ensure:
- Loads quickly
- Renders correctly
- Readable font size
- No authentication required

## 📱 In-App Links

For linking from within your iOS app, use these URLs:

### Settings Screen Links

```swift
// EULA
let eulaURL = URL(string: "https://github.com/seanebones-lang/NextEleven-App-Documents-/blob/main/ScannerApp_EULA.md")!

// Privacy Policy
let privacyURL = URL(string: "https://github.com/seanebones-lang/NextEleven-App-Documents-/blob/main/ScannerApp_Privacy_Policy.md")!

// Terms of Use
let termsURL = URL(string: "https://github.com/seanebones-lang/NextEleven-App-Documents-/blob/main/ScannerApp_Terms_of_Use.md")!

// Subscription Terms
let subscriptionURL = URL(string: "https://github.com/seanebones-lang/NextEleven-App-Documents-/blob/main/ScannerApp_Subscription_Terms.md")!

// Support
let supportURL = URL(string: "https://github.com/seanebones-lang/NextEleven-App-Documents-")!
```

### Open in Safari

```swift
UIApplication.shared.open(eulaURL)
```

### Open in SFSafariViewController

```swift
import SafariServices

let safariVC = SFSafariViewController(url: eulaURL)
present(safariVC, animated: true)
```

## 🛠️ Maintenance

### When to Update Links

Update links in App Store Connect when:
- Document content changes significantly
- File names change (not recommended)
- Repository URL changes (not recommended)
- Moving to custom domain (future)

### Preserving Links

To maintain working links:
- ✅ Keep file names unchanged
- ✅ Keep repository name unchanged
- ✅ Keep branch name as `main`
- ✅ Update content in-place (don't delete and recreate)

### Breaking Changes

These actions will break existing links:
- ❌ Renaming files
- ❌ Renaming repository
- ❌ Making repository private
- ❌ Deleting files
- ❌ Changing branch from `main` to something else

## 📊 Link Analytics

Consider tracking link clicks to understand:
- Which documents users view most
- Mobile vs desktop traffic
- Geographic distribution
- Peak viewing times

GitHub provides basic repository traffic analytics:
- Repository → Insights → Traffic

## ✅ Pre-Submission Checklist

Before submitting to App Store Review:

- [ ] Privacy Policy URL added to App Information
- [ ] EULA configured (custom or standard with link)
- [ ] App Description includes legal links
- [ ] Support URL configured
- [ ] All links tested in private browser
- [ ] All links tested on mobile device
- [ ] Links open without authentication
- [ ] Documents are up-to-date
- [ ] Repository is public
- [ ] No broken links or 404 errors

## 🔐 Security

All documents are:
- Served over HTTPS (secure)
- Publicly accessible (no authentication)
- Version controlled (change history tracked)
- Backed up by GitHub

## 📞 Questions?

If you have questions about links or configuration:

**Email:** info@mothership-ai.com  
**Subject:** "App Store Links - Scanner App"

## 🎯 Related Documents

- [README.md](./README.md) - Repository overview
- [ScannerApp_EULA.md](./ScannerApp_EULA.md) - End User License Agreement
- [ScannerApp_Privacy_Policy.md](./ScannerApp_Privacy_Policy.md) - Privacy Policy
- [ScannerApp_Terms_of_Use.md](./ScannerApp_Terms_of_Use.md) - Terms of Use
- [ScannerApp_Subscription_Terms.md](./ScannerApp_Subscription_Terms.md) - Subscription Terms

---

**Scanner App by NextEleven**  
By NextEleven / Mothership AI  
Contact: info@mothership-ai.com  
Last Updated: December 2025

