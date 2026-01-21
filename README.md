# Cheerleading Stunt Validity Checker

A web-based tool for analyzing cheerleading stunts to verify if flyer's toes remain above base's eye level during competition.

**Purpose:** To help cheerleading coaches and judges verify competition stunt compliance

## ⚠️ CRITICAL SAFETY WARNINGS

### Security Notice
**THIS TOOL ACCESSES YOUR CAMERA AND VIDEO FILES - VERIFY BEFORE USE!**

- ✅ **ONLY use the official version** from this GitHub repository
- ❌ **DO NOT use modified versions** sent by others via text, email, or social media
- 🔍 **Always verify the URL** matches exactly: `https://735783D.github.io/cheer-stunt-checker`
- 📝 **Review the source code** on GitHub before using
- 🚫 **Never download and run** `.html` files from untrusted sources

### Why This Matters
This is client-side HTML/JavaScript that:
- Requests camera permissions
- Can read video files from your device
- Runs entirely in your browser
- **Malicious modifications could:**
  - Record/steal your videos
  - Access your camera without consent
  - Extract personal information
  - Install tracking code

### How to Verify You're Using the Safe Version

1. **Check the URL**
   - Official URL: `https://735783D.github.io/cheer-stunt-checker`
   - Anything else = DO NOT USE

2. **Verify on GitHub**
   - Go to this repository
   - Check commit history for any suspicious changes
   - Last updated: 01/18/2026
   - Version: 1.0

3. **View Source Code**
   - Click on `index.html` in this repository
   - Review the code yourself
   - Check file hash: 39B55C04ED3B74176092E681899B128E8552426E4F0013E7678F66B6C629ECA7
   - Compare with what's running in your browser (View Page Source)

4. **Check File Integrity**
   - File should be exactly one `.html` file
   - No external dependencies except CDN libraries (listed below)

## What This Tool Does

### Features
- 📹 Upload pre-recorded stunt videos (MP4, MOV, etc.)
- 🎯 Manual tracking of base's eyes and flyer's toes
- ▶️ Frame-by-frame playback controls
- 🐌 Slow motion (0.25x - 2x speed)
- 🔍 Zoom and pan controls
- ✅ Real-time validation (Green = valid, Red = toes dropped)
- 📱 Optimized for mobile devices

### How to Use

1. **Upload a Video**
   - Tap "Choose Video" 
   - Select a video of a cheerleading stunt

2. **Set Tracking Points**
   - Tap on the base's eyes (blue marker)
   - Tap on the flyer's toes (red/green marker)

3. **Analyze the Stunt**
   - Use play/pause controls
   - Use frame-by-frame buttons (◀️ ▶️) for precision
   - Adjust playback speed (tap the speed indicator)
   - Zoom in with + button or pinch gesture
   - Pan with arrow buttons when zoomed

4. **Interpret Results**
   - ✅ **GREEN** = Valid stunt (toes above eye level)
   - ❌ **RED** = Invalid (toes dropped below eyes)

5. **Adjust as Needed**
   - Drag markers to follow movement
   - Reset and try again if needed

## Privacy & Data

### What Data is Collected?
**NONE.** This tool:
- ✅ Runs entirely in your browser
- ✅ Videos never leave your device
- ✅ No data sent to any server
- ✅ No analytics or tracking
- ✅ No accounts or login required

### Permissions Required
- **Camera/Video Access**: Only to read video files you explicitly select
- All permissions are handled by your browser's built-in security

## Technical Details

### Technology Stack
- Pure HTML5/CSS3/JavaScript
- No external frameworks except:
  - Standard browser APIs (getUserMedia, Canvas)
  - No tracking libraries
  - No backend servers

### Browser Compatibility
- ✅ Chrome/Safari on iOS (iPhone/iPad)
- ✅ Chrome on Android
- ✅ Desktop browsers (Chrome, Firefox, Safari, Edge)

### Requirements
- Modern browser with HTML5 video support
- Camera/file access permissions
- JavaScript enabled

## Installation & Deployment

### For Developers
1. Clone this repository
2. Open `index.html` in a browser
3. That's it! No build process required.

### For GitHub Pages Deployment
1. Fork this repository
2. Go to Settings → Pages
3. Set Source to "main branch"
4. Access at `https://735783D.github.io/cheer-stunt-checker`

## Contributing

Found a bug or want to suggest an improvement?
1. Open an issue on GitHub
2. Describe the problem or feature request
3. Include screenshots if applicable

## Version History

- **v1.0** (January 2026) - Initial release
  - Video upload and playback
  - Manual tracking points
  - Frame-by-frame controls
  - Zoom and pan
  - Real-time validation

## Credits

**Developed by:** Jason Whitby/737583D with assistance from Claude (Anthropic AI)

**Inspiration:** Cheerleading content creators highlighting the need for precise stunt height verification tools

**Use Case:** Helps determine if a flyer's toes drop below the base's eye level during stunts, which can invalidate the stunt in competition

## License

MIT License - Free to use, modify, and distribute

## Disclaimer

This tool is provided "as is" for educational and coaching purposes. 

- Not affiliated with any cheerleading governing body
- Judgments should be verified by official competition judges
- Use at your own discretion
- The creators assume no liability for competition decisions made using this tool

## Support

For issues or questions:
- Open a GitHub issue in this repository
- Check existing issues for similar problems

---

**Remember:** Only use the official version from this GitHub repository. Stay safe! 🎉
