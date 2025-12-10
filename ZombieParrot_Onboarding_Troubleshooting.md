# Zombie Parrot - Onboarding & Troubleshooting Guide

**Last Updated:** December 9, 2025  
**App Version:** 1.0

---

## Table of Contents

1. [Getting Started](#getting-started)
2. [First-Time Setup](#first-time-setup)
3. [Using Features](#using-features)
4. [Troubleshooting](#troubleshooting)
5. [Common Issues](#common-issues)
6. [Advanced Tips](#advanced-tips)

---

## Getting Started

### Welcome to Zombie Parrot!

Zombie Parrot is an AI-powered coding assistant designed specifically for iOS developers. It helps you generate, debug, and refactor Swift code using the powerful Grok Code Fast 1 AI model.

### What You Can Do

- **Generate Code:** Create Swift code from natural language descriptions
- **Debug Code:** Find and fix bugs in your code
- **Refactor Code:** Improve code structure and maintainability
- **Chat with AI:** Have conversations about coding
- **Voice Input:** Use your voice to interact with the AI

---

## First-Time Setup

### Step 1: Install the App

1. Download Zombie Parrot from the App Store
2. Open the app on your iOS device (iOS 19.0+ required)
3. Grant necessary permissions when prompted

### Step 2: Set Up Your API Key

**Option A: Use Default API Key (If Available)**
1. Open the app
2. Go to **Settings** (top right)
3. If a default key is available, tap **"Use Default Key"**
4. Tap **"Save & Close"**

**Option B: Use Your Own API Key**
1. Get your xAI API key from https://console.x.ai
2. Open Zombie Parrot
3. Go to **Settings**
4. Enter your API key (starts with "xai-")
5. Tap **"Save & Close"**

**Important:** Your API key is stored securely in Apple's Keychain and never shared.

### Step 3: Choose Your Mode

Zombie Parrot has three modes:

1. **Code Tools** - Generate, debug, and refactor code
2. **Chat** - Conversational AI assistance
3. **Voice** - Hands-free voice input

Switch between modes using the segmented control at the bottom.

### Step 4: Start Using the App

You're ready! Try generating your first piece of code:
1. Select **Code Tools** mode
2. Type a description in the code editor (e.g., "Create a function that sorts an array")
3. Tap **"Generate Code"**
4. Review the generated code in the output area

---

## Using Features

### Code Generation

**How to Generate Code:**
1. Select **Code Tools** mode
2. Enter your code description or requirements in the text editor
3. Tap **"Generate Code"**
4. Review the generated Swift code in the output area

**Tips:**
- Be specific about what you want
- Mention iOS version if relevant (e.g., "iOS 19.0+")
- Specify Swift version if needed (e.g., "Swift 6.5")

**Example:**
```
Input: "Create a function that takes an array of integers and returns the sum of all even numbers"

Output: [Generated Swift code with explanation]
```

### Debugging Code

**How to Debug:**
1. Paste your code into the editor
2. Tap **"Debug"**
3. Review the fixes and explanations

**Tips:**
- Include error messages if you have them
- Describe what the code should do
- Mention any specific issues you're experiencing

### Refactoring Code

**How to Refactor (Pro Feature):**
1. Paste your code into the editor
2. Tap **"Refactor"**
3. Review the improved code structure

**What Refactoring Does:**
- Applies SOLID principles
- Improves code organization
- Enhances readability
- Maintains functionality

### Agent Swarm (Pro Feature)

**What is Agent Swarm?**
Agent Swarm uses multiple AI agents working in parallel:
- **Generator Agent:** Creates new code
- **Optimizer Agent:** Improves performance
- **Tester Agent:** Generates unit tests

**How to Use:**
1. Toggle **"Agent Swarm"** ON
2. Enter your code or description
3. Tap **"Generate Code"**
4. Get combined results from all agents

### Chat Mode

**How to Chat:**
1. Select **Chat** mode
2. Type your question or message
3. Tap the send button
4. Continue the conversation

**Tips:**
- Ask coding questions
- Get explanations of concepts
- Discuss best practices
- Get help with specific problems

### Voice Mode

**How to Use Voice Input:**
1. Select **Voice** mode
2. Grant microphone and speech recognition permissions
3. Tap the microphone button
4. Speak your request
5. Review the transcription
6. Send to Grok AI

**Tips:**
- Speak clearly
- Use coding terminology
- Review transcription before sending

---

## Troubleshooting

### App Won't Start

**Symptoms:** App crashes on launch or won't open

**Solutions:**
1. **Restart your device**
2. **Update iOS** - Ensure you're running iOS 19.0 or later
3. **Reinstall the app** - Delete and reinstall from App Store
4. **Check device storage** - Ensure you have enough free space
5. **Contact support** - Email info@mothership-ai.com

### API Key Issues

**Symptoms:** "Invalid API Key" error or API calls failing

**Solutions:**
1. **Verify API Key Format:**
   - Must start with "xai-" or "gsk-"
   - No spaces or extra characters
   - Copy the entire key

2. **Check API Key Validity:**
   - Log into https://console.x.ai
   - Verify your key is active
   - Generate a new key if needed

3. **Update API Key:**
   - Go to Settings
   - Enter your API key
   - Save and try again

4. **Check xAI Service Status:**
   - Visit xAI status page
   - Verify their service is operational

### Network Connection Issues

**Symptoms:** "Network Error" or "Offline" messages

**Solutions:**
1. **Check Internet Connection:**
   - Ensure WiFi or cellular data is enabled
   - Try loading a webpage to test connection

2. **Check Network Settings:**
   - Restart WiFi router
   - Try cellular data if WiFi fails
   - Check VPN settings (may block API calls)

3. **Use Cached Results:**
   - If offline, tap "Use Cached" button
   - View previously cached responses

4. **Firewall Issues:**
   - Ensure api.x.ai is not blocked
   - Check corporate firewall settings

### Code Generation Issues

**Symptoms:** No output, errors, or poor quality code

**Solutions:**
1. **Be More Specific:**
   - Add more details to your request
   - Specify iOS version and Swift version
   - Include example code if relevant

2. **Check Query Limit:**
   - Free tier: 10 queries per day
   - Upgrade to Pro for unlimited queries

3. **Try Different Phrasing:**
   - Rephrase your request
   - Break complex requests into smaller parts

4. **Use Agent Swarm (Pro):**
   - Toggle Agent Swarm ON
   - Get multiple perspectives on your code

### Subscription Issues

**Symptoms:** Pro features locked, subscription not recognized

**Solutions:**
1. **Restore Purchases:**
   - Go to Settings
   - Tap "Restore Purchases"
   - Wait for confirmation

2. **Check Apple ID:**
   - Verify you're signed in with correct Apple ID
   - Check subscription status in iOS Settings

3. **Verify Subscription:**
   - Go to Settings > [Your Name] > Subscriptions
   - Verify Zombie Parrot subscription is active

4. **Contact Support:**
   - Email info@mothership-ai.com
   - Include your Apple ID and subscription details

### Voice Input Issues

**Symptoms:** Voice recognition not working, microphone not responding

**Solutions:**
1. **Grant Permissions:**
   - Go to iOS Settings > Zombie Parrot
   - Enable Microphone and Speech Recognition

2. **Check Microphone:**
   - Test microphone in other apps
   - Clean microphone if blocked

3. **Environment:**
   - Reduce background noise
   - Speak clearly and at normal volume
   - Ensure good internet connection

4. **Restart App:**
   - Close and reopen the app
   - Try again

### Performance Issues

**Symptoms:** Slow responses, app freezing, high battery usage

**Solutions:**
1. **Close Other Apps:**
   - Close background apps
   - Free up device memory

2. **Restart Device:**
   - Restart your iPhone or iPad
   - Clear device memory

3. **Check Device Storage:**
   - Ensure adequate free space
   - Clear cache if needed

4. **Update App:**
   - Check for app updates in App Store
   - Install latest version

---

## Common Issues

### Issue: "Rate Limit Exceeded"

**Cause:** Too many API requests in a short time

**Solution:**
- Wait a few minutes and try again
- Upgrade to Pro for higher rate limits
- Check your xAI API account limits

### Issue: "Timeout Error"

**Cause:** API request took too long

**Solution:**
- Check internet connection
- Try again (request will retry automatically)
- Simplify your request if it's very complex

### Issue: "Invalid Response"

**Cause:** API returned unexpected data

**Solution:**
- Try the request again
- Check xAI service status
- Contact support if issue persists

### Issue: "Cache Not Available"

**Cause:** No cached results for your query

**Solution:**
- Ensure internet connection
- Make a new query to create cache
- Cache is only available for previously made queries

---

## Advanced Tips

### Optimizing Code Generation

1. **Be Specific:**
   - Include iOS version
   - Specify Swift version
   - Mention frameworks needed

2. **Provide Context:**
   - Include related code
   - Explain the problem you're solving
   - Mention any constraints

3. **Iterate:**
   - Start with basic request
   - Refine based on results
   - Ask for improvements

### Using Agent Swarm Effectively

1. **For Complex Tasks:**
   - Use Agent Swarm for large projects
   - Get multiple perspectives
   - Combine best ideas

2. **For Optimization:**
   - Use Agent Swarm when optimizing code
   - Compare different approaches
   - Choose best solution

### Managing API Keys

1. **Security:**
   - Never share your API key
   - Use default key if available
   - Rotate keys periodically

2. **Multiple Keys:**
   - You can switch between keys
   - Store keys securely
   - Use different keys for different purposes

### Offline Usage

1. **Caching:**
   - App caches recent queries
   - Access cached results when offline
   - Cache limit: 50 entries

2. **Cache Management:**
   - Older entries are automatically removed
   - Cache is device-specific
   - Clear cache in Settings if needed

---

## Getting Help

### Support Resources

1. **In-App Help:**
   - Settings > FAQ
   - Settings > Troubleshooting
   - Settings > Onboarding

2. **Email Support:**
   - Email: info@mothership-ai.com
   - Response time: 5 business days (typically 24-48 hours)

3. **Documentation:**
   - Privacy Policy
   - Terms of Service
   - Subscription Details

### Reporting Bugs

When reporting bugs, include:
- Device model and iOS version
- App version
- Steps to reproduce
- Screenshots or screen recordings
- Error messages

---

## Quick Reference

### Keyboard Shortcuts (iPad with Keyboard)

- **Cmd + S:** Save API key
- **Cmd + G:** Generate code
- **Cmd + D:** Debug code
- **Cmd + R:** Refactor code

### Gestures

- **Swipe down:** Refresh
- **Long press:** Context menu
- **Pinch:** Zoom (where applicable)

---

**Need More Help?**

Contact us at **info@mothership-ai.com**  
Visit **Settings > Support** for more resources

---

**Zombie Parrot**  
Version 1.0  
Copyright © 2025 Sean McDonnell and Mothership AI. All rights reserved.
