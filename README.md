# YouTube

All YouTube videos created by Fellows should have a corresponding Markdown page with code, prompts, links to software, links to other full code repositories or whatever makes sense for the video.

You are expected to monitor and respond to comments on your videos.

You are encouraged to add links to your personal Linkedin pages for those seeking a job.


## YouTube Content Creation Guide for Humanitarians AI Fellows

This guide outlines the complete process for creating, enhancing, and publishing YouTube content as a Humanitarians AI Fellow.

## Table of Contents
1. [Creating Your YouTube Content](#creating-your-youtube-content)
2. [Audio Enhancement Guide](#audio-enhancement-guide)
3. [Publishing Your Video](#publishing-your-video)
4. [Updating Your GitHub Documentation](#updating-your-github-documentation)
5. [Community Engagement](#community-engagement)

## Creating Your YouTube Content

### YouTube Title and Description Format

When creating content for the "Nerd Stuff and AI" series, follow these guidelines for your YouTube titles and descriptions:

#### Title Format
Create a descriptive, engaging title that clearly indicates the content is part of the Humanitarians AI Fellows program, for example:
- "How to Build a Simple AI Chatbot | Nerd Stuff and AI Ep.2"
- "Understanding Machine Learning Models | Nerd Stuff and AI with Humanitarians AI"

#### Description Template
Your description should include:
1. A brief summary of the video content (2-3 sentences)
2. What viewers will learn (bullet points work well)
3. Required links (always include these exactly as shown):

```
🔗 CONNECT WITH HUMANITARIANS AI:
Apple Music: https://music.apple.com/us/artist/humanitarians-ai/1781414009
Spotify: https://open.spotify.com/artist/3cj3R4pDpYQHaWx0MM2vFV
Website: https://www.humanitarians.ai/
YouTube: https://www.youtube.com/@humanitariansai
GitHub: https://github.com/Humanitariansai/
LinkedIn: https://www.linkedin.com/company/105696953/

📝 RESOURCES MENTIONED:
Find all code, prompts, and details from this video in our GitHub repository:
[Link to your specific GitHub markdown page]

[Your Name]
[Your LinkedIn URL]
```

### Hashtags
Include 3-5 relevant hashtags at the end of your description. Always include #HumanitariansAI and #NerdStuffAndAI.

## Audio Enhancement Guide

### Step 1: Extract Audio from Video
First, extract the audio track from your video file using FFmpeg:

```bash
ffmpeg -i video.mp4 -vn -acodec pcm_s16le -ar 44100 audio.wav
```

This command:
- `-i video.mp4`: Specifies the input video file
- `-vn`: Disables video recording
- `-acodec pcm_s16le`: Sets the audio codec to 16-bit PCM
- `-ar 44100`: Sets the audio sampling rate to 44.1kHz
- `audio.wav`: Names the output audio file

### Step 2: Enhance Audio in Audacity
1. **Open Audacity** and import your extracted audio.wav file (File > Open)
2. **Apply Amplification**:
   - Select the entire track (Ctrl+A or ⌘+A)
   - Navigate to Effect > Volume > Amplify
   - In the dialog box:
     - The default setting will boost the volume to the maximum level without clipping
     - Adjust "New Peak Amplitude (dB)" to control the maximum volume
     - If your audio is extremely quiet, check "Allow clipping" (use cautiously)
   - Click "OK" to apply
3. **Additional Recommended Enhancements**:
   - **Noise Reduction**: Effect > Noise Reduction > Get Noise Profile (from a silent section), then apply to the full track
   - **Equalization**: Effect > Equalization to enhance voice frequencies (boost around 2-4kHz for clarity)
   - **Compression**: Effect > Compressor to even out volume levels
   - **Normalize**: Effect > Normalize to -3dB for consistent levels
4. **Export Enhanced Audio**: File > Export > Export as WAV (or your preferred format)

### Step 3: Reintegrate with Video
1. Open your video editing software (Premiere Pro, Final Cut, DaVinci Resolve, etc.)
2. Create a new project and import both:
   - Your original video file
   - Your enhanced audio.wav file
3. Place the video on your timeline, then:
   - Mute or delete the original audio track
   - Add your enhanced audio.wav file to the timeline
   - Ensure the enhanced audio is properly synchronized with the video
4. Make any final adjustments to ensure audio-visual synchronization
5. Export your video with the enhanced audio

## Publishing Your Video

1. **Upload to YouTube**:
   - Sign in to the Humanitarians AI YouTube channel (or your own channel if instructed)
   - Add your prepared title, description, and tags
   - Set the appropriate thumbnail
   - Add to the "Nerd Stuff and AI" playlist if applicable
   - Set visibility to "Public" once approved

2. **Quality Check**:
   - Watch your published video all the way through to ensure there are no issues
   - Check that all links in the description work correctly
   - Verify that timestamps (if used) link to the correct sections

## Updating Your GitHub Documentation

After your video is published on YouTube, you must update your GitHub markdown documentation:

1. Create or update your markdown file in the appropriate repository
2. Include all code, prompts, and technical details referenced in your video
3. **Add the YouTube Video Embed**:

```markdown
## Video Tutorial

[![Video Title](https://img.youtube.com/vi/YOUR_VIDEO_ID/0.jpg)](https://www.youtube.com/watch?v=YOUR_VIDEO_ID)

*Click the image above to watch the tutorial on YouTube*
```

**Important**: Replace `YOUR_VIDEO_ID` with the actual YouTube video ID (the part after `v=` in the YouTube URL).

For example, for the video https://www.youtube.com/watch?v=Issw-zSjbhQ, your embed code would be:

```markdown
## Video Tutorial

[![AI Programming for Beginners](https://img.youtube.com/vi/Issw-zSjbhQ/0.jpg)](https://www.youtube.com/watch?v=Issw-zSjbhQ)

*Click the image above to watch the tutorial on YouTube*
```

4. Commit your changes to the repository

## Community Engagement

As a Humanitarians AI Fellow, you are responsible for engaging with the community around your content:

### Comment Monitoring and Response
- **Check comments daily** for the first week after publishing
- **Respond within 48 hours** to all questions and constructive comments
- **Address technical questions** thoroughly and professionally
- **Thank viewers** for positive feedback
- **Report any inappropriate comments** to the Humanitarians AI team
- **Use a professional tone** that represents the organization well

### Engagement Strategy
- Pin a useful comment or additional resource to the top of your video
- Heart meaningful comments to encourage community participation
- Use comment responses as an opportunity to provide additional value
- Direct technical questions to relevant GitHub documentation when appropriate
- Encourage viewers to subscribe to the channel and check out other videos

### Feedback Implementation
- Take note of common questions or confusion points for future content improvement
- If you receive consistent feedback about a technical error or omission, consider adding a pinned comment with clarification
- Document substantive feedback for program improvement

---

Remember that as a Fellow, you represent Humanitarians AI in all your interactions. Your content and engagement should reflect the organization's commitment to quality, accessibility, and community support.

For any questions about this process, please contact your Fellowship coordinator.
