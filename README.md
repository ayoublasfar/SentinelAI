# SentinelAI - Ongoing Developement
SentinelAI is a SaaS platform with complete solution to audit security of web sites assisted by AI
It scans web sites for an extensive list of vulnerabilities with advanced scripts powered by a diversified list of ML models for maximum detection
AI models are fine-tuned to such type of data from scans to provide an audit that is comprehensive yet advanced to detect patterns and probability of system failure/attack

Initial prototype features:
Web Discovery: Advanced website domain recognition and information scrapping (WHOIS, DNS, Robots.txt, public files, security files and mail addresses, bug bounty program existence, location, ...etc) aswell as scanning exposed ports and other techniques applied on the target domain.

Vulnerabilities Scan: Offensive techniques applied on target website to detect vulnerabilities, map attack surface, define how to exploit findings and structure data. It automates the scanning of common and most ciritical web vulnerabilities. Configurable with scan depth, maximum number of links, robots.txt respect, including forms which may affect the false positive results and predefined subdomains list.
*Note:* Further parameters for each vulnerability are going to be configuratble aswell in the next update.

AI Prioritization: Scores vulnerabilities based on context (e.g., severity, exploitability, regulatory impact) and provides tailored remediation advice. Enables AI-driven prioritization and risk scoring. Based on vulnerability type, affected component, site context (e.g. login page, admin panel), and with the following models: Heuristic Scoring Tables, Compliance-aware Scorers (PCI DSS, HIPAA, SOX), Temporal decay for CVE age, an output with all details and scores is produced for each vulnerability on each link scanned.

Threat Graph: Builds interactive graphs to show attack paths between vulnerabilities and identify potential exploitation routes. Integrates GNN models to predict high-risk chains.

<img width="906" alt="image 1" src="https://github.com/user-attachments/assets/cb078c23-30ae-41fc-bb76-9a984f35621b" />



