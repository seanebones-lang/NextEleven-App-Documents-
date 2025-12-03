# Scanner App by NextEleven - Fix App Store Rejection 3.1.2

**Rejection Date:** December 03, 2025  
**Submission ID:** 78764d95-d6ee-4f83-9ef9-24649e8a0584  
**Version:** 1.3.0  
**Issue:** Guideline 3.1.2 - Missing Terms of Use (EULA) link

## Problem

App Store Review requires:
- **A functional link to the Terms of Use (EULA)** for apps with auto-renewable subscriptions
- Either in App Description (if using standard Apple EULA) OR in App Store Connect (if using custom EULA)

## Solution

You have two options. **Option 1 (Custom EULA) is recommended** as it gives you more control.

---

## Option 1: Use Custom EULA (RECOMMENDED)

### Step 1: Upload Documents to GitHub

1. Push all documents to: `https://github.com/seanebones-lang/NextEleven-App-Documents-`
2. Ensure files are in the `main` branch
3. Verify files are publicly accessible

### Step 2: Add Custom EULA in App Store Connect

1. Log in to [App Store Connect](https://appstoreconnect.apple.com)
2. Navigate to: **My Apps** → **Scanner App by NextEleven**
3. Click on your app
4. Go to **App Information** (left sidebar)
5. Scroll down to **"End User License Agreement (EULA)"** section
6. Click **"Use Custom EULA"** radio button
7. Copy the **entire content** from `EULA.md` file
8. Paste into the text field
9. Click **"Save"** (top right)

### Step 3: Add Privacy Policy Link

1. Still in **App Information** page
2. Find **"Privacy Policy URL"** field
3. Enter:
   ```
   https://raw.githubusercontent.com/seanebones-lang/NextEleven-App-Documents-/main/Privacy_Policy.md
   ```
4. Click **"Save"**

### Step 4: Update App Description (Optional but Recommended)

1. Go to **App Store** tab (left sidebar)
2. Select your version (1.3.0)
3. Scroll to **"Description"** field
4. Add at the end of your description:
   ```
   
   Terms of Use: https://github.com/seanebones-lang/NextEleven-App-Documents-/blob/main/EULA.md
   Privacy Policy: https://github.com/seanebones-lang/NextEleven-App-Documents-/blob/main/Privacy_Policy.md
   ```
5. Click **"Save"**

---

## Option 2: Use Standard Apple EULA with Link

### Step 1: Upload Documents to GitHub

Same as Option 1, Step 1.

### Step 2: Keep Standard EULA Selected

1. In App Store Connect → **App Information**
2. Ensure **"Use Standard Apple EULA"** is selected (default)
3. Do NOT change this

### Step 3: Add EULA Link to App Description

1. Go to **App Store** tab
2. Select version **1.3.0**
3. Scroll to **"Description"** field
4. Add at the **beginning or end** of your description:
   ```
   Terms of Use: https://github.com/seanebones-lang/NextEleven-App-Documents-/blob/main/EULA.md
   ```
5. Make sure the link is clearly visible and functional
6. Click **"Save"**

### Step 4: Add Privacy Policy Link

Same as Option 1, Step 3.

---

## Verification Checklist

Before resubmitting, verify:

- [ ] EULA is added (Custom EULA in App Store Connect OR link in App Description)
- [ ] Privacy Policy URL is set in App Information
- [ ] All GitHub links are publicly accessible (test them in a browser)
- [ ] Links work on mobile devices
- [ ] No authentication required to view documents
- [ ] App Description includes EULA link (if using Option 2)
- [ ] All changes are saved in App Store Connect

## Testing Links

Test these links in your browser (should open without login):

**EULA:**
```
https://github.com/seanebones-lang/NextEleven-App-Documents-/blob/main/EULA.md
```

**Privacy Policy:**
```
https://github.com/seanebones-lang/NextEleven-App-Documents-/blob/main/Privacy_Policy.md
```

**Raw EULA (for App Store Connect):**
```
https://raw.githubusercontent.com/seanebones-lang/NextEleven-App-Documents-/main/EULA.md
```

**Raw Privacy Policy (for App Store Connect):**
```
https://raw.githubusercontent.com/seanebones-lang/NextEleven-App-Documents-/main/Privacy_Policy.md
```

## Resubmission Steps

1. Complete one of the options above
2. Verify all links work
3. Go to **App Store Connect** → **TestFlight** or **App Store** tab
4. Click **"Submit for Review"**
5. In the review notes, you can add:
   ```
   EULA link has been added per Guideline 3.1.2 requirements.
   Custom EULA is now configured in App Store Connect.
   Privacy Policy URL has been added.
   ```

## What to Reply to App Review

If you need to reply to the rejection, use this template:

```
Thank you for the review feedback.

We have addressed the Guideline 3.1.2 requirement:

1. Custom EULA has been added in App Store Connect (App Information section)
2. Privacy Policy URL has been configured
3. Terms of Use link is available in App Description

All documents are publicly accessible at:
https://github.com/seanebones-lang/NextEleven-App-Documents-

The app is ready for resubmission.
```

## Quick Reference: Exact Text to Add

### For App Description (Option 2):
```
Terms of Use: https://github.com/seanebones-lang/NextEleven-App-Documents-/blob/main/EULA.md
```

### For Privacy Policy URL (Both Options):
```
https://raw.githubusercontent.com/seanebones-lang/NextEleven-App-Documents-/main/Privacy_Policy.md
```

### For Custom EULA Content (Option 1):
Copy entire content from `EULA.md` file

---

## Important Notes

1. **GitHub Repository:** Make sure all files are pushed to the `main` branch
2. **Public Access:** Repository must be public or documents must be in a public location
3. **Link Format:** 
   - Use `github.com/.../blob/...` for App Description (user-friendly)
   - Use `raw.githubusercontent.com/...` for App Store Connect fields (direct file access)
4. **File Names:** Keep file names exactly as created (`EULA.md`, `Privacy_Policy.md`) to preserve links

## Support

If you encounter issues:
- Verify GitHub repository is public
- Test all links in incognito/private browser window
- Ensure files are in `main` branch (not `master` or other branch)
- Check file names match exactly (case-sensitive)

---

**Scanner App by NextEleven**  
By NextEleven / Mothership AI  
Last Updated: December 2025
