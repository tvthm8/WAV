# 🧠 WAV AI  – Part 1

**WAV** (Web-Accessing Virtual Assistant) is a lightweight, terminal-based AI agent designed for interactive and personalized web search. This is Part 1 of an evolving assistant project focused on foundational user interactions and AI-driven information retrieval.

## ✅ Features

- 👤 **User Registration & Persistence**  
  Stores user name and age (with anonymous mode and age restriction enforcement).

- 🧠 **AI Query Agent**  
  Connects to an AI agent to search the web and return summarized results.

- 🕘 **Search History**  
  Displays the 3 most recent searches for returning users.

- 📂 **SQLite Integration**  
  Uses a local SQLite database (`wav_data.db`) for persistent user data and search logs.

- 🚦 **Age Verification**  
  New users under 16 are not allowed to proceed for safety and compliance.

## 📁 Project Structure

```
WAV/
├── agent_tools.py         # Handles AI request logic
├── config.py              # Environment and configuration settings
├── database.py            # SQLite interface for user and search storage
├── main.py                # Entry point script with command-line interface
├── response_encoder.py    # Formats responses (planned for future use)
├── wavfunc1.py            # User onboarding and age verification logic
├── wav_data.db            # Local SQLite DB storing user data and search logs
```

## 🛠️ Tech Stack

- Python 3.10+
- SQLite3
- Custom AI agent handler (modular for external API or local LLM integration)
- CLI-based interface (cross-platform)

## 🚀 Getting Started

1. **Clone the repo**
   ```bash
   git clone https://github.com/your-username/wav-ai.git
   cd wav-ai/WAV
   ```

2. **Install dependencies**
   *(If using Poetry)*
   ```bash
   poetry install
   ```

3. **Run the assistant**
   ```bash
   python main.py
   ```

## 🧩 Coming Soon (Part 2+)

- 🔊 Voice interaction & TTS
- 🧬 Personalized context memory
- 🧭 Conversational follow-ups
- 🌐 Smarter search query expansion
- 📖 Natural language history commands
- 🔐 Multi-user support & login
