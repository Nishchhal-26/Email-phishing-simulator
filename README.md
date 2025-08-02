# Email-phishing-simulator
<img width="565" height="357" alt="image" src="https://github.com/user-attachments/assets/b9859af0-1553-4a0d-b832-5e14b5f5c74f" />

Red Team TTPs (Tactics, Techniques, Procedures)
1. Pretexting - Creating a believable job portal theme to increase click‑through rate.

2. Social Engineering Simulation - Enticing users with a “Job Application/Login” prompt.

3. URL Masking

  a. Custom Render domain or

  b. URL shorteners (Bitly/TinyURL) to make links appear legitimate.

OSINT & Targeting Support
1. WHOIS & Recon Tools 

  a. For choosing realistic domain names and ensuring target plausibility.

2. Shodan / Google Dorks

  b. To assess the target’s digital footprint (for realism in social engineering).

Logging & Monitoring
1. Custom Python Logging - Captures date, IP, User-Agent, and credentials into phishing_attempts.log.

2. Dashboard View (Flask) - For live monitoring of phishing attempts.

Network Exposure (Optional)
1. ngrok - To create a temporary public link for local Flask app.


