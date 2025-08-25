Multi-Agent Browser Automation
Turn natural language into automated browser actions with AI-powered agents
:sparkles: Features
Natural Language Interface: "Book a table for 2 tonight" → Automated booking
Multi-Agent Collaboration: Navigation, interaction, extraction, and validation agents work together
Live Execution View: Watch agents collaborate in real-time
Multi-User Support: Handle multiple users and tasks simultaneously
:rocket: Quick Start
# Clone and install
git clone https://github.com/NizzCorp-O/Glot.ai.git
cd browser-agent-system

# Backend (Python)
cd backend && pip install -r requirements.txt
export OPENAI_API_KEY="your_key"
python main.py

# Agent Layer (Node.js) 
cd agent-layer && npm install && npx playwright install
npm start

# Frontend
cd frontend && npm install && npm start
Open http://localhost:3000 and start automating!
:bulb: Usage
# Simple task
"Check iPhone 15 price on Apple.com"

# Complex task  
"Compare flight prices NYC to Paris on Dec 15, book cheapest under $800"

# Monitoring task
"Track Tesla stock price daily and email me if it drops 5%"
:building_construction: Architecture
User Input → Python Backend (AI/NLP) → Node.js Agents → Browser Automation → Results
                    ↓
            Redis (Communication) → WebSocket (Live Updates)
:handshake: Agent Types
Navigation: Page loading and routing
Interaction: Forms, clicks, user actions
Extraction: Data collection and parsing
Validation: Quality assurance and verification
:bar_chart: Example Flow
User: "Find Italian restaurants with 4+ stars for tonight"
Navigation agent opens restaurant sites
Search agent finds restaurants matching criteria
Extraction agent collects ratings, availability, prices
Validation agent verifies data quality
Results presented to user with booking options
:wrench: Configuration
# Environment variables
OPENAI_API_KEY=your_openai_key
REDIS_URL=redis://localhost:6379
BROWSER_HEADLESS=false
MAX_CONCURRENT_AGENTS=10
:bug: Troubleshooting
Agents timing out: Increase AGENT_TIMEOUT value
Browser not closing: Run pkill -f "chromium"
Redis connection: Check redis-cli ping
:handshake: Contributing
Fork the repo
Create feature branch: git checkout -b feature/name
Commit changes: git commit -m 'Add feature'
Push: git push origin feature/name
Open pull request
:page_facing_up: License
MIT License - see LICENSE file.
Ready to automate the web? Get started in 5 minutes! :rocket:
claude.aiclaude.ai
Claude
Talk with Claude, an AI assistant from Anthropic (12 kB)
