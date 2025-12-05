# SnapInsight Frequently Asked Questions (FAQ)

**Last Updated:** December 5, 2025  
**Version:** 3.0

**Quick Support:** info@mothership-ai.com

---

## General Questions

### What is SnapInsight?
SnapInsight is an AI-powered media analysis app that uses xAI's Grok 4.1 to analyze your photos and videos. Run multiple specialized AI agents simultaneously, chain them for complex workflows, and get instant insights—all while keeping your data private on your device.

### Who makes SnapInsight?
Next

Eleven / Mothership AI, a solo developer operation based in Dallas, Texas, focused on privacy-first AI applications.

### What makes SnapInsight different?
- **Privacy-First:** Your media never leaves your device (unless you send to xAI for analysis)
- **User-Controlled AI:** You provide your own API key (Pro/Dev) = full control
- **No Tracking:** Zero ads, zero tracking, zero data selling
- **Powerful Features:** Agent chaining, AR mode, video analysis
- **Affordable:** $4.99/month (vs. competitors at $15-30/month)

### What iOS version do I need?
iOS 18.0 or later. SnapInsight uses the latest Apple technologies for performance and security.

### What devices are supported?
- iPhone (iOS 18.0+)
- iPad (iOS 18.0+)
- Best experience: iPhone 14 Pro or newer (for AR mode)

---

## Pricing & Subscriptions

### Is there a free version?
Yes! Free tier includes:
- 3 analyses per day
- Basic agents
- Local storage
- Share to X
- No credit card required

### How much does Pro cost?
**$4.99/month** (auto-renewing subscription via Apple)

Includes unlimited analyses (subject to your xAI quota), all premium features, AR mode, video analysis, and agent chaining.

### How much does Dev cost?
**$9.99/month** (auto-renewing subscription via Apple)

Includes all Pro features plus custom agent scripting, API key sharing, developer analytics, and beta features.

### Is there a free trial?
Yes! 7-day free trials available for Pro and Dev tiers (first-time subscribers only). Cancel before trial ends to avoid charges.

### Can I cancel anytime?
Yes. Cancel via: iPhone Settings → [Your Name] → Subscriptions → SnapInsight. Access continues until end of current billing period.

### Do I get a refund if I cancel?
No prorated refunds for unused time. Contact Apple Support for exceptional circumstances.

### How do I get a refund?
Visit https://reportaproblem.apple.com, sign in, find SnapInsight purchase, and request refund. All refunds managed by Apple.

---

## API Keys

### Why do I need my own API key?
**For Pro/Dev tiers only.** By using your own xAI Grok API key:
- We eliminate variable API costs → keep subscriptions affordable
- You get unlimited usage at xAI's direct pricing
- You control and monitor your AI usage
- Transparent cost structure (no hidden fees)

Free tier uses our shared key (3/day limit).

### How do I get an API key?
1. Visit https://x.ai/api
2. Sign up (free, 2 minutes)
3. Generate API key
4. Copy key
5. SnapInsight Settings → API Configuration → paste key

### How much does the xAI API cost?
**Free Tier (xAI):** $25 credit/month = ~8,000 analyses  
**Most Users:** Pay $0 (within free tier)  
**Heavy Users:** ~$0.003 per image analysis beyond free tier

Monitor usage at x.ai/console.

### Is my API key secure?
Yes. Stored in iOS Keychain (bank-level encryption), never transmitted to SnapInsight servers, sent directly from your device to xAI.

### Can I share my API key?
- **Pro:** No (one device)
- **Dev:** Yes (up to 5 family devices)
- **Security:** Only share with trusted family members

### What if my key is compromised?
1. Go to x.ai/console
2. Revoke compromised key immediately
3. Generate new key
4. Update in SnapInsight Settings

### My key isn't working. Help!
**Check:**
1. Key starts with "xai-" and is 40+ characters
2. No extra spaces when pasted
3. Key is active at x.ai/console
4. xAI account has available credit
5. Internet connection working

Still stuck? Email info@mothership-ai.com with error screenshot.

---

## Features

### What are AI agents?
Specialized AI assistants focused on specific tasks (e.g., Product Agent identifies items, Price Agent finds costs, Recipe Agent extracts ingredients).

### How many agents can I run?
- **Free:** 3 basic agents
- **Pro:** 20+ premium agents, run up to 10 simultaneously
- **Dev:** All agents, unlimited simultaneous

### What is agent chaining?
Multi-step workflows where one agent's output feeds into the next. Example: Product Agent identifies item → Price Agent finds cost → ROI Agent calculates value.

### Does video analysis work?
Yes (Pro/Dev only). Upload videos up to 30 seconds, we extract key frames and analyze.

### What is AR Live Camera mode?
Point your camera at something, get real-time AI analysis overlaid on the screen (Pro/Dev only). Great for shopping, identifying objects, instant translations.

### Can I create custom agents?
Yes (Dev tier only). Write custom prompts, save as reusable agents, share with others.

### Does SnapInsight work offline?
No. Analysis requires internet connection to call xAI API. History viewing works offline.

---

## Privacy & Security

### Do you store my photos?
**No.** Photos and videos stay on your device unless you send them to:
1. xAI (for analysis, when you tap "Analyze")
2. X/Twitter (when you tap "Share on X")

We never store your media on SnapInsight servers.

### What data do you collect?
**Minimal:**
- Subscription status (via Apple)
- App settings (locally on your device)
- Optional: Apple Analytics (if you enable in iOS Settings)

**We do NOT collect:**
- Your name, email, phone, or personal info
- Your photos or videos
- Your location
- Tracking data (no ads, no IDFA)

### Is my data encrypted?
Yes:
- Local data: Encrypted by iOS
- API keys: Stored in Keychain (AES-256)
- Network: HTTPS only (TLS 1.3+)

### Can I delete my data?
Yes:
- Individual analyses: Swipe left in History → Delete
- All history: Settings → Clear History
- API key: Settings → API Configuration → Remove Key
- Everything: Uninstall app

### Is SnapInsight GDPR/CCPA compliant?
Yes. Full compliance with GDPR (EU), CCPA (California), and other privacy laws. See Privacy Policy for details.

### Is it safe for kids?
App is rated 17+. Not directed at children under 13. Parental supervision recommended.

---

## Using SnapInsight

### How do I analyze a photo?
1. Open SnapInsight
2. Tap "Select Photo"
3. Choose photo from library
4. Select agents (tap agent names)
5. Tap "Analyze with Grok Agents"
6. Wait 5-15 seconds
7. View results

### How accurate are the results?
AI results are probabilistic estimates, not facts. Accuracy depends on:
- Image quality (clear, well-lit photos work best)
- Agent specialization
- AI model limitations

**Not suitable for:**
- Medical diagnosis
- Legal decisions
- Financial advice
- Safety-critical decisions

### Can I edit the AI prompts?
- **Free/Pro:** Use predefined agent prompts
- **Dev:** Create custom agents with your own prompts

### How do I save results?
**Automatic:** All analyses saved to History (locally)  
**Manual Export:** Tap Share button → Save to Files / Copy Text / Share to X

### How do I share on X?
1. Complete analysis
2. Tap "Share on X"
3. Authorize SnapInsight (first time)
4. Review post
5. Tap "Post"

### Can I analyze multiple photos at once?
Not currently. One photo/video per analysis. Use agent chaining to run multiple analysis steps.

### What file formats work?
**Photos:** JPG, PNG, HEIC (all iPhone formats)  
**Videos:** MP4, MOV (up to 30 seconds, Pro/Dev only)

---

## Troubleshooting

### App crashes on launch
1. Force quit: Swipe up from bottom, swipe up on SnapInsight
2. Restart: Reopen app
3. Update: App Store → Updates → SnapInsight
4. Reinstall: Delete app, redownload from App Store
5. Contact us if persists: info@mothership-ai.com

### Subscription not recognized
1. Settings → Restore Purchases
2. Check: iPhone Settings → [Your Name] → Subscriptions → SnapInsight (verify active)
3. Sign in with correct Apple ID
4. Restart app
5. Contact us with receipt screenshot if still broken

### "Network error" when analyzing
1. Check internet (Wi-Fi or cellular)
2. Try again (temporary xAI outage possible)
3. Verify API key (Pro/Dev): Settings → API Configuration
4. Check xAI status: https://status.x.ai
5. Contact us if ongoing: info@mothership-ai.com

### Analysis takes forever / spinning wheel
**Possible causes:**
- Large image (compress before upload)
- Slow internet
- xAI API experiencing delays
- Too many simultaneous analyses

**Solutions:**
- Wait 30-60 seconds
- Cancel and retry with smaller image
- Close other apps using network
- Try later if xAI having issues

### API key validation fails
1. Copy key again from x.ai/console (avoid extra spaces)
2. Verify format: starts with "xai-", 40+ characters
3. Check key status at x.ai/console (not revoked)
4. Ensure xAI account has available credit
5. Email us screenshot of error: info@mothership-ai.com

### iCloud sync not working
1. iPhone Settings → [Your Name] → iCloud → SnapInsight (toggle ON)
2. Check iCloud storage (Settings → [Your Name] → iCloud → Manage Storage)
3. Sign in to same Apple ID on all devices
4. Wait 5-10 minutes for sync
5. Restart devices

### X/Twitter sharing fails
1. Settings → X Integration → Disconnect → Reconnect
2. Check X account (not suspended)
3. Verify post content (no policy violations)
4. Try shorter caption (X character limits)
5. Check X API status

---

## Payments & Billing

### How do I upgrade to Pro/Dev?
1. Open SnapInsight
2. Settings → Subscription
3. Choose Pro or Dev
4. Tap "Subscribe"
5. Complete Apple payment
6. Add your xAI API key (Settings → API Configuration)

### When am I charged?
- **First time:** Immediately after trial ends (if trial) or immediately (if no trial)
- **Renewals:** 24 hours before current period expires
- **Billing date:** Same day each month (e.g., subscribe Dec 5 → renews Jan 5, Feb 5)

### Where do I see my receipt?
Email from Apple (sent to Apple ID email) or App Store app → Account → Purchase History

### Can I switch between Pro and Dev?
Yes. iPhone Settings → Subscriptions → SnapInsight → select new tier. Change applies at next renewal.

### What if I'm charged incorrectly?
1. Check receipt (verify charge is for SnapInsight)
2. Visit https://reportaproblem.apple.com
3. Report problem
4. Request refund if erroneous charge

### Do prices ever change?
Possibly. If so, 30 days notice via in-app alert. Existing subscribers grandfathered until next renewal. You can cancel before renewal to avoid new price.

---

## Technical Questions

### Does SnapInsight use my camera roll?
Only when you grant permission. Permissions:
- **Photos:** To select images for analysis
- **Camera:** For AR Live Camera mode (Pro/Dev)

Revoke: iPhone Settings → Privacy & Security → Photos/Camera → SnapInsight (toggle OFF)

### How much storage does SnapInsight use?
- **App:** ~50 MB
- **Data:** Varies by history size (~10 MB per 100 analyses)
- **iCloud:** If sync enabled, data stored in your iCloud quota

Free up space: Settings → Clear History

### Does it use a lot of battery?
**Normal use:** Minimal (<5% per hour)  
**AR mode:** Moderate (10-15% per hour, uses camera continuously)  
**Tip:** Close AR mode when not in use

### Why does it need internet?
- Analyze media (calls xAI API)
- Share on X (posts to X servers)
- Sync via iCloud (optional)

History viewing works offline.

### Will it work on my old iPhone?
**Minimum:** iPhone XS (2018) with iOS 18  
**Recommended:** iPhone 14 Pro or newer for best performance and AR mode

### Does it work on iPad?
Yes! Compatible with iPad running iOS 18+. Optimized UI for larger screen.

### Does it work on Mac?
Not yet. iPhone/iPad only currently. Mac version under consideration.

---

## Advanced Features

### How do I create a custom agent? (Dev only)
1. Settings → Agent Studio → Create Custom Agent
2. Name your agent
3. Write prompt (instructions for AI)
4. Test with sample image
5. Save
6. Use like any other agent

### Can I export agent chains? (Dev)
Yes. Settings → Agent Chains → [Your Chain] → Export. Share as JSON file.

### What is family API key sharing? (Dev)
Dev subscribers can share their xAI API key with up to 5 family members:
1. Dev user shares key manually (text/email)
2. Family members add key in their SnapInsight Settings
3. Usage counts toward Dev user's xAI quota

**Important:** Only share with trusted family. You're responsible for usage.

### What are developer analytics? (Dev)
Stats dashboard showing:
- Total analyses run
- Agent usage frequency
- Performance metrics
- API cost estimates

Access: Settings → Developer Tools → Analytics

---

## Account & Settings

### Do I need to create an account?
No. SnapInsight works without account registration. Everything stored locally.

### Can I use SnapInsight on multiple devices?
Yes:
- Subscription syncs via Apple ID
- Settings/history sync via iCloud (if enabled)
- API key must be added on each device (or shared via Dev tier)

### How do I transfer to a new iPhone?
1. Backup old iPhone (iCloud or iTunes)
2. Restore backup on new iPhone
3. Download SnapInsight from App Store
4. Settings → Restore Purchases
5. Re-add API key (Settings → API Configuration)

### How do I reset the app?
Settings → Clear History (deletes all analyses)  
Settings → API Configuration → Remove Key (removes API key)  
Or: Delete and reinstall app (nuclear option)

### Can I change my Apple ID?
Yes, but:
- Subscription tied to old Apple ID (cancel/resubscribe)
- No way to transfer purchases between Apple IDs

---

## Legal & Compliance

### Who owns my photos?
You do. SnapInsight claims no ownership of your content.

### Who owns the AI results?
You own results generated from your content. xAI's terms apply to AI output. Generally free to use for personal purposes.

### What are your terms?
- **Privacy Policy:** https://github.com/seanebones-lang/NextEleven-App-Documents-/blob/main/SnapInsight_Privacy_Policy.md
- **Terms of Use:** https://github.com/seanebones-lang/NextEleven-App-Documents-/blob/main/SnapInsight_Terms_of_Use.md
- **EULA:** https://github.com/seanebones-lang/NextEleven-App-Documents-/blob/main/SnapInsight_EULA.md

### Can I use SnapInsight commercially?
Contact us: info@mothership-ai.com for commercial licensing. Personal use only by default.

### Is SnapInsight open source?
No. Closed source, proprietary software. © 2025 NextEleven / Mothership AI.

---

## Contact & Support

### How do I contact support?
**Email:** info@mothership-ai.com  
**In-App:** Settings → Help & Support  
**Response Time:** 12-72 hours (depending on tier)

### What info should I include?
- iOS version (Settings → General → About → Software Version)
- Device model (Settings → General → About → Model Name)
- SnapInsight version (Settings → About)
- Subscription tier (Free/Pro/Dev)
- Detailed issue description
- Screenshots (if applicable)

### Do you have live chat?
No. Email support only. Fast response times for Pro/Dev tiers.

### Can I request features?
Yes! Email: info@mothership-ai.com with subject "Feature Request - [Description]". We read every suggestion.

### How do I report a bug?
Email: info@mothership-ai.com with subject "Bug Report - [Issue]". Include steps to reproduce.

### Can I leave feedback?
Absolutely! App Store reviews appreciated, or email info@mothership-ai.com.

---

## Still Have Questions?

**Email:** info@mothership-ai.com  
**Subject:** "SnapInsight Question - [Topic]"

**Documentation:**
- GitHub Docs: https://github.com/seanebones-lang/NextEleven-App-Documents-
- Support Policy: https://github.com/seanebones-lang/NextEleven-App-Documents-/blob/main/SnapInsight_Support_Policy.md
- Onboarding Guide: https://github.com/seanebones-lang/NextEleven-App-Documents-/blob/main/SnapInsight_Onboarding_Troubleshooting.md

---

**SnapInsight by NextEleven / Mothership AI**  
_AI-Powered Media Analysis | Privacy-First | Powered by Grok 4.1_

**Last Updated:** December 5, 2025  
**Version:** 3.0

Questions? Email info@mothership-ai.com

