GoldScope AI - fixed date range

1. Install Python 3.15 (you already have it detected by the py launcher).
2. Open Command Prompt in this folder.
3. Run: py -m pip install -r requirements.txt
4. Run: py -m streamlit run app.py
5. Open http://localhost:8501 in Chrome.

The history request is clamped to start no earlier than 2026-09-21 for the free API tier.
If the provider still returns a plan-gated error, check the exact date in that error and update the allowed date accordingly.
AI chat requires a valid OPENAI_API_KEY environment variable and a model name enabled for your API account.
This app does not connect to MT5 or place trades. Market data may be delayed.
