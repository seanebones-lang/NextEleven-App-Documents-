# SnapInsight Onboarding & Troubleshooting Guide

**Version:** 3.0  
**Last Updated:** December 5, 2025

**Quick Support:** info@mothership-ai.com

---

## Welcome to SnapInsight!

This guide will help you get started quickly and solve common issues. Whether you're a new user or troubleshooting a problem, you're in the right place.

---

## Part 1: Quick Start Guide

### Step 1: Choose Your Tier

**Free Tier (No Cost)**
- 3 analyses per day
- Basic agents
- Perfect for trying out SnapInsight

**Pro Tier ($4.99/month)**
- Unlimited analyses*
- All premium features
- Requires your own xAI API key

**Dev Tier ($9.99/month)**
- Pro + developer tools
- Custom agents
- API key sharing with family
- Requires your own xAI API key

*Subject to your xAI quota

**Start Free →** No credit card needed. Upgrade anytime.

### Step 2: Get Your API Key (Pro/Dev Only)

**Why?** By using your own xAI key, we keep subscriptions affordable and you get unlimited usage at xAI's pricing.

**How to Get Key (2 minutes):**

1. **Visit:** https://x.ai/api
2. **Sign Up:** Email + verify
3. **Generate Key:** Click "Create API Key"
4. **Copy Key:** Starts with "xai-", 40+ characters

**xAI Free Tier:** $25/month credit = ~8,000 analyses (most users pay $0)

**Add Key to SnapInsight:**
1. Open SnapInsight
2. Settings → API Configuration
3. Paste key
4. Tap "Validate & Save Key"
5. ✅ Ready!

### Step 3: First Analysis

1. **Select Media**
   - Tap "Select Photo" or "Select Video" (Pro/Dev)
   - Choose from your library
   - Clear, well-lit images work best

2. **Choose Agents**
   - Tap agent names to select (tap again to deselect)
   - Start with 2-3 agents
   - Examples: Product, Price, Emotion

3. **Analyze**
   - Tap "Analyze with Grok Agents"
   - Wait 5-15 seconds
   - Results appear below

4. **Review & Share**
   - Read AI insights
   - Tap "Share on X" to post (optional)
   - Results auto-saved to History

🎉 **You're Done!** You've completed your first analysis.

---

## Part 2: Feature Walkthrough

### 2.1 Understanding Agents

**What Are Agents?**
Specialized AI assistants focused on specific tasks.

**Available Agents:**
- **Product Agent:** Identifies items in photos
- **Price Agent:** Estimates market prices
- **Emotion Agent:** Detects emotions in faces
- **Scene Agent:** Describes location/setting
- **Text Agent:** Extracts and translates text
- **Recipe Agent:** Extracts ingredients/steps from food photos
- **Fashion Agent:** Analyzes clothing styles
- **Code Agent:** Analyzes code screenshots
- **Math Agent:** Solves equations from images
- **Fitness Agent:** Counts reps, analyzes form
- **Creative Agent:** Generates poems/stories
- ... and 10+ more!

**How to Use:**
1. Tap agent names to select
2. Selected agents turn purple
3. Run multiple simultaneously (up to 10)

### 2.2 Agent Chaining (Pro/Dev)

**What Is It?**
Multi-step workflows where one agent's output feeds into the next.

**Example Chain:**
1. Product Agent identifies item
2. Price Agent finds cost using product name
3. ROI Agent calculates value

**How to Set Up:**
1. Settings → Agent Chains
2. Tap "Create New Chain"
3. Name your chain
4. Add steps: Agent + Prompt
5. Use placeholders: `{previous_output}`, `{step_0_output}`
6. Save
7. Use from main screen

**Pro Tip:** Start simple (2-3 steps), then get creative!

### 2.3 AR Live Camera Mode (Pro/Dev)

**What Is It?**
Point your camera, get real-time AI analysis.

**How to Use:**
1. Main screen → AR Mode button
2. Grant camera permission (first time)
3. Point at object/scene
4. Results overlay on screen in real-time

**Use Cases:**
- Shopping: Instant product info
- Travel: Identify landmarks
- Learning: Translate signs
- Cooking: Recipe extraction

**Tip:** Requires good lighting, steady hands.

### 2.4 Video Analysis (Pro/Dev)

**What Is It?**
Analyze videos up to 30 seconds.

**How It Works:**
1. We extract 5-20 key frames
2. Each agent analyzes frames
3. Results aggregated

**How to Use:**
1. Tap "Select Video"
2. Choose video (max 30 sec)
3. Select agents
4. Tap "Analyze"
5. Wait 20-40 seconds (longer than photos)

**Best For:**
- Action sequences
- Tutorial videos
- Product demos
- Time-lapse analysis

### 2.5 History & Sync

**Local Storage:**
- All analyses saved automatically
- View: History tab
- Delete: Swipe left
- Clear all: Settings → Clear History

**iCloud Sync (Optional):**
1. iPhone Settings → [Your Name] → iCloud
2. Toggle "SnapInsight" ON
3. Syncs settings, history, API key
4. Access across all devices

**Export Options:**
- Share button → Save to Files
- Copy text
- Share on X
- Screenshot

---

## Part 3: Troubleshooting

### Problem: App Crashes / Won't Open

**Symptoms:**
- App closes immediately after opening
- Black screen then crash
- Stuck on splash screen

**Solutions:**

**Step 1: Force Quit**
1. Swipe up from bottom (or double-click Home button)
2. Find SnapInsight
3. Swipe up to close
4. Wait 5 seconds
5. Reopen

**Step 2: Update App**
1. App Store → Updates
2. Find SnapInsight
3. Tap "Update"

**Step 3: Restart iPhone**
1. Press and hold Side + Volume buttons
2. Slide to power off
3. Wait 30 seconds
4. Turn back on

**Step 4: Reinstall**
1. Delete SnapInsight (hold icon → Remove App)
2. App Store → Search "SnapInsight"
3. Download
4. Settings → Restore Purchases

**Still Crashing?**
Email: info@mothership-ai.com
Include: iOS version, device model, when it started

---

### Problem: Subscription Not Recognized

**Symptoms:**
- Pro/Dev features locked despite paying
- "Upgrade to Pro" prompts when subscribed
- Free tier limits applying

**Solutions:**

**Step 1: Restore Purchases**
1. SnapInsight → Settings
2. Tap "Restore Purchases"
3. Wait for confirmation
4. Restart app

**Step 2: Verify Subscription**
1. iPhone Settings → [Your Name] → Subscriptions
2. Find SnapInsight
3. Check status (should say "Active")
4. Screenshot for reference

**Step 3: Check Apple ID**
1. Subscribed with correct Apple ID?
2. Sign out/in: Settings → [Your Name] → Sign Out → Sign In
3. Try Restore Purchases again

**Step 4: Wait for Sync**
- Sometimes takes 5-10 minutes after purchase
- Close and reopen app
- Be patient

**Still Not Working?**
Email: info@mothership-ai.com
Include: Screenshot of Apple Subscriptions screen

---

### Problem: API Key Won't Validate

**Symptoms:**
- "Invalid API key" error
- Validation spinner forever
- "401 Unauthorized" message

**Solutions:**

**Step 1: Check Key Format**
- Must start with "xai-"
- Should be 40-50 characters long
- No spaces before/after
- Copy fresh from x.ai/console

**Step 2: Verify at xAI**
1. Visit: x.ai/console
2. Sign in
3. API Keys section
4. Check key status (Active? Revoked?)
5. Regenerate if needed

**Step 3: Check xAI Account**
1. Account has available credit?
2. Not suspended/banned?
3. Created within last 6 months?

**Step 4: Test Internet**
1. Safari → google.com (loads?)
2. Try Wi-Fi vs. cellular
3. Airplane mode OFF

**Step 5: Remove & Re-add**
1. Settings → API Configuration → Remove Key
2. Close app completely
3. Reopen
4. Add key again (fresh copy)

**Still Failing?**
Email: info@mothership-ai.com
Include: Screenshot of error (blur key!)

---

### Problem: Analysis Fails / Never Completes

**Symptoms:**
- Loading spinner forever
- "Network error" message
- Results don't appear
- App freezes during analysis

**Solutions:**

**Step 1: Check Basics**
- ✅ Internet connected (Wi-Fi or cellular)
- ✅ API key added (Pro/Dev users)
- ✅ xAI account has credit
- ✅ Image not corrupted

**Step 2: Simplify Request**
- Use smaller image (compress in Photos app)
- Select fewer agents (start with 1-2)
- Try different photo
- Disable agent chaining

**Step 3: Check xAI Status**
- Visit: https://status.x.ai
- xAI experiencing outage?
- Try again in 15-30 minutes

**Step 4: Clear Cache**
1. Settings → Clear History
2. Force quit app
3. Reopen
4. Try again

**Step 5: Check API Quota**
1. Visit: x.ai/console → Usage
2. Free tier exhausted?
3. API key rate limited?
4. Wait until quota resets (monthly)

**Still Stuck?**
Email: info@mothership-ai.com
Include:
- Screenshot of error
- Photo size (Settings → General → iPhone Storage → Photos → Check image)
- Agents selected

---

### Problem: Share to X Not Working

**Symptoms:**
- "Authorization failed" error
- Post doesn't appear on X
- Can't connect account

**Solutions:**

**Step 1: Reconnect X Account**
1. Settings → X Integration
2. Tap "Disconnect"
3. Tap "Connect X Account"
4. Authorize again
5. Try sharing

**Step 2: Check X Account**
- Not suspended/banned?
- Can post from X app directly?
- Account in good standing?

**Step 3: Review Content**
- Caption too long? (X has character limits)
- Violates X policies? (adjust content)
- Image format supported?

**Step 4: Update Permissions**
1. iPhone Settings → Privacy & Security
2. Tap "X" or "Twitter"
3. Ensure SnapInsight has access

**Step 5: Check X API Status**
- X experiencing issues?
- Try later

**Still Can't Share?**
Email: info@mothership-ai.com

---

### Problem: iCloud Sync Not Working

**Symptoms:**
- History doesn't sync between devices
- Settings not syncing
- API key not appearing on new device

**Solutions:**

**Step 1: Enable iCloud**
- iPhone Settings → [Your Name] → iCloud
- Scroll to SnapInsight
- Toggle ON

**Step 2: Check iCloud Storage**
- Settings → [Your Name] → iCloud
- Enough space available?
- Upgrade if full

**Step 3: Same Apple ID**
- All devices using same Apple ID?
- Settings → [Your Name] (check email)

**Step 4: Wait for Sync**
- Can take 5-10 minutes
- On Wi-Fi (faster than cellular)
- Keep both devices unlocked

**Step 5: Force Sync**
1. Device 1: Make a change (e.g., analyze something)
2. Device 2: Force quit app, reopen
3. Check if change appears

**Sync Limitations:**
- API keys may not sync (security feature)
- Large histories sync slowly
- Requires internet on both devices

---

### Problem: AR Mode Laggy / Not Working

**Symptoms:**
- Low frame rate
- Analysis results delayed
- Camera freezes

**Solutions:**

**Step 1: Close Background Apps**
- Swipe up from bottom
- Close all apps
- Reopen SnapInsight

**Step 2: Check Device Compatibility**
- iPhone 14 Pro+ recommended
- iPhone 12+ minimum
- Older devices may struggle

**Step 3: Improve Conditions**
- Good lighting (AR needs it)
- Steady hands (or tripod)
- Move slower
- Closer to objects

**Step 4: Restart AR Mode**
- Exit AR
- Force quit app
- Reopen
- Try again

**Step 5: Reduce Load**
- Select fewer agents
- Lower screen brightness (saves battery)

**AR Too Slow?**
Use standard photo mode (faster, more accurate anyway).

---

### Problem: Battery Drains Fast

**Symptoms:**
- Battery drops quickly while using app
- iPhone gets hot

**Solutions:**

**Normal Usage (Photo Analysis):**
- Should use <5% per hour
- If more, something else is wrong

**AR Mode:**
- Camera + AI = 10-15% per hour (normal)
- Close AR when not using
- Lower screen brightness

**Reduce Battery Usage:**
1. Settings → Low Power Mode (when battery low)
2. Close SnapInsight when done
3. Don't leave AR mode running
4. Reduce agent count per analysis

**Excessive Battery Drain?**
- Update SnapInsight (bug fixes)
- Update iOS (battery optimizations)
- Check Battery Health: Settings → Battery → Battery Health

---

### Problem: Can't Select Photos/Videos

**Symptoms:**
- "Select Photo" button grayed out
- Permission denied error
- Photos app doesn't open

**Solutions:**

**Step 1: Grant Permissions**
1. iPhone Settings → Privacy & Security → Photos
2. Find SnapInsight
3. Select "All Photos" or "Selected Photos"

**Step 2: Restart App**
- Force quit
- Reopen
- Try selecting again

**Step 3: Check Photo Library**
- Photos app works normally?
- iCloud Photos enabled?
- Syncing complete?

**Step 4: Reset Permissions**
1. Settings → Privacy & Security → Photos
2. SnapInsight → Select "None"
3. Reopen SnapInsight
4. Grant permission when prompted

---

## Part 4: Best Practices

### Getting Best Results

**Photo Tips:**
- ✅ Clear, well-lit images
- ✅ Subject in focus
- ✅ Minimal blur
- ✅ High resolution
- ❌ Avoid overly dark/bright photos
- ❌ Don't use screenshots of screenshots

**Agent Selection:**
- Start with 2-3 relevant agents
- Don't run all 20 at once (overkill)
- Match agents to content (Product Agent for items, Emotion Agent for faces)

**Video Tips:**
- Keep under 30 seconds (legal limit)
- Good lighting throughout
- Steady camera
- Clear action/subject

**AR Mode Tips:**
- Use in well-lit areas
- Steady hands or tripod
- Move slowly
- Close when done (saves battery)

### Privacy Tips

**Protect Your API Key:**
- Don't screenshot key and share publicly
- Don't post key online
- Only share with trusted family (Dev tier)
- Revoke if compromised

**Manage History:**
- Delete sensitive analyses (swipe left)
- Clear history before selling device
- Disable iCloud sync for private content

**Control Data Sharing:**
- Don't analyze content you don't own
- Think before sharing on X
- Free tier = shared API key (less privacy than your own key)

### Cost Management (Pro/Dev)

**Monitor xAI Usage:**
1. Visit: x.ai/console → Usage
2. Check daily/monthly totals
3. Set budget alerts (if xAI offers)

**Reduce Costs:**
- Optimize agent selection (fewer agents per analysis)
- Compress large images before analyzing
- Use agent chaining efficiently (avoid redundant steps)
- Most users stay within free tier ($25/month = ~8,000 analyses)

**Unexpected Charges?**
- Check x.ai/console for usage breakdown
- Revoke API key if suspicious activity
- Contact xAI support: support@x.ai

---

## Part 5: Pro Tips

### For Content Creators

**Analyze Before Posting:**
- Product Agent → get specs
- Price Agent → verify competitive pricing
- Emotion Agent → ensure desired mood
- Text Agent → check for typos in images

**Batch Analysis:**
- Select multiple photos in Photos app
- Analyze one at a time
- Export results
- Create comparison posts

**X Integration:**
- Add analysis as caption
- Boosts engagement (AI insights interesting!)
- Credit SnapInsight for more reach

### For Developers (Dev Tier)

**Custom Agents:**
- Create niche agents for your use case
- Example: "Real Estate Agent" (analyzes property photos)
- Test with diverse images
- Share with community (export/import JSON)

**Agent Chaining:**
- Build complex workflows
- Debug with individual steps first
- Use `{step_N_output}` for precise control
- Export chains as templates

**API Usage Analytics:**
- Track performance over time
- Identify most useful agents
- Optimize prompts for better results
- Share learnings with other devs

### For Power Users

**Keyboard Shortcuts:**
- (Feature coming soon: iOS 18 keyboard shortcuts support)

**Siri Integration:**
- "Hey Siri, open SnapInsight"
- (Future: Analyze photos via Siri)

**Widgets:**
- (Feature coming soon: Home screen quick access)

---

## Part 6: Getting More Help

### Before Contacting Support

**Check These First:**
1. Read this guide thoroughly
2. Check FAQ: https://github.com/seanebones-lang/NextEleven-App-Documents-/blob/main/SnapInsight_FAQ.md
3. Review Support Policy: https://github.com/seanebones-lang/NextEleven-App-Documents-/blob/main/SnapInsight_Support_Policy.md
4. Update app (App Store → Updates)
5. Restart iPhone
6. Try on Wi-Fi (if using cellular)

### When Contacting Support

**Email:** info@mothership-ai.com

**Subject Line:** "SnapInsight Support - [Brief Issue]"

**Include:**
1. **Device:** iPhone 15 Pro, iOS 18.2
2. **App Version:** Settings → About → Version
3. **Subscription:** Free / Pro / Dev
4. **Issue:** Detailed description
5. **Steps to Reproduce:**
   - Step 1: ...
   - Step 2: ...
   - Result: [Problem occurs]
6. **Screenshots:** If applicable (blur API keys!)
7. **What You've Tried:** List troubleshooting steps

**Response Times:**
- Free: 48-72 hours
- Pro: 24-48 hours
- Dev: 12-24 hours

### Escalation

If no response after SLA or issue unresolved:

**Email:** legal@mothership-ai.com  
**Subject:** "ESCALATION - [Original Ticket #]"

---

## Part 7: Feedback & Feature Requests

### We Want to Hear From You!

**Feature Requests:**
Email: info@mothership-ai.com  
Subject: "Feature Request - [Feature Name]"

**Bug Reports:**
Email: info@mothership-ai.com  
Subject: "Bug Report - [Issue]"

**General Feedback:**
- App Store reviews (appreciated!)
- Email: info@mothership-ai.com
- Social media: @SnapInsightApp (coming soon)

**What We Build:**
- Most requested features
- Feasible within scope
- Aligned with privacy-first mission

---

## Part 8: Resources

### Documentation
- **Privacy Policy:** https://github.com/seanebones-lang/NextEleven-App-Documents-/blob/main/SnapInsight_Privacy_Policy.md
- **Terms of Use:** https://github.com/seanebones-lang/NextEleven-App-Documents-/blob/main/SnapInsight_Terms_of_Use.md
- **EULA:** https://github.com/seanebones-lang/NextEleven-App-Documents-/blob/main/SnapInsight_EULA.md
- **Subscription Terms:** https://github.com/seanebones-lang/NextEleven-App-Documents-/blob/main/SnapInsight_Subscription_Terms.md
- **Support Policy:** https://github.com/seanebones-lang/NextEleven-App-Documents-/blob/main/SnapInsight_Support_Policy.md
- **FAQ:** https://github.com/seanebones-lang/NextEleven-App-Documents-/blob/main/SnapInsight_FAQ.md

### Third-Party Resources
- **xAI Console:** https://console.x.ai
- **xAI Docs:** https://docs.x.ai
- **xAI Status:** https://status.x.ai
- **Apple Support:** https://support.apple.com
- **X/Twitter Support:** https://help.x.com

### Community
- Coming soon: SnapInsight Discord server
- Coming soon: Reddit community
- Coming soon: X/Twitter @SnapInsightApp

---

**SnapInsight by NextEleven / Mothership AI**  
_AI-Powered Media Analysis | Privacy-First | Powered by Grok 4.1_

**Last Updated:** December 5, 2025  
**Version:** 3.0

Questions? Email info@mothership-ai.com

