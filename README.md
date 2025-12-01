# Samachar AI 🗞️🤖

An end-to-end AI-powered journalist that scrapes news and Reddit content using the Model Context Protocol (MCP), summarizes it via LLMs, and converts it into audio.

---

## 🛠️ Project Build-up Workflow

### Phase 1: Frontend Setup
- Set up Streamlit for user input
- Allow users to enter topics and sources
- Display backend responses

### Phase 2: Backend Logic
- Scrape data from Google News & Reddit
- Summarize using LLM
- Convert summary to audio
- Send response to frontend

### Phase 3: Scrapers & Bright Data
- Configure Bright Data MCP for scraping
- Implement Text-to-Scraping logic
- Set up FastAPI endpoints

### Phase 4: Integration
- Connect frontend and backend
- End-to-end testing

---

## 🧠 How It Works

1. **Input**: User enters topics and preferred sources (Google News, Reddit)
2. **Scraping**: Bright Data MCP scrapes content while avoiding anti-bot mechanisms
3. **Summarization**: LLM processes and summarizes the scraped content
4. **Audio Conversion**: Text-to-Speech converts the summary into audio
5. **Output**: User receives a personalized news report in text and audio formats

---

## 🚧 Challenges Addressed

- Anti-bot mechanisms during web scraping
- Integration of multiple tools and APIs
- Real-time data processing and summarization

---

## 🚀 Getting Started

### Prerequisites
- Python 3.9 or higher
- API keys for:
  - Bright Data (for web scraping)
  - Your preferred LLM (OpenAI, Anthropic, Groq, or Ollama)
  - ElevenLabs (for text-to-speech)

### Installation

**Clone the repository**
```bash
git clone https://github.com/YOUR_USERNAME/Samachar-AI.git
cd Samachar-AI
pip install -r requirements.txt
