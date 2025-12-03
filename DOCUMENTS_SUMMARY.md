# Scanner App by NextEleven - Documents Summary

**Created: December 2025**

## Overview

This document summarizes all legal and policy documents created for **Scanner App by NextEleven** to address App Store Review Guideline 3.1.2 (Business - Payments - Subscriptions) requirements.

## Issue Addressed

**App Store Review Rejection:**
- Guideline 3.1.2 - Business - Payments - Subscriptions
- Missing: Functional link to Terms of Use (EULA) for apps offering auto-renewable subscriptions

## Documents Created

All documents include **"Scanner App by NextEleven"** at the beginning for easy identification.

### 1. EULA.md - End User License Agreement
**Purpose:** Primary document required by App Store for apps with auto-renewable subscriptions

**Key Sections:**
- License grant and restrictions
- Subscription services (auto-renewable terms)
- Free trial terms
- Cancellation and refund policies
- Apple-specific terms
- Limitation of liability

**Use:** Upload to App Store Connect as Custom EULA or link in App Description

### 2. Terms_of_Use.md - Terms of Use
**Purpose:** Comprehensive terms governing app usage and subscriptions

**Key Sections:**
- Service description
- Subscription plans and pricing
- Auto-renewal terms
- User responsibilities
- Dispute resolution

**Use:** Reference document for users and support

### 3. Privacy_Policy.md - Privacy Policy
**Purpose:** Required privacy disclosure for all apps

**Key Sections:**
- Data collection practices
- Data storage and processing
- Third-party services (Grok API, X/Twitter)
- User rights (GDPR, CCPA compliant)
- Security measures

**Use:** Required link in App Store Connect

### 4. Subscription_Terms.md - Subscription Terms
**Purpose:** Detailed subscription information for users

**Key Sections:**
- All subscription plans (Free, Monthly, Yearly)
- Auto-renewal details
- Free trial terms
- Cancellation procedures
- Refund policies
- Family Sharing information

**Use:** Reference document for users and support

### 5. README.md - Repository Documentation
**Purpose:** Guide for using the documents repository

**Contents:**
- Quick links for App Store Connect
- Setup instructions
- Document descriptions

### 6. APP_STORE_LINKS.md - Quick Reference
**Purpose:** Ready-to-use links for App Store Connect configuration

**Contents:**
- GitHub raw links (for App Store Connect)
- GitHub web links (for App Description)
- Step-by-step setup instructions

## Next Steps for App Store Submission

### Step 1: Upload Documents to GitHub
1. Push all documents to: `https://github.com/seanebones-lang/NextEleven-App-Documents-`
2. Ensure all files are in the `main` branch
3. Verify all links are publicly accessible

### Step 2: Configure App Store Connect

**A. Add EULA (Choose one option):**

**Option 1: Custom EULA (Recommended)**
1. App Store Connect → Your App → App Information
2. Scroll to "End User License Agreement (EULA)"
3. Select "Use Custom EULA"
4. Copy content from `EULA.md` and paste

**Option 2: Standard EULA with Link**
1. Keep "Use Standard Apple EULA" selected
2. Add to App Description:
   ```
   Terms of Use: https://github.com/seanebones-lang/NextEleven-App-Documents-/blob/main/EULA.md
   ```

**B. Add Privacy Policy:**
1. App Store Connect → Your App → App Information
2. Privacy Policy URL field:
   ```
   https://raw.githubusercontent.com/seanebones-lang/NextEleven-App-Documents-/main/Privacy_Policy.md
   ```

**C. Update App Description:**
Add these links to your App Description:
```
Terms of Use: https://github.com/seanebones-lang/NextEleven-App-Documents-/blob/main/EULA.md

Privacy Policy: https://github.com/seanebones-lang/NextEleven-App-Documents-/blob/main/Privacy_Policy.md
```

### Step 3: Verify Links
Before submitting:
- [ ] All GitHub links are accessible
- [ ] Links work on mobile devices
- [ ] No authentication required to view documents
- [ ] All documents display correctly

### Step 4: Resubmit for Review
1. Update app metadata with EULA link
2. Ensure Privacy Policy URL is set
3. Submit for App Store review
4. Reference: "EULA link added per Guideline 3.1.2"

## Document Features

### Compliance
- ✅ Apple App Store Review Guidelines
- ✅ Guideline 3.1.2 (Subscriptions)
- ✅ GDPR (European Union)
- ✅ CCPA (California)
- ✅ COPPA (Children's Privacy)

### Subscription Details Covered
- ✅ Auto-renewable subscription terms
- ✅ Free trial disclosure
- ✅ Cancellation procedures
- ✅ Refund policies
- ✅ Price change notifications
- ✅ Family Sharing information

### App-Specific Information
- ✅ App name: Scanner App by NextEleven
- ✅ Developer: NextEleven / Mothership AI
- ✅ Contact: info@mothership-ai.com
- ✅ Subscription pricing: $4.99/month, $29.99/year
- ✅ Product IDs included

## File Structure

```
NextEleven-App-Documents-/
├── EULA.md                    # End User License Agreement
├── Terms_of_Use.md            # Terms of Use
├── Privacy_Policy.md          # Privacy Policy
├── Subscription_Terms.md      # Subscription Terms
├── README.md                  # Repository documentation
├── APP_STORE_LINKS.md         # Quick reference links
└── DOCUMENTS_SUMMARY.md       # This file
```

## Important Notes

1. **App Name:** All documents start with "Scanner App by NextEleven" for identification
2. **Last Updated:** All documents dated December 2025
3. **Links:** Use raw GitHub links for App Store Connect, formatted links for App Description
4. **Updates:** When updating documents, maintain same file names to preserve links
5. **Accessibility:** All documents must be publicly accessible (no authentication)

## Support

For questions about these documents:
- **Email:** info@mothership-ai.com
- **Company:** NextEleven / Mothership AI
- **App:** Scanner App by NextEleven

---

**Scanner App by NextEleven**  
By NextEleven / Mothership AI  
Contact: info@mothership-ai.com  
Created: December 2025
