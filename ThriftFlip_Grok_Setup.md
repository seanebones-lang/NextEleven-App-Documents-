# ThriftFlip Grok API Setup Guide

**Version 2.0** | January 2, 2025  
**Complete Guide to Configuring Grok 4.1 in ThriftFlip**

---

## Quick Setup (5 Minutes)

### Step 1: Get Your API Key

1. Visit [x.ai/api](https://x.ai/api)
2. Click "Sign Up" or "Log In"
3. Navigate to API section
4. Click "Create New API Key"
5. Copy the Bearer token (starts with "xai-...")

### Step 2: Add to ThriftFlip

1. Open ThriftFlip
2. Tap **Settings** (gear icon)
3. Tap **"Grok AI Configuration"**
4. Paste your API key
5. Tap **"Test Connection"**
6. See "Connected & active" ✅

### Step 3: Start Scanning!

That's it! You can now use ThriftFlip's AI-powered features.

---

## What is Grok?

Grok 4.1 is xAI's advanced AI model that powers ThriftFlip's smartest features.

### What Grok Does in ThriftFlip

**1. Product Identification**
- Take a photo → Grok identifies the product
- Detects brand, model, type
- Works without barcodes

**2. Condition Assessment**
- Analyzes product condition
- Scores from 0-100
- Notes damage or wear

**3. Market Intelligence**
- Searches 10+ marketplaces
- Finds real current prices
- Amazon, Mercari, Poshmark, Facebook, etc.

**4. Multi-Object Detection**
- Scan multiple items at once
- Separate pricing for each
- Great for bulk sourcing

### Why Use Your Own API Key?

**Benefits:**
- **You Control Costs:** Only pay for what you use
- **Privacy:** Your key, your data
- **No Middleman:** Pay xAI directly
- **Transparent:** See exact usage at x.ai/dashboard
- **Secure:** Stored in iOS Keychain

**vs Traditional Apps:**
- Traditional: $9.99/month subscription → Use it or lose it
- ThriftFlip: Pay per use → $0.02-$0.05/month typical

---

## Getting Your xAI Account

### Sign Up for xAI

**1. Visit xAI Portal**
- Go to [x.ai](https://x.ai)
- Click "Sign In" or "Sign Up"

**2. Create Account**
- Use email or social login
- Verify your email
- Complete profile

**3. Add Payment Method**
- Credit/debit card
- Set billing alerts (recommended)
- No charges until you use API

**4. Generate API Key**
- Dashboard > API Keys
- Click "Create New Key"
- Name it "ThriftFlip"
- Copy the Bearer token

**Important:** Save your key securely! You won't be able to see it again.

---

## Configuring ThriftFlip

### First-Time Setup

**The Grok Introduction shows automatically:**

**Page 1: Welcome to Grok**
- What Grok is
- Grok 4.1 + Heavy model
- Key capabilities

**Page 2: What Grok Does**
- Smart scanning
- Condition assessment
- Price prediction
- Multi-object detection

**Page 3: Cost & Setup**
- Pricing information ($0.02-$0.05/month)
- Security notes
- Usage breakdown

**Choose:**
- "Set Up Grok API" → Go to settings
- "I'll Set It Up Later" → Skip for now

### Manual Setup

**If You Skipped Introduction:**

1. Open ThriftFlip
2. Tap **Settings** (gear icon, top right)
3. Tap **"Grok AI Configuration"** (first section)
4. Enter your API key
5. Tap **"Test Connection"**

### Testing Your Connection

**What Happens:**

1. ThriftFlip validates key format
2. Makes test API call to xAI
3. Checks authentication
4. Saves key to Keychain (if successful)

**Success:**
- ✅ Status: "Connected & active"
- ✅ Green checkmark shown
- ✅ Model: "Grok 4.1 + Heavy"
- ✅ Ready to use!

**Failure:**
- ❌ Shows error message
- ❌ Check key is correct
- ❌ Verify internet connection
- ❌ Try again

---

## Understanding Grok Features

### Vision Analysis

**When You Take a Photo:**

Grok 4.1 analyzes and provides:

**Product Identification:**
- Brand detection
- Product type
- Model numbers
- Color/size
- Confidence score

**Example:**
```
Brand: Nike
Type: Sneakers  
Model: Air Max 90
Color: White/Blue
Size: US 10
Confidence: 95%
```

**Condition Assessment:**
- Overall score (0-100)
- Specific notes
- Wear indicators
- Value impact

**Example:**
```
Condition Score: 85/100
Rating: Good - Used
Notes: Minor creasing on toe, soles show light wear
Impact: -15% vs new condition
```

### Market Intelligence

**Grok's Web Search Capabilities:**

**What Grok Searches:**
1. Amazon listings
2. Mercari active listings
3. Poshmark closets
4. Facebook Marketplace
5. OfferUp
6. Depop
7. Grailed
8. StockX
9. Walmart.com
10. Target.com
11. And more!

**What Grok Extracts:**
- Current selling prices
- Product titles
- Condition descriptions
- Direct URLs to listings
- Availability status

**Example Result:**
```
Found 8 listings across 5 platforms:

Amazon:     $89.99 (New)
Mercari:    $72.50 (Good)
Poshmark:   $78.00 (Like New)
StockX:     $120.00 (Deadstock)
Facebook:   $65.00 (Used - Local)

Average: $89.10
Range: $65-$120
```

### Multi-Object Detection

**Scan Multiple Items:**

1. Take photo with multiple products visible
2. Grok identifies each separately
3. Get individual pricing for each

**Great For:**
- Lot sales at thrift stores
- Bulk clearance items
- Estate sale photography
- Inventory documentation

**Example:**
```
Photo contains:
1. Nike Air Max (left) → $85
2. Adidas Ultraboost (center) → $110
3. New Balance 990 (right) → $95

Total Bundle Value: $290
```

---

## Pricing & Usage

### How Much Does It Cost?

**Grok API Pricing (as of Jan 2025):**
- Input tokens: $0.20 per million
- Output tokens: $0.50 per million

**ThriftFlip Usage:**
- Barcode scan: ~$0.00005 (minimal)
- Photo analysis: ~$0.00036 per scan
- Market search: ~$0.001 per search

**Real-World Costs:**

| Monthly Usage | Est. Cost |
|---------------|-----------|
| 50 scans | $0.02 |
| 100 scans | $0.04 |
| 200 scans | $0.07 |
| 500 scans | $0.18 |
| 1000 scans | $0.36 |

**Compare To:**
- Traditional app subscriptions: $9.99-29.99/month
- Multiple API subscriptions: $50-200/month
- **Grok: Pay only for what you use!**

### Monitoring Your Usage

**xAI Dashboard:**

1. Visit [x.ai/dashboard](https://x.ai/dashboard)
2. View usage statistics
3. See costs in real-time
4. Download usage reports

**Set Billing Alerts:**
1. xAI Dashboard > Billing
2. Set alert threshold (e.g., $5)
3. Get email when reached
4. Prevents surprise charges

### Optimizing Costs

**Use Less, Pay Less:**

**Cost-Saving Tips:**

1. **Use Barcode Scanner First**
   - Barcode scans are cheaper
   - Only use photo AI when needed

2. **Batch Your Searches**
   - Scan multiple items
   - Review results at once
   - Fewer individual searches

3. **Cache Results**
   - ThriftFlip caches for 5 minutes
   - Re-viewing same product is free

4. **Set Score Threshold**
   - Only scan promising items
   - Skip obvious passes
   - Focus on quality finds

**Estimated Savings:**
- Selective scanning: 40% cost reduction
- Using barcode when possible: 30% reduction
- Combined: Up to 70% less than scanning everything

---

## Security & Privacy

### API Key Security

**How ThriftFlip Protects Your Key:**

✅ **iOS Keychain Storage**
- Hardware-encrypted
- Sandboxed per app
- Protected by Face ID/Touch ID
- Never accessible to other apps

✅ **Network Security**
- HTTPS/TLS encryption
- Direct to xAI (not through our servers)
- No key logging or storage on servers
- Secure transmission

✅ **Access Control**
- Only ThriftFlip can access key
- User must authorize use
- Can be removed anytime

### What We DON'T Do

❌ **We Never:**
- Store your key on our servers (we don't have servers)
- Share your key with anyone
- Use your key for our purposes
- Log your API requests
- Sell your data

### Removing Your Key

**Revoke Access Anytime:**

1. Settings > Grok AI Configuration
2. Tap "Remove API Key"
3. Confirm removal
4. Key deleted from Keychain

**Or:**

1. xAI Dashboard
2. Revoke the key
3. Generate new one if needed

---

## Troubleshooting

### Connection Test Fails

**Error: "Invalid API Key"**

**Check:**
- ✅ Key starts with "xai-" or is Bearer token
- ✅ No extra spaces before/after
- ✅ Complete key copied (not truncated)
- ✅ Key not revoked in xAI dashboard

**Fix:**
- Copy key again carefully
- Remove and re-paste
- Generate new key if needed

**Error: "Connection Timeout"**

**Check:**
- ✅ Internet connection works
- ✅ Not on restrictive network (VPN, corporate)
- ✅ xAI service is online ([status.x.ai](https://status.x.ai))

**Fix:**
- Try different network
- Wait and retry
- Check xAI status page

**Error: "Insufficient Credits"**

**Fix:**
- Add credits at [x.ai/dashboard](https://x.ai/dashboard)
- Check billing method is valid
- Review usage limits

### API Key Won't Save

**Problem:** Key doesn't save after test

**Check:**
- ✅ Keychain access enabled
- ✅ iOS passcode set (required for Keychain)
- ✅ Not in restricted mode

**Fix:**
1. iOS Settings > Face ID & Passcode
2. Ensure passcode is set
3. Restart device
4. Try saving key again

### Scans Not Using Grok

**Problem:** Photo scans don't work

**Check:**
1. Settings > Grok AI Configuration
2. Verify "Connected & active"
3. Test connection again

**If Connected but Not Working:**
- Restart app
- Check internet
- Verify xAI credits remain
- Contact support

### Slow Grok Responses

**Normal:** Grok searches take 3-5 seconds (searching 10+ websites)

**Too Slow (10+ seconds):**
- Check internet speed
- Try different network
- Check xAI status
- Retry scan

**Optimization:**
- Use barcode scanner when possible (faster)
- Cache works for 5 minutes (instant re-checks)

---

## Advanced Configuration

### Custom Model Selection (Future)

Currently using: **Grok 4.1 Fast Reasoning**

Future versions may allow:
- Model selection (Fast vs Heavy)
- Temperature adjustment
- Token limits
- Response format

### Rate Limiting

**ThriftFlip Automatically:**
- Throttles requests
- Caches recent results
- Prevents duplicate calls
- Optimizes token usage

**xAI Limits:**
- Check your plan limits
- Set alerts before hitting limits
- Upgrade plan if needed

---

## Cost Examples

### Real User Scenarios

**Casual Flipper (Weekend Warrior):**
```
Activity:
- Thrift stores on Saturdays
- 20 products scanned
- 10 worth flipping
- 4 purchases made

Grok Usage:
- 20 scans × $0.00036 = $0.0072
- Monthly (4 weeks) = $0.03

Annual Cost: $0.36
```

**Active Flipper (Part-Time):**
```
Activity:
- Thrift stores 3x per week
- 100 products scanned/week
- 400 scans/month
- 30-40 purchases/month

Grok Usage:
- 400 scans × $0.00036 = $0.144
- Monthly = $0.14

Annual Cost: $1.68
```

**Professional Flipper (Full-Time):**
```
Activity:
- Daily sourcing
- 1000+ products scanned/month
- 100-150 purchases/month

Grok Usage:
- 1000 scans × $0.00036 = $0.36
- Monthly = $0.36

Annual Cost: $4.32
```

**Still cheaper than a single coffee!** ☕

---

## Best Practices

### Maximizing Value

**Get the Most from Grok:**

1. **Quality Photos**
   - Good lighting = better results
   - Clear focus = accurate ID
   - Include labels = higher confidence

2. **Strategic Scanning**
   - Scan branded items
   - Use for items without barcodes
   - Skip obvious passes

3. **Learn from Results**
   - Note what Grok identifies well
   - Understand confidence scores
   - Verify and improve prompts

4. **Cache Utilization**
   - Same product within 5 min = free
   - Review detailed analysis without re-scanning

### When to Use Grok vs Barcode

**Use Barcode Scanner:**
- Item has visible barcode
- Need fast results
- Standard packaged goods
- Books (ISBN)

**Use Grok Photo AI:**
- No barcode visible
- Clothing, shoes, accessories
- Vintage items
- Need condition assessment
- Multiple items at once

---

## Troubleshooting Guide

### Common Issues & Fixes

**Issue:** "No API Key Configured"  
**Fix:** Settings > Grok AI Configuration > Enter key

**Issue:** "Connection Test Failed"  
**Fix:** Verify key is correct, check internet

**Issue:** "Insufficient Credits"  
**Fix:** Add credits at x.ai/dashboard

**Issue:** "API Rate Limit Exceeded"  
**Fix:** Wait a moment, upgrade xAI plan if needed

**Issue:** "Invalid Response Format"  
**Fix:** Update ThriftFlip to latest version

**Issue:** "Grok Identification Inaccurate"  
**Fix:** Take clearer photo, ensure good lighting

### Getting Help

**ThriftFlip Support:**
- Email: info@mothership-ai.com
- Settings > Contact Support

**xAI Support:**
- Website: [x.ai/support](https://x.ai/support)
- Dashboard: [x.ai/dashboard](https://x.ai/dashboard)
- Documentation: [docs.x.ai](https://docs.x.ai)

**Debug Information:**
- Settings > Grok AI > Copy Debug Log
- Include in support emails

---

## Privacy & Security

### Your Data

**What's Sent to Grok:**
- Product photos (when you scan)
- Barcode numbers (for search)
- Product names (for market search)

**What's NOT Sent:**
- Your personal information
- Your flip records
- Your purchase history
- Your location
- Your device info

### API Key Security

**Best Practices:**

✅ **Do:**
- Keep key secret
- Store in ThriftFlip only
- Set billing alerts
- Monitor usage regularly
- Revoke if compromised

❌ **Don't:**
- Share publicly
- Post in forums/social media
- Email to others
- Store in notes apps
- Use same key across multiple apps

**If Key Is Compromised:**
1. Revoke immediately at x.ai/dashboard
2. Generate new key
3. Update in ThriftFlip
4. Review billing for unauthorized usage

---

## Billing & Payments

### Understanding Your Bill

**xAI Billing:**
- Monthly statement
- Per-token pricing
- Itemized usage
- Download invoices

**ThriftFlip Shows:**
- Estimated costs (in settings)
- Per-scan estimates
- Usage recommendations

**You Pay:**
- xAI directly (via your payment method)
- Not through App Store
- Not through NextEleven

### Setting Up Billing Alerts

**Prevent Surprise Charges:**

1. xAI Dashboard > Settings > Billing
2. Set Alert Threshold: $5.00 (or your preference)
3. Add email for notifications
4. Get notified when approaching limit

**Recommended Thresholds:**
- Casual user: $1.00
- Regular user: $5.00
- Heavy user: $10.00

### Managing Costs

**If Costs Are Too High:**

**1. Review Usage**
- xAI Dashboard > Usage
- See what's consuming tokens
- Identify patterns

**2. Optimize Scanning**
- Use barcode scanner more
- Scan fewer items
- Focus on high-score items
- Batch your scanning sessions

**3. Adjust Settings**
- Set higher score threshold
- Disable auto-scan features
- Manual mode only

**4. Consider Pausing**
- Remove API key temporarily
- Use barcode-only mode
- Re-add when ready

---

## Quick Actions

### In-App Quick Actions

**Settings > Grok AI Configuration:**

**"Open x.ai/api →"**
- Direct link to xAI portal
- Generate new keys
- View documentation

**"How much will this cost me?"**
- Detailed pricing breakdown
- Usage estimates
- Billing information

**"Copy debug log"**
- System diagnostics
- Recent activity
- Error logs
- For support requests

### Useful xAI Links

**Dashboard:** [x.ai/dashboard](https://x.ai/dashboard)
- View usage statistics
- Manage billing
- Download reports

**API Documentation:** [docs.x.ai](https://docs.x.ai)
- Technical documentation
- API reference
- Code examples

**Pricing:** [x.ai/pricing](https://x.ai/pricing)
- Current pricing
- Plan comparisons
- Calculator

**Status:** [status.x.ai](https://status.x.ai)
- Service status
- Outage notifications
- Maintenance schedules

---

## Frequently Asked Questions

**Q: Do I have to pay for Grok?**  
A: Yes, but only for what you use. Typical cost: $0.02-$0.05/month.

**Q: Can I use ThriftFlip without Grok?**  
A: Yes! Barcode scanner works without Grok. Photo AI requires Grok.

**Q: Is there a free tier?**  
A: Check xAI's current offerings at [x.ai/pricing](https://x.ai/pricing).

**Q: What if I can't afford Grok?**  
A: Use barcode scanner only (free). Photo AI requires Grok.

**Q: Can I share my key with friends?**  
A: No. Keys are personal and usage is billed to your account.

**Q: How do I cancel?**  
A: Just remove your API key from ThriftFlip. No cancellation needed.

**Q: Will costs increase?**  
A: xAI controls pricing. Check [x.ai/pricing](https://x.ai/pricing) for current rates.

**Q: Are there hidden fees?**  
A: No! You only pay xAI's per-token pricing. No markups, no subscriptions through us.

---

## Support

**Need Help with Grok Setup?**

**ThriftFlip Issues:**
- info@mothership-ai.com

**xAI Account Issues:**
- [x.ai/support](https://x.ai/support)

**Check Documentation:**
- [ThriftFlip User Guide](https://github.com/seanebones-lang/NextEleven-App-Documents-/blob/main/ThriftFlip_User_Guide.md)
- [ThriftFlip FAQ](https://github.com/seanebones-lang/NextEleven-App-Documents-/blob/main/ThriftFlip_FAQ.md)

---

## Summary

### What You Need to Know

1. ✅ Grok 4.1 powers ThriftFlip's AI features
2. ✅ You need your own API key from xAI
3. ✅ Setup takes 5 minutes
4. ✅ Typical cost: $0.02-$0.05/month
5. ✅ Key stored securely in iOS Keychain
6. ✅ Monitor usage at x.ai/dashboard
7. ✅ Remove key anytime
8. ✅ Barcode scanning works without Grok

### Getting Started Checklist

- [ ] Visit [x.ai/api](https://x.ai/api)
- [ ] Create xAI account
- [ ] Generate API key
- [ ] Open ThriftFlip Settings
- [ ] Paste key in "Grok AI Configuration"
- [ ] Test connection
- [ ] See "Connected & active" ✅
- [ ] Start scanning products!

---

**Questions?** info@mothership-ai.com

**ThriftFlip** by NextEleven Software Solutions  
© 2025 NextEleven. All rights reserved.
