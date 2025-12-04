# Upload Documents to GitHub - Step by Step Instructions

**Repository:** https://github.com/seanebones-lang/NextEleven-App-Documents-  
**Branch:** main  
**Date:** December 2025

## Prerequisites

- GitHub account (seanebones-lang)
- Repository exists: `NextEleven-App-Documents-`
- Repository is PUBLIC (not private)
- Git installed on your computer (or use GitHub web interface)

## Option 1: Upload via GitHub Web Interface (Easiest)

### Step 1: Navigate to Your Repository

1. Go to: https://github.com/seanebones-lang/NextEleven-App-Documents-
2. Sign in if not already signed in
3. Ensure you're on the `main` branch (check dropdown near top)

### Step 2: Upload Files

1. Click **"Add file"** button (top right)
2. Select **"Upload files"**
3. Drag and drop ALL files from the `github-docs` folder:
   - `ScannerApp_EULA.md`
   - `ScannerApp_Privacy_Policy.md`
   - `ScannerApp_Terms_of_Use.md`
   - `ScannerApp_Subscription_Terms.md`
   - `ScannerApp_FAQ.md`
   - `ScannerApp_Support_Policy.md`
   - `ScannerApp_APP_STORE_LINKS.md`
   - `README.md`

4. **Important:** These files will REPLACE existing files if they have the same name

### Step 3: Commit Changes

1. Scroll down to "Commit changes" section
2. **Commit message:** `Add Scanner App documentation with proper naming`
3. **Description (optional):** `Organized all Scanner App legal and support documents with ScannerApp_ prefix for App Store compliance`
4. Select **"Commit directly to the main branch"**
5. Click **"Commit changes"** button

### Step 4: Verify Upload

1. Navigate back to repository home
2. Verify all 8 files are present
3. Click on each file to ensure content is correct
4. Check that files display properly (formatted markdown)

## Option 2: Upload via Git Command Line (Advanced)

### Step 1: Navigate to the github-docs folder

```bash
cd /Users/nexteleven/Scanner-App-by-NextEleven-/github-docs
```

### Step 2: Initialize Git (if not already done)

```bash
# Clone the repository if you haven't already
cd ~
git clone https://github.com/seanebones-lang/NextEleven-App-Documents-.git
cd NextEleven-App-Documents-
```

### Step 3: Copy Files to Repository

```bash
# Copy all files from github-docs to repository
cp /Users/nexteleven/Scanner-App-by-NextEleven-/github-docs/*.md ~/NextEleven-App-Documents-/
```

### Step 4: Add, Commit, and Push

```bash
# Add all markdown files
git add *.md

# Commit with descriptive message
git commit -m "Add Scanner App documentation with proper naming

- Add ScannerApp_EULA.md (End User License Agreement)
- Add ScannerApp_Privacy_Policy.md (Privacy Policy)
- Add ScannerApp_Terms_of_Use.md (Terms of Use)
- Add ScannerApp_Subscription_Terms.md (Subscription Terms)
- Add ScannerApp_FAQ.md (Frequently Asked Questions)
- Add ScannerApp_Support_Policy.md (Support Policy)
- Add ScannerApp_APP_STORE_LINKS.md (App Store Links Reference)
- Update README.md with Scanner App information

All documents properly organized with ScannerApp_ prefix for App Store compliance and multi-app repository organization."

# Push to GitHub
git push origin main
```

### Step 5: Verify

```bash
# Check repository status
git status

# Verify push was successful
git log --oneline -1
```

Then visit: https://github.com/seanebones-lang/NextEleven-App-Documents- to verify

## Post-Upload Verification

### Test All Links

Open each link in a **private/incognito browser** (to test without authentication):

1. **README:**
   https://github.com/seanebones-lang/NextEleven-App-Documents-/blob/main/README.md

2. **EULA:**
   https://github.com/seanebones-lang/NextEleven-App-Documents-/blob/main/ScannerApp_EULA.md

3. **Privacy Policy:**
   https://github.com/seanebones-lang/NextEleven-App-Documents-/blob/main/ScannerApp_Privacy_Policy.md

4. **Terms of Use:**
   https://github.com/seanebones-lang/NextEleven-App-Documents-/blob/main/ScannerApp_Terms_of_Use.md

5. **Subscription Terms:**
   https://github.com/seanebones-lang/NextEleven-App-Documents-/blob/main/ScannerApp_Subscription_Terms.md

6. **FAQ:**
   https://github.com/seanebones-lang/NextEleven-App-Documents-/blob/main/ScannerApp_FAQ.md

7. **Support Policy:**
   https://github.com/seanebones-lang/NextEleven-App-Documents-/blob/main/ScannerApp_Support_Policy.md

8. **App Store Links:**
   https://github.com/seanebones-lang/NextEleven-App-Documents-/blob/main/ScannerApp_APP_STORE_LINKS.md

### Verify Raw Links (For App Store Connect)

Test these raw GitHub URLs:

1. **Privacy Policy (Raw):**
   https://raw.githubusercontent.com/seanebones-lang/NextEleven-App-Documents-/main/ScannerApp_Privacy_Policy.md

2. **EULA (Raw):**
   https://raw.githubusercontent.com/seanebones-lang/NextEleven-App-Documents-/main/ScannerApp_EULA.md

These should display plain text (no GitHub UI).

### Check on Mobile

1. Open each link on your iPhone/iPad
2. Verify they load without requiring login
3. Verify text is readable
4. Verify formatting is preserved

## Cleanup Old Files (Optional)

If you have old files with different names, you may want to remove them:

### Via GitHub Web:
1. Navigate to old file
2. Click trash icon (top right)
3. Commit deletion

### Via Git Command Line:
```bash
cd ~/NextEleven-App-Documents-

# Remove old files
git rm EULA.md Privacy_Policy.md Terms_of_Use.md
git rm Subscription_Terms.md APP_STORE_LINKS.md
git rm DOCUMENTS_SUMMARY.md FIX_REJECTION_3.1.2.md
git rm QUICK_FIX_CHECKLIST.md

# Commit removal
git commit -m "Remove old documents (replaced with ScannerApp_ prefixed versions)"

# Push changes
git push origin main
```

**Note:** Only remove old files AFTER verifying new files are working in App Store Connect.

## Update App Store Connect

After uploading to GitHub:

1. **Update Privacy Policy URL:**
   - Go to App Store Connect → App Information
   - Update to: `https://raw.githubusercontent.com/seanebones-lang/NextEleven-App-Documents-/main/ScannerApp_Privacy_Policy.md`

2. **Update Custom EULA:**
   - Go to App Store Connect → App Information → EULA
   - Copy content from `ScannerApp_EULA.md`
   - Paste into custom EULA field

3. **Update App Description:**
   - Go to App Store Connect → App Store → Version 1.3
   - Add legal links at end (see `ScannerApp_APP_STORE_LINKS.md` for exact text)

4. **Save all changes**

5. **Reply to App Review** (see main rejection fix document)

## Troubleshooting

### Links Return 404 Error

**Cause:** File not uploaded or wrong file name

**Solution:**
1. Check repository file list
2. Verify file name matches exactly (case-sensitive)
3. Ensure file is in main branch (not a different branch)
4. Verify repository is public

### Links Require Authentication

**Cause:** Repository is private

**Solution:**
1. Go to repository Settings
2. Scroll to "Danger Zone"
3. Click "Change visibility"
4. Select "Public"
5. Confirm change

### Raw Links Don't Work

**Cause:** Wrong URL format

**Solution:**
Use this format:
```
https://raw.githubusercontent.com/USERNAME/REPO/BRANCH/FILE.md
```

Example:
```
https://raw.githubusercontent.com/seanebones-lang/NextEleven-App-Documents-/main/ScannerApp_Privacy_Policy.md
```

### Git Push Fails

**Cause:** Authentication issue

**Solution:**
1. Ensure you're signed in: `git config user.name` and `git config user.email`
2. Use personal access token (not password)
3. Generate token at: https://github.com/settings/tokens
4. Use token as password when prompted

## Files Ready to Upload

Location on your Mac:
```
/Users/nexteleven/Scanner-App-by-NextEleven-/github-docs/
```

Files to upload:
- ✅ ScannerApp_EULA.md
- ✅ ScannerApp_Privacy_Policy.md
- ✅ ScannerApp_Terms_of_Use.md
- ✅ ScannerApp_Subscription_Terms.md
- ✅ ScannerApp_FAQ.md
- ✅ ScannerApp_Support_Policy.md
- ✅ ScannerApp_APP_STORE_LINKS.md
- ✅ README.md

## Next Steps After Upload

1. ✅ Upload all files to GitHub
2. ✅ Verify all links work
3. ✅ Update App Store Connect metadata
4. ✅ Reply to App Store Review
5. ✅ Wait for approval (1-3 days)

## Support

If you encounter issues:

**Email:** info@mothership-ai.com  
**Subject:** "GitHub Upload Issue - Scanner App"

---

**Scanner App by NextEleven**  
By NextEleven / Mothership AI  
Last Updated: December 2025

