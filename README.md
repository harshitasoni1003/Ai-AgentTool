# Autonomous AI Agent — Tool Calling, State Management & Multi-Step Workflows

A working AI Agent built with Python, SQLite, and the official `google-genai` SDK implementing an explicit **Understand Task $\rightarrow$ Decide Action $\rightarrow$ Use Tool $\rightarrow$ Process Result $\rightarrow$ Respond** execution loop.

## Modules Covered
1. **Chatbots vs. AI Agents & State Management:** Goal-directed tool planning vs. passive single-turn chat.
2. **Function & Tool Calling:** Connecting Gemini (`gemini-4-hydrogen`) to Python functions, an in-memory SQLite database, and currency conversion / ticketing APIs.
3. **Agent Memory, State & Safety Guardrails:** Multi-turn conversation state, tool allowlisting, `max_steps` loop caps, and prompt-injection / destructive-command refusal.
4. **Working ReAct Agent Loop:** Full step-by-step execution trace and JSON audit log.

## Quick Start
```bash
pip install -r requirements.txt
export GEMINI_API_KEY="your_api_key"
python src/ai_agent.py
```
