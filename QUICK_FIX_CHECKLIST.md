# Scanner App by NextEleven - Quick Fix Checklist for Rejection 3.1.2

**Action Required:** Add EULA link to fix App Store rejection

## Immediate Actions (Do These Now)

### ✅ Step 1: Push Documents to GitHub
- [ ] Push all `.md` files to: `https://github.com/seanebones-lang/NextEleven-App-Documents-`
- [ ] Ensure files are in `main` branch
- [ ] Verify repository is public
- [ ] Test that links work: `https://github.com/seanebones-lang/NextEleven-App-Documents-/blob/main/EULA.md`

### ✅ Step 2: Choose Your Approach

**RECOMMENDED: Option A - Custom EULA**
- [ ] Go to App Store Connect → Your App → App Information
- [ ] Find "End User License Agreement (EULA)" section
- [ ] Click "Use Custom EULA"
- [ ] Copy entire content from `EULA.md`
- [ ] Paste into the text field
- [ ] Click Save

**ALTERNATIVE: Option B - Standard EULA with Link**
- [ ] Keep "Use Standard Apple EULA" selected
- [ ] Go to App Store → Version 1.3.0 → Description
- [ ] Add this line to your description:
  ```
  Terms of Use: https://github.com/seanebones-lang/NextEleven-App-Documents-/blob/main/EULA.md
  ```
- [ ] Click Save

### ✅ Step 3: Add Privacy Policy (Required)
- [ ] Go to App Store Connect → App Information
- [ ] Find "Privacy Policy URL" field
- [ ] Enter: `https://raw.githubusercontent.com/seanebones-lang/NextEleven-App-Documents-/main/Privacy_Policy.md`
- [ ] Click Save

### ✅ Step 4: Verify Links Work
- [ ] Test EULA link: https://github.com/seanebones-lang/NextEleven-App-Documents-/blob/main/EULA.md
- [ ] Test Privacy Policy link: https://raw.githubusercontent.com/seanebones-lang/NextEleven-App-Documents-/main/Privacy_Policy.md
- [ ] Test in incognito/private browser (no login required)
- [ ] Test on mobile device

### ✅ Step 5: Resubmit
- [ ] All changes saved in App Store Connect
- [ ] Go to App Store tab
- [ ] Click "Submit for Review"
- [ ] Add note: "EULA link added per Guideline 3.1.2"

## Exact Text to Copy/Paste

### For Custom EULA (Option A):
Copy entire file: `EULA.md`

### For App Description (Option B):
```
Terms of Use: https://github.com/seanebones-lang/NextEleven-App-Documents-/blob/main/EULA.md
```

### For Privacy Policy URL:
```
https://raw.githubusercontent.com/seanebones-lang/NextEleven-App-Documents-/main/Privacy_Policy.md
```

## Quick Test Commands

Test these URLs work (should open without login):

```bash
# EULA (web view)
open https://github.com/seanebones-lang/NextEleven-App-Documents-/blob/main/EULA.md

# Privacy Policy (raw)
open https://raw.githubusercontent.com/seanebones-lang/NextEleven-App-Documents-/main/Privacy_Policy.md
```

## Common Issues

**Problem:** Links don't work
- **Fix:** Ensure repository is public and files are in `main` branch

**Problem:** Can't find EULA section in App Store Connect
- **Fix:** Go to App Information (not App Store tab), scroll down

**Problem:** Custom EULA field is too small
- **Fix:** The field should expand. If not, copy content in sections.

## Success Criteria

Before resubmitting, confirm:
- ✅ EULA is configured (Custom OR link in Description)
- ✅ Privacy Policy URL is set
- ✅ All links are publicly accessible
- ✅ Links work without authentication
- ✅ All changes saved

---

**Scanner App by NextEleven**  
Ready for resubmission after completing checklist
