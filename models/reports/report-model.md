# [Report Title]
[Name of campaign, sample, incident, or investigation] – [Date]

# 1. Objective
[Explain in 1–2 sentences what the report analyzes.]

Ex.: This report presents an initial analysis of a malware sample distributed via phishing emails targeting the financial sector.

# 2. Context
[Briefly describe the scenario that motivated the analysis.]

Ex.: In recent days, there has been an increase in the sending of emails containing .doc attachments with malicious macros. Similar samples were reported by [public source], indicating a possible coordinated campaign.

# 3. Summary of Key Findings
- [Finding 1]
- [Finding 2]
- [Finding 3]
- [Summary of Potential Impact]

# 4. Evidence and Technical Details

## 4.1 Indicators (IOCs)
**Hashes:**
- MD5:
- SHA256:

**IP Addresses/Domains:**

- IP:
- Domain:
- URL:

## 4.2 Tactics, Techniques, and Procedures (MITRE ATT&CK)
- **Tactic:** [Ex. Initial Access]
- **Technique:** [Ex. T1566.001 – Spearphishing Attachment]
- **Short Description:** [Explain in one sentence how this technique appears in the campaign.]

## 4.3 Observed Behavior
[Describe in short paragraphs or bullet points.]

Ex.:
- The file contains a VBA macro that downloads a payload hosted on a compromised domain.

- The malware establishes persistence via a Run key in the registry.

- C2 communication via HTTP to /update.php.

## 4.4 Complementary Analysis (optional)
[Include any other relevant evidence: timeline, fl]()