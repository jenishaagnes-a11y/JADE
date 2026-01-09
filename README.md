JADE - Javascript Advance Domain Enforcer
🚨 Problem Statement

--Modern websites execute dozens of third-party JavaScript files automatically.
--Users have no visibility or control over what these scripts actually do.

-Existing Issues:

--Hidden tracking & surveillance scripts

--Silent data access without UI changes

--Ad-blockers only block known lists, not unknown behaviors

--No explanation of why a script is dangerous

💡 Our Solution

--JADE is a policy-driven browser extension that applies --Zero-Trust Security to JavaScript execution.

🔑 Core Idea

--Every website starts with zero trust

--JavaScript actions are monitored in real time

--Actions are allowed or blocked based on intent, not reputation

--Users are shown clear explanations for every security decision

✨ Key Features
🧠 Intent-Based JavaScript Classification

Classifies scripts based on behavior:

--Tracking

--UI Interaction

--Data Access

-Silent Surveillance

👁️ Silent Surveillance Detection

--Detects scripts that:

--Access cookies, storage, sensors, or identifiers

--Without any visible UI interaction

📊 Website Security Risk Score

--Dynamic risk score based on actual behavior

--Not dependent on blacklists or domain reputation

🔍 Explain-Why Alerts

--Every blocked action is explained in simple human language

--Helps users understand what happened and why

🔐 Zero-Trust Policy Engine

--Unknown sites start with no permissions

--Policies stored per-site

--Fully user-controlled

🏗️ Technical Architecture
🧩 Built As

--Chrome Extension (Manifest V3)

--Lightweight & fast (no heavy ML)

⚙️ Technologies Used

--JavaScript – behavior interception & policy engine

--HTML + CSS – UI dashboards and popups

Chrome Extension APIs:

--scripting

--storage

--activeTab

🔄 How It Works (High-Level Flow)

--Website loads JavaScript

--content.js monitors script behavior

--Behavior sent to background.js

--Policy Engine evaluates intent

Action is:

--✅ Allowed

--❌ Blocked

--⚠️ Flagged with explanation

Risk score updated in dashboard

🎯 Impact & Benefits

🚫 Prevents hidden tracking

🔒 Protects user privacy

🧠 Increases awareness of web behavior

🛡️ Reduces JavaScript attack surface

👥 Ideal For

Privacy-conscious users

--Students & researchers

--Enterprises

Parental control systems

🔍 Why JADE is Different
--Traditional Blockers	JADE
--Static blacklists	Real-time behavior analysis
--Blocks what	Explains why
--Reputation-based	Intent-based
--No transparency	Full user visibility
📚 Research & References

--Zero-Trust Security Architecture

--OWASP JavaScript Security Risks

--Browser Content Security Policies (CSP)

--Studies on Web Tracking & User Profiling

--Limitations of Traditional Ad-Blockers

🏁 Key Takeaway

--JADE brings Zero-Trust and intent awareness directly into the browser.
--It doesn’t just block JavaScript — it understands intent, detects silent surveillance, and explains risk clearly.

OUTPUT:

![alt text](<Screenshot 2026-01-10 045738.png>)
![alt text](<WhatsApp Image 2026-01-10 at 4.41.33 AM.jpeg>)
![alt text](<WhatsApp Image 2026-01-10 at 4.42.14 AM.jpeg>)
![alt text](<WhatsApp Image 2026-01-10 at 4.43.46 AM.jpeg>)

