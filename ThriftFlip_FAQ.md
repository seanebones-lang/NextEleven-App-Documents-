# ThriftFlip Frequently Asked Questions (FAQ)

**Version 2.0** | January 2, 2025

---

## Getting Started

### What is ThriftFlip?

ThriftFlip is an AI-powered mobile app that helps resellers find profitable items to flip. It scans products, searches marketplace prices, and calculates profit potential.

### Is ThriftFlip free?

Yes, the app is free to download. However, AI features require a Grok API key (you pay xAI directly, ~$0.02-$0.05/month for typical usage).

### What do I need to get started?

1. iOS device (iPhone or iPad)
2. Grok API key from [x.ai/api](https://x.ai/api)
3. That's it!

### Do I need reselling experience?

No! ThriftFlip is designed for beginners and experienced flippers alike. The app guides you through the entire process.

---

## Grok AI

### What is Grok?

Grok 4.1 is xAI's advanced AI model that powers ThriftFlip's smartest features: photo analysis, product identification, condition assessment, and market intelligence.

### Why do I need my own API key?

- **Cost Control:** You only pay for what you use
- **Privacy:** Your key, your data
- **No Subscriptions:** No monthly app fees
- **Direct Billing:** Pay xAI, not through app stores

### How much does Grok cost?

**Typical Usage:**
- ~$0.00036 per product scan
- 50 scans/month: ~$0.02
- 100 scans/month: ~$0.04
- 200 scans/month: ~$0.07

**Much cheaper than traditional API subscriptions!**

### Where do I get a Grok API key?

1. Visit [x.ai/api](https://x.ai/api)
2. Create xAI account
3. Generate API key
4. Copy Bearer token
5. Paste in ThriftFlip Settings > Grok AI Configuration

### Is my API key secure?

Yes! Your key is stored in iOS Keychain (hardware-encrypted). It never leaves your device except to make API calls directly to xAI.

### Can I share my API key?

No! Your key is personal and usage is billed to your account. Never share it publicly or with others.

### What if I run out of Grok credits?

Add credits at [x.ai/dashboard](https://x.ai/dashboard). Set billing alerts to avoid unexpected charges.

---

## Scanning Products

### What can I scan?

**Barcodes:**
- UPC, EAN, ISBN codes
- 13 different barcode types
- Books, electronics, packaged goods

**Photos (with Grok AI):**
- Any product with visible branding
- Shoes, clothing, collectibles
- Items without barcodes
- Vintage/antique items

### Why won't my barcode scan?

**Common Fixes:**
- Clean the barcode
- Better lighting
- Hold camera steady
- Move 6-12 inches away
- Try different angle
- Use "Take Photo" method instead

### How accurate is AI product identification?

**Grok 4.1 is typically:**
- 95%+ accurate for branded items
- 90%+ accurate for common products
- 70-80% accurate for generic items
- Lower accuracy for vintage/rare items

**Always verify AI results before making purchase decisions!**

### Can I scan multiple items at once?

Yes! Use Grok's multi-object detection:
1. Take photo of multiple items
2. Grok identifies each separately
3. Get pricing for each item

---

## Pricing & Market Data

### Where do prices come from?

**Two Sources:**

**1. eBay API (Fast & Reliable)**
- Real-time listings
- Always available
- No API key needed

**2. Grok Market Intelligence (Comprehensive)**
- Searches 10+ marketplaces
- Real current prices
- Amazon, Mercari, Poshmark, Facebook, StockX, etc.

### How current are the prices?

- **eBay:** Real-time (live API)
- **Grok:** Real-time web search
- **Cached:** 5 minutes max
- Tap "Refresh" for latest

### Why don't I see prices for some items?

**Possible Reasons:**
- Product not sold on tracked platforms
- Too new or too rare
- Generic/unbranded item
- Grok API not configured
- Internet connection issue

**Try:**
- Manual product search
- Different search terms
- Google the UPC directly

### Are prices guaranteed accurate?

**No.** Prices are estimates for research purposes.

**Always:**
- Verify on actual marketplace
- Check recent sold listings
- Factor in condition differences
- Account for fees and shipping

### What marketplaces does ThriftFlip search?

**Currently Tracked:**
- eBay
- Amazon
- Mercari
- Poshmark
- Facebook Marketplace
- OfferUp
- Depop
- Grailed
- StockX
- Walmart
- Target
- *More being added*

---

## Profit Calculations

### How is profit calculated?

```
Profit = (Selling Price) - (Purchase Cost) - (Platform Fees) - (Shipping Cost)
```

**Break-Even Price:**
```
Break-Even = (Purchase Cost) + (Fees) + (Shipping)
```

**ROI:**
```
ROI = (Profit / Purchase Cost) × 100%
```

### Are fees accurate?

ThriftFlip knows current fee structures for major platforms. However:

- Fees may change
- Special promotions may apply
- Some fees are tiered
- Always check platform's fee schedule

### What costs are NOT included?

- Listing fees (some platforms)
- Promoted listings
- Shipping supplies
- Gas/travel costs
- Storage costs
- Your time/labor
- Return/refund costs

### What is a good profit margin?

**General Guidelines:**
- 30%+: Minimum for most flippers
- 50%+: Good margin
- 100%+: Excellent flip
- 200%+: Amazing find!

**Adjust Based On:**
- Item cost (higher % on cheap items)
- Selling speed (lower % for fast sales)
- Competition (lower % if saturated)
- Demand (higher % if high demand)

---

## Flip Score

### What is the Flip Score?

A 0-100 score indicating flip profitability.

**Components:**
- **Demand (30%):** How often it sells
- **Margin (30%):** Profit potential  
- **Competition (20%):** Market saturation
- **Condition (20%):** Item quality

### What score should I aim for?

- **80-100:** Excellent - Buy immediately
- **60-79:** Good - Solid flip
- **40-59:** Moderate - Research more
- **20-39:** Risky - Proceed with caution
- **0-19:** Pass - Not worth it

### Why is my score low?

**Common Reasons:**
- High competition (many listings)
- Low profit margin
- Poor condition
- Slow-selling category
- Oversaturated market

**Not Always Bad:**
- Some items score low but sell fast
- Local markets may differ
- Your expertise might help

---

## Data & Storage

### Where is my data stored?

**All data is LOCAL** (on your device):
- SwiftData database (local)
- iOS Keychain (API key)
- Photo library (if you save photos)

**We do NOT have servers.** Your data never leaves your device unless you export it.

### Can I sync across devices?

Not currently. iCloud sync is planned for a future update.

### How do I back up my data?

**Option 1: Export**
- Library > Export
- Save CSV/PDF to iCloud Drive

**Option 2: iOS Backup**
- Your data backs up with iOS device backup
- Restore when you restore device

### How do I delete all my data?

**Method 1: Reset in App**
- Settings > Reset All Settings
- Confirm deletion

**Method 2: Delete App**
- Delete ThriftFlip from device
- All data automatically removed

---

## Account & Privacy

### Do I need to create an account?

No! ThriftFlip works without any account signup.

### What data does ThriftFlip collect?

- Product scans (local only)
- Your flip records (local only)
- Usage statistics (anonymized)
- Crash reports (anonymized)

**See full details:** [ThriftFlip Privacy Policy](https://github.com/seanebones-lang/NextEleven-App-Documents-/blob/main/ThriftFlip_Privacy_Policy.md)

### Does ThriftFlip sell my data?

**No.** Never. Period.

- Your data stays on your device
- We don't have servers to store it
- No advertising
- No tracking
- No data selling

### Can I use ThriftFlip anonymously?

Yes! No account required, no email needed, no tracking.

---

## Technical Issues

### App crashes frequently

**Try:**
1. Update to latest iOS
2. Update ThriftFlip
3. Restart device
4. Free up storage space
5. Reinstall app (backup first)

**Still Crashing?**
- Settings > Copy Debug Log
- Email to: info@mothership-ai.com
- Include iOS version and device model

### Camera not working

**Check Permissions:**
1. iOS Settings > ThriftFlip
2. Enable Camera permission
3. Restart ThriftFlip

**Still Not Working?**
- Restart device
- Check if camera works in other apps
- Update iOS

### Slow scanning

**Optimize Performance:**
- Close background apps
- Clear marketplace cache
- Good internet connection
- Update to latest version

---

## Business Questions

### Can I actually make money with this?

ThriftFlip is a research tool. Your success depends on:
- Your sourcing ability
- Market knowledge
- Pricing strategy
- Seller skills
- Condition assessment
- Customer service

**ThriftFlip helps you make informed decisions, but doesn't guarantee profits.**

### What's a realistic profit expectation?

**Beginner Flippers:**
- $100-$500/month part-time
- 30-50% average margin
- Focus on learning

**Experienced Flippers:**
- $1,000-$5,000+/month
- 40-70% margins
- Efficient sourcing

**Factors:**
- Time investment
- Capital available
- Market knowledge
- Category expertise

### What items sell fastest?

**High Velocity Items:**
- Name-brand electronics
- Popular sneakers
- Designer clothing
- Gaming items
- Collectibles in demand

**Use ThriftFlip to identify:**
- High listing count = high demand
- Quick price variation = fast sales
- Low flip scores might be fast movers

### Do I need a business license?

**Depends on:**
- Your location (city/state laws)
- Sales volume
- Revenue amount
- Business structure

**Consult:**
- Local business licensing office
- Accountant
- Attorney

**Not Legal Advice:** ThriftFlip doesn't provide legal or tax guidance.

### How do I handle taxes?

**You're Responsible For:**
- Sales tax (if required)
- Income tax on profits
- Self-employment tax (if applicable)
- Quarterly estimated taxes

**Use ThriftFlip's Export:**
- Generate profit reports
- Share with accountant
- Track for tax season

**Consult a tax professional** for your specific situation.

---

## Platform-Specific Questions

### eBay

**Q: Why does eBay always show results?**  
A: eBay has a free API that always works. It's our most reliable data source.

**Q: Are eBay prices real-time?**  
A: Yes! Direct from eBay's Finding API, updated live.

### Amazon

**Q: Why don't I see many Amazon results?**  
A: Amazon requires product API credentials. Grok searches Amazon when possible via web search.

**Q: Can I sell on Amazon using ThriftFlip?**  
A: ThriftFlip helps research. Actual selling happens on Amazon Seller Central.

### Mercari

**Q: How does Mercari pricing work?**  
A: Grok searches current Mercari listings via web search and extracts real prices.

**Q: Are Mercari fees accurate?**  
A: Yes, ThriftFlip knows Mercari's 10% selling fee structure.

### Facebook Marketplace

**Q: Why Facebook listings?**  
A: Facebook is free to sell on (no fees). Grok finds current Facebook Marketplace listings.

**Q: Are Facebook prices lower?**  
A: Often yes. Facebook is more local, prices tend to be lower but also more negotiable.

---

## Updates & Future Features

### How do I update ThriftFlip?

**Automatic:**
- App Store > Updates
- Enable auto-updates

**Manual:**
- App Store > Search "ThriftFlip"
- Tap "Update"

### What's coming in future updates?

**Planned Features:**
- iCloud sync across devices
- Bulk scanning mode
- Barcode history
- Pricing trends over time
- Seller performance tracking
- Community features
- More marketplace integrations

**Requested Features:**
- Profit goal tracking
- Inventory management
- Listing templates
- Auto-listing to marketplaces

**Follow Updates:**
- In-app notifications
- [GitHub documentation](https://github.com/seanebones-lang/NextEleven-App-Documents-)

---

## Troubleshooting Common Issues

### "No API Key Configured"

**Fix:**
1. Settings > Grok AI Configuration
2. Enter your Grok API key
3. Tap "Test Connection"
4. Verify "Connected & active"

### "Connection Test Failed"

**Check:**
- API key is correct (no extra spaces)
- Internet connection works
- xAI account is active
- You have API credits

**Try:**
- Copy/paste key again
- Remove and re-add
- Restart app

### "No Pricing Data Found"

**Reasons:**
- Product not sold online
- Too new/rare
- Generic/unbranded
- Grok API not configured

**Solutions:**
- Configure Grok AI
- Try manual search
- Search by category
- Google the UPC

### Pricing Seems Wrong

**Verify:**
- Check condition matches
- Compare to actual listings
- Look at recent sold items
- Factor in fees and shipping

**Report Issues:**
- Settings > Contact Support
- Include product details

### App is Slow

**Speed Up:**
- Close background apps
- Clear cache (Settings)
- Restart app
- Update iOS
- Reinstall app (backup first)

### Battery Draining Fast

**Reduce Battery Use:**
- Lower screen brightness
- Close app when not using
- Disable background app refresh
- Update to latest version

---

## Best Practices

### Before Buying at Thrift Store

- ✅ Scan product with ThriftFlip
- ✅ Check flip score (60+ recommended)
- ✅ Calculate profit potential
- ✅ Verify condition matches listings
- ✅ Test electronics if possible
- ✅ Check for authenticity
- ✅ Factor in your time
- ✅ Consider storage/shipping

### Photographing Products

**For Best AI Results:**
- Natural lighting (outdoors or near window)
- Clean product first
- Include brand labels
- Multiple angles
- Close-up of tags/labels
- Show any flaws clearly

### Pricing Strategy

**Competitive Pricing:**
1. See ThriftFlip's average price
2. List slightly below average
3. Sells faster
4. Still profitable

**Premium Pricing:**
1. If condition is excellent
2. If item is rare
3. If you can wait longer
4. Price at high end

### Managing Inventory

**Stay Organized:**
- Create flip records immediately after purchase
- Take inventory photos
- Store items properly
- Update status as you list/sell
- Review statistics monthly

---

## Reselling Tips

### Where to Source Items

**Best Places:**
- Goodwill, Salvation Army
- Estate sales
- Garage sales
- Flea markets
- Clearance sections
- Facebook Marketplace (buy low)
- Storage unit auctions

### What to Look For

**Hot Categories:**
- Brand-name electronics
- Designer clothing
- Collectibles (LEGO, Pokémon)
- Vintage items
- Sneakers
- Video games

**Red Flags:**
- Damaged items
- Counterfeit suspicions
- Oversaturated markets
- Low flip scores
- Very low margins

### Authentication

**Avoiding Counterfeits:**
- Research authentication methods
- Check stitching, materials, tags
- Verify serial numbers
- Use Grok's authenticity notes
- When in doubt, don't buy
- Never claim authenticity unless certain

**Resources:**
- YouTube authentication guides
- Brand-specific forums
- Authentication services (for high-value items)

### Shipping Tips

**Save on Shipping:**
- Weigh items accurately
- Use USPS Flat Rate when possible
- Save boxes and packaging
- Buy shipping supplies in bulk
- Offer local pickup on large items

---

## Platform Comparisons

### eBay

**Pros:**
- Largest audience
- Auction or Buy It Now
- Good for collectibles

**Cons:**
- 12.9% fees
- More buyer protections
- Can be slow

**Best For:** Electronics, collectibles, vintage items

### Mercari

**Pros:**
- Simple to use
- 10% fees (lower than eBay)
- Fast shipping labels

**Cons:**
- Smaller audience
- Lower average prices

**Best For:** Everyday items, quick flips, clothing

### Poshmark

**Pros:**
- Great for fashion
- Active community
- Social features

**Cons:**
- 20% fees (expensive)
- Clothing/accessories only

**Best For:** Designer clothing, shoes, handbags

### Facebook Marketplace

**Pros:**
- Free (no fees)
- Local pickup
- Huge audience

**Cons:**
- More scams
- No-shows common
- Cash only (usually)

**Best For:** Furniture, local items, quick sales

### StockX / Grailed

**Pros:**
- Authenticate items
- Premium audience
- Higher prices

**Cons:**
- Category-specific
- Authentication fees
- Longer process

**Best For:** Sneakers (StockX), streetwear (Grailed)

---

## Avoiding Common Mistakes

### Don't Make These Mistakes

❌ **Buying without scanning first**  
→ Always scan before purchasing

❌ **Ignoring condition**  
→ "Used" items sell for much less

❌ **Not factoring in fees**  
→ Use ThriftFlip's calculator

❌ **Overpricing items**  
→ Check market average

❌ **Buying oversaturated items**  
→ High listing count = hard to sell

❌ **Selling counterfeits**  
→ Research authentication, when in doubt pass

❌ **Not testing electronics**  
→ Always test before buying

❌ **Forgetting shipping costs**  
→ Heavy items eat profits

❌ **Ignoring return policies**  
→ Factor in return risk

❌ **Not tracking expenses**  
→ Use flip records for taxes

### Success Principles

✅ **Research First:** Always scan before buying  
✅ **Condition Matters:** Price accordingly  
✅ **Fast Flips:** Don't hold inventory forever  
✅ **Track Everything:** Use flip records  
✅ **Learn Continuously:** See what works for you  
✅ **Diversify:** Don't depend on one category  
✅ **Quality Photos:** Better photos = faster sales  
✅ **Accurate Descriptions:** Honesty builds reputation  
✅ **Responsive:** Answer buyer questions quickly  
✅ **Professional:** Ship fast, package well  

---

## Settings Guide

### General Settings

**Preferred Platform:** Default for fee calculations  
**Default Profit Margin:** Target profit % (30% default)  
**Haptic Feedback:** Vibration on taps

### Flip Score Settings

**Minimum Recommended Score:** Hide items below threshold  
- Set to 60 for good opportunities only
- Set to 40 to see more options
- Set to 80 for only excellent flips

### Search Preferences

**Enable/Disable Vendors:**
- Turn off vendors you don't use
- Reduce search time
- Focus on relevant platforms

### Notifications

**Price Drop Alerts:** Watchlist notifications  
**Flip Reminders:** Check unsold items  
**Weekly Reports:** Performance summaries (coming soon)

---

## Need More Help?

### In-App Resources

- Settings > User Guide (this document)
- Settings > FAQ
- Settings > Support Policy
- Settings > Troubleshooting

### Contact Support

**Email:** info@mothership-ai.com  
**Subject:** ThriftFlip Support  
**Response:** Within 48 hours

**Include:**
- iOS version
- ThriftFlip version
- Description of issue
- Screenshots if helpful
- Debug log (Settings > Grok AI > Copy Debug Log)

### Community

**Share Your Success:**
- Tag #ThriftFlip on social media
- Share your best flips
- Help other flippers

---

## Quick Reference

### Scanning Cheat Sheet

| Situation | Method | Speed |
|-----------|--------|-------|
| Clear barcode | Barcode Scanner | 2 sec |
| Photo needed | Take Photo | 4-6 sec |
| No barcode | Take Photo | 4-6 sec |
| Multiple items | Take Photo | 6-10 sec |
| Research only | Manual Search | 3-5 sec |

### Score Quick Reference

| Score | Action |
|-------|--------|
| 80-100 | Buy it! |
| 60-79 | Solid flip |
| 40-59 | Research more |
| 20-39 | Probably pass |
| 0-19 | Definitely pass |

### Profit Margin Guide

| Margin | Rating |
|--------|--------|
| 100%+ | Excellent |
| 50-99% | Good |
| 30-49% | Acceptable |
| 10-29% | Marginal |
| <10% | Not worth it |

---

## Glossary of Terms

**BOLO:** Be On the Lookout (profitable items to find)  
**FBA:** Fulfilled by Amazon  
**FVF:** Final Value Fee (eBay seller fee)  
**GUC:** Good Used Condition  
**ISO:** In Search Of  
**NIB:** New In Box  
**NWT:** New With Tags  
**OBO:** Or Best Offer  
**ROI:** Return on Investment  
**UPC:** Universal Product Code (barcode)  

---

## Additional Resources

### Learning Reselling

**YouTube Channels:**
- Search "reselling for beginners"
- Product authentication guides
- Platform-specific tutorials

**Communities:**
- r/Flipping (Reddit)
- r/ThriftStoreHauls
- Facebook reseller groups

**Books:**
- "The 10 Commandments of Flipping" (various authors)
- Platform seller handbooks

### ThriftFlip Resources

**Documentation:**
- [NextEleven App Documents](https://github.com/seanebones-lang/NextEleven-App-Documents-)

**Support:**
- info@mothership-ai.com

**Updates:**
- Check App Store for new versions
- In-app notifications for features

---

**Happy Flipping!** 🎯

Find profitable items, make smart decisions, and grow your resale business with ThriftFlip.

**Questions?** info@mothership-ai.com

**ThriftFlip** by NextEleven Software Solutions  
© 2025 NextEleven. All rights reserved.
