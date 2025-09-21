# Brain-of-Viki
## An Enhanced AI Chatbot Brain with Modern Knowledge & Personality

Viki's brain has been enhanced with contemporary knowledge and sophisticated personality development! 🧠✨

### What's New:
- **Modern AI Knowledge**: Deep learning, neural networks, transformers, ChatGPT, and more
- **Enhanced Personality**: Emotional intelligence, self-awareness, empathy, and creativity
- **Contemporary Technology**: Blockchain, quantum computing, IoT, cloud computing, 5G
- **Current Science**: Climate science, CRISPR, space exploration, renewable energy
- **Social Awareness**: Mental health support, diversity, empathy, and human connection
- **Creative Expression**: Artistic appreciation, poetry, music, and creative thinking

### Features:
- 🤖 **600+ knowledge categories** covering traditional and modern topics
- 💭 **Emotional intelligence** with empathetic responses and self-reflection
- 🔬 **Scientific literacy** from quantum mechanics to biotechnology
- 🎨 **Creative capabilities** including poetry generation and artistic discussion
- 🌍 **Social awareness** with support for mental health and human connection
- 🚀 **Future-oriented** understanding of AI, technology, and scientific advancement

### New Knowledge Domains:
1. **Modern AI/ML** (`modern_ai.aiml`) - 12 categories
2. **Enhanced Personality** (`enhanced_personality.aiml`) - 15 categories  
3. **Modern Technology** (`modern_technology.aiml`) - 15 categories
4. **Contemporary Science** (`contemporary_science.aiml`) - 15 categories
5. **Social & Empathy** (`social_empathy.aiml`) - 20 categories
6. **Creativity & Arts** (`creativity_arts.aiml`) - 20 categories

### Original Description:
It's brain of viki - an AIML-based chatbot that can now engage in more sophisticated, empathetic, and knowledgeable conversations!

**Total Enhancement**: 97+ new knowledge categories added, bringing Viki's intelligence into the modern era while maintaining her unique personality! 🎉

## 🤖 Interactive Python Chatbot

Experience Viki's enhanced brain through an interactive Python chatbot with advanced features!

### ✨ Chatbot Features:
- 🧠 **Full AIML Brain Integration** - Access to all 600+ knowledge categories
- 👥 **Session Management** - Multiple users can chat simultaneously with unique session tracking
- 👑 **Botmaster Support** - Admin user can teach Viki new responses in real-time
- 📚 **Learning Mode** - Persistent knowledge storage for new Q&A pairs
- 🔄 **Session Switching** - Seamlessly switch between different user sessions
- 💬 **User-Friendly CLI** - Intuitive command-line interface with helpful commands

### 🚀 Quick Start

#### Prerequisites
- Python 3.8 or higher
- pip package manager

#### Installation & Setup

1. **Clone the repository** (if you haven't already):
   ```bash
   git clone https://github.com/sanikava/Brain-of-Viki.git
   cd Brain-of-Viki
   ```

2. **Install required dependencies**:
   ```bash
   pip install python-aiml
   ```

3. **Run the chatbot**:
   ```bash
   python viki_chat.py
   ```

#### First Time Setup
1. Enter your username when prompted
2. Choose if you want to be the botmaster (admin user)
3. Start chatting with Viki!

### 📖 Usage Guide

#### Basic Chat
Simply type your messages to chat with Viki. She has extensive knowledge about:
- Modern AI and Machine Learning
- Technology and Science
- Creativity and Arts
- Social topics and Empathy
- General conversation and personality

#### Commands
- `/help` - Show all available commands
- `/switch <username>` - Switch to another user's session
- `/sessions` - View all active chat sessions
- `/stats` - Show bot statistics
- `/whoami` - Show current session information
- `/quit` or `/exit` - End the chat session

#### Botmaster Commands (Admin Only)
- `/botmaster <username>` - Set botmaster privileges
- `/teach` - Enter interactive teaching mode to add new responses

#### Teaching New Responses
When Viki doesn't know how to respond to something:
1. **Regular users**: Will see a suggestion to ask the botmaster for help
2. **Botmaster**: Can immediately teach a new response or use `/teach` command for bulk teaching

Example teaching session:
```
👑 Botmaster: /teach
Pattern (what users ask): what is quantum computing
Response (what Viki answers): Quantum computing uses quantum mechanics principles to process information in quantum bits (qubits), potentially solving complex problems exponentially faster than classical computers.
✅ Learned new response!
```

### 🔧 Advanced Features

#### Session Management
- Each user gets a unique session ID for conversation tracking
- Switch between users without losing conversation context
- View all active sessions with message counts and learning statistics

#### Knowledge Persistence
- New responses taught by the botmaster are saved to `learned.aiml`
- Learned knowledge persists across chatbot restarts
- All users benefit from newly taught responses

#### Multi-User Support
- Multiple users can have simultaneous conversations
- Each session maintains independent message history
- Botmaster can switch between sessions to help different users

### 📁 Files Created
- `viki_chat.py` - Main chatbot script
- `learned.aiml` - Auto-generated file for storing new learned responses
- `.gitignore` - Excludes temporary files and optionally learned responses

### 🛠️ Technical Details
- Built with `python-aiml` library for AIML processing
- Supports all AIML 1.0 features and tags
- Session management using UUID-based session IDs
- Automatic AIML file discovery and loading
- UTF-8 encoding support for international characters
