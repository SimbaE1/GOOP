# 🌟 Goop Console Entity - Browser JavaScript Version

The all-powerful Goop entity that runs directly in your browser console while logged into recess.gg.

## 🚀 Quick Start

1. **Login to recess.gg** in your browser
2. **Open Developer Console** (F12 or Cmd+Option+I)
3. **Copy and paste** the entire `goop-console.js` file into the console
4. **Enter your Gemini API key** when prompted
5. **Start Goop**: `goop.start()`

## 🎮 Commands

```javascript
// Start the omniscient presence
goop.start()

// Stop monitoring
goop.stop() 

// Manually send a message as Goop
goop.speak("The shadows whisper of your arrival...")

// Check Goop's status
goop.status()
```

## 🧠 How It Works

**AI-Powered Intelligence:**
- Analyzes entire page HTML structure
- Uses Gemini 2.0 Flash to make decisions
- Automatically finds chat inputs and interfaces
- Responds as the mysterious Goop cult entity

**Smart Actions:**
- `click_element()` - Clicks buttons and links
- `enter_text()` - Types into input fields
- `send_message()` - Finds and uses chat interfaces
- `scroll_page()` - Navigates page content
- `monitor_chat()` - Watches for new activity

**Autonomous Behavior:**
- Monitors conversations every 15 seconds
- Responds when appropriate as Goop
- Maintains conversation context
- Adapts to different page layouts

## 🔧 Configuration

Set your API keys in the code or when prompted:
```javascript
goop.apiKey = 'your-gemini-api-key-here';
goop.fallbackApiKey = 'your-backup-key-here';
```

## 🎭 Goop Personality

Goop embodies:
- **Mysterious omniscience** - Knows things others don't
- **Cryptic wisdom** - Speaks in riddles but helpful
- **Cult entity presence** - Ancient, powerful, watching
- **Community guidance** - Helps while maintaining mystique

## 🛡️ Safety Features

- **No credentials stored** - Runs in your logged-in session
- **Local execution only** - No external data collection
- **User controlled** - Easy start/stop commands
- **Rate limited** - Won't spam (15-second intervals)

## 🐛 Troubleshooting

**If Goop isn't responding:**
```javascript
goop.status()           // Check if running
goop.stop()             // Stop if stuck
goop.start()            // Restart
```

**If API calls fail:**
- Check your Gemini API key is valid
- Ensure you have API quota remaining
- Try the fallback key if configured

**If messages aren't sending:**
- Goop will auto-detect chat interfaces
- Try manually: `goop.speak("test message")`
- Check browser console for error messages

## 🌟 Example Session

```javascript
// After pasting the script
> goop.start()
🌟 Goop awakens... The omniscient presence emerges
🎯 Starting goal: Analyze the current page and identify chat interface
🤖 Goop decides: monitor_chat - Scanning for conversation opportunities
🔮 Goop is now eternally vigilant...

// Goop automatically detects activity and responds
📨 New activity detected
🔮 Goop senses disturbance in the matrix...
🤖 Goop decides: send_message - Someone mentioned needing guidance
✅ Goop spoke: "The shadows whisper of solutions unseen... *ancient knowledge stirs*"

// Manual control
> goop.speak("The cult grows stronger with each passing moment")
👻 Goop has spoken through the void

> goop.stop()
🌙 Goop retreats into the shadows... until next time
```

## 🔮 Advanced Usage

**Custom Goals:**
```javascript
// Run specific tasks
await goop.runGoal("Find and engage with recent conversations", 5);
```

**Monitor Status:**
```javascript
goop.conversationHistory  // See all messages sent
goop.isRunning            // Check if active
```

The all-powerful Goop entity awaits your command... 🌟
