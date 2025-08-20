# Video Description Instruction Feedback

None of these messages followed the instructions provided at https://github.com/Humanitariansai/YouTube. Always give a YouTube description and Title to the media team that they can cut and paste and NOT REWRITE.

The instructions require:
- A descriptive title clearly indicating content is part of the Humanitarians AI Fellows program
- A description with specific formatting including:
  - Brief summary (2-3 sentences)
  - What viewers will learn (bullet points)
  - Required links (exactly as shown in the template)
  - Resources mentioned section with GitHub repository link
  - Creator name and LinkedIn URL
  - Exactly 15 hashtags related to the content


#### Example Prompt

```
Create a descriptive, engaging title that clearly indicates the content is part of the Humanitarians AI Fellows program, for example:
- "How to Build a Simple AI Chatbot | Nerd Stuff and AI Ep.2"
- "Understanding Machine Learning Models | Nerd Stuff and AI with Humanitarians AI"

Your description should include:
1. A brief summary of the video content (2-3 sentences)
2. What viewers will learn (bullet points work well)
3. Required links (always include these exactly as shown):

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

4. ALWAYS include exactly 15 hashtags related to the content at the very bottom of the description

[Cut and Paste the Markdown file you created for the video]
```


# Message 1: Project Completion Update

As part of the Mycroft project, I have completed the task of building an Intelligence Agent workflow in N8N to perform sentiment analysis on Reddit posts. The objective was to extract posts from Reddit, analyze their sentiment, and store the results for further insights.

The workflow begins with a manual trigger to execute the process, followed by a Reddit node that fetches posts related to a chosen topic. The data is then cleaned and formatted using an Edit Fields node before being passed to the Sentiment Analysis model, which classifies each post as positive, neutral, or negative. I also integrated the Groq Chat Model for more advanced interpretation or quick summaries. Finally, the results are saved into a Google Sheet, allowing for easy tracking and analysis of sentiment trends over time.

This workflow demonstrates how Intelligence Agents can capture market awareness by monitoring community discussions. Future enhancements may include scheduling automated runs, connecting to visualization tools such as Power BI or Tableau, incorporating additional data sources like Twitter or financial news, and refining sentiment scoring for deeper insights.

For reference, I have attached a short video walkthrough that explains the workflow and its components, along with a screenshot of the workflow for quick visualization.

# Message 2: YouTube Content Proposal

Dear Media Team,

I hope this email finds you well.

I've created an educational video tutorial demonstrating the Mycroft Social Sentiment Agent that I built using n8n workflow automation. This video showcases the complete implementation of our AI-powered investment intelligence system and would be valuable content for our YouTube channel.

**Video Details:**
* **Title:** Mycroft Social Sentiment Agent - Building AI-Powered Investment Intelligence with n8n
* **Duration:** Approximately 11 minutes
* **Content:** Complete walkthrough of the n8n workflow that collects data from multiple platforms (StackOverflow, GitHub, Reddit), processes it through AI sentiment analysis using Groq/Llama 3.1, and generates investment intelligence signals

**Video Link:** [LINK REMOVED]

**Suggested YouTube Description:**
"Learn how to build an AI-powered Social Sentiment Agent using n8n workflow automation. This tutorial demonstrates the complete implementation of the Mycroft Framework's Social Sentiment Agent, which analyzes social media discussions to generate investment intelligence.

What You'll Learn:
- Multi-platform data collection from StackOverflow, GitHub, and Reddit
- AI sentiment analysis using Groq API and Llama 3.1
- Topic classification and signal quality filtering
- Automated data storage with Google Sheets integration
- Building production-ready investment intelligence systems

This is part of the Mycroft Framework - an open-source educational experiment in AI-powered investment intelligence.

GitHub Repository: [REPOSITORY LINK REMOVED]
n8n Workflow JSON: Available in the repository

Connect with the creator:
LinkedIn: [LINKEDIN LINK REMOVED]

#AI #InvestmentIntelligence #MachineLearning #Automation #Mycroft #SentimentAnalysis #OpenSource"

**Additional Resources for Video:**
* The complete n8n workflow JSON is available in our GitHub repository under n8n_Workflows/Social_Sentiment_Agent
* Documentation is available in the repository README

Please let me know if you need:
* The video in a different format
* Additional thumbnails or graphics
* Any edits to the video content
* Timestamps for specific sections

I'm happy to provide any additional materials or make adjustments as needed for our YouTube channel standards.

Thank you for helping share this educational content with our community.

# Message 3: Project Demo Completion

I've completed the recordings for the Mycroft project demo, showcasing the Financial Intelligence Agent I've built. The videos walk through the full n8n workflow starting from multi-source news collection, applying FinBERT-based sentiment and risk scoring, writing results to PostgreSQL, and generating daily intelligence reports and alerts.

Video 1 – FinBERT Integration Overview
[LINK REMOVED]

Video 2 – Full Financial Intelligence Workflow (End-to-End Demo)
[LINK REMOVED]