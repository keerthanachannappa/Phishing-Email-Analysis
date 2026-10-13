# Phishing-Email-Analysis
A beginner cybersecurity project analyzing a phishing email sample and identifying common phishing indicators.
# Phishing Email Analysis

## 1. Objective
To identify phishing characteristics in a suspicious email sample by analyzing the sender address, email headers, URLs, and message content.

## 2. Tools Used
- GitHub — project documentation and evidence storage
- Google Admin Toolbox Messageheader — email header analysis
- Text editor — inspection of the raw email source

## 3. Methodology
1. Obtained a sample email from a public cybersecurity training repository.
2. Examined the sender address and subject.
3. Reviewed SPF, DKIM, and DMARC authentication results.
4. Inspected the email body for urgency and social-engineering indicators.
5. Identified a shortened URL without opening it.
6. Documented the findings and captured screenshots.

## 4. Key Findings
- The sender used the domain `microsoftonline-verify.com`.
- SPF authentication reported failure.
- DKIM authentication reported failure.
- DMARC authentication reported failure.
- The message contained a shortened `bit.ly` link with an unverified destination.
- The message used urgent account-security language.

## 5. Conclusion
The combined indicators suggest that the sample is likely a phishing email. Authentication failures alone do not prove malicious intent, so the assessment also considers the sender domain, message content, and link characteristics.

## 6. Repository Contents
- `sample/phishing_email.txt` — raw email sample
- `screenshots/email_sample.png` — email sample screenshot
- `screenshots/header_analysis.png` — header analyzer screenshot
- `report/phishing_analysis_report.md` — detailed findings and conclusion

## 7. Safety Precautions
- Did not click the shortened URL.
- Did not open any attachments.
- Used the sample for defensive cybersecurity analysis.
- Redacted personal information before publishing evidence.
