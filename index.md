Zaph Privacy Policy

Last Updated: December 2025

Zaph (“the Service”, “we”, “us”) provides AI-powered standup generation, engineering analytics, and workflow insights.
This Privacy Policy explains what information we collect, how we use it, and how we comply with privacy laws including GDPR and CCPA.

⸻

1. Information We Collect

1.1 From Atlassian Products (Jira, Confluence)

If your organization connects Jira or Confluence, Zaph may collect:
	•	Atlassian accountId
	•	Issue metadata (summary, status, assignee, timestamps)
	•	Sprint and project metadata
	•	Confluence page titles, change logs, and activity
	•	No passwords are collected
	•	No content is modified by Zaph

1.2 From Other Integrations

If connected:

Slack
	•	Channel names
	•	Message metadata (not stored longer than required for summaries)

GitHub
	•	Pull request events
	•	Commit metadata
	•	Repository names

1.3 Authentication Data
	•	OAuth tokens (encrypted using AWS KMS)
	•	Tenant and user identifiers

We do not store plaintext access tokens.

⸻

2. How We Use Data

We use integration data strictly to:
	•	Generate automated standup summaries
	•	Provide engineering signals and activity insights
	•	Enhance team productivity reporting
	•	Improve product performance and accuracy

We do not sell, share, or monetize your data.

⸻

3. Data Storage & Security

Zaph uses industry-standard protections provided by Amazon Web Services (AWS):
	•	Data is encrypted at rest using AWS KMS
	•	Data is encrypted in transit using TLS 1.2+
	•	Access is restricted via IAM least-privilege policies
	•	All requests are logged and monitored

⸻

4. Data Retention

Data is retained while:
	•	A tenant’s account remains active
	•	The integration (Slack, GitHub, Jira, etc.) is enabled

When a tenant disconnects an integration or deletes their account, all associated data is deleted within 30 days.

⸻

5. User Rights (GDPR, CCPA)

Users may request:
	•	Export of their personal data
	•	Deletion of their personal data
	•	Details on what personal data is stored

Requests can be sent to: privacy@zaph.ai

Zaph complies with:
	•	GDPR (EU)
	•	CCPA (California)
	•	Atlassian Personal Data Reporting API requirements

⸻

6. Sub-processors

We use the following trusted infrastructure providers:
	•	Amazon Web Services (AWS) for compute, storage, encryption
	•	OpenAI for AI model inference (text processing only; no long-term storage)

No other parties receive your data.

⸻

7. Contact

For privacy or data protection questions, contact:

privacy@zaph.ai

⸻

End of Policy
