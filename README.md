# SCU ACM — Fall AWS Hackathon
> **Santa Clara University ACM**

Welcome! This repo has two tutorials to get you up and running with AWS. Complete them in order.

---

## Fundamental Rules
1. **Never Hardcode Credentials**: Do NOT paste `AWS_ACCESS_KEY_ID` or `AWS_SECRET_ACCESS_KEY` directly in your code.
2. **Never Call AWS from the Frontend**: Your React/iOS/web app should never contain AWS credentials or SDK calls. Call AWS from your backend only.
3. **Stick to One Region**: Use **`us-east-1` (N. Virginia)** for all resources.

---

## Tutorial 1 — Setup
**Start here.** Log into AWS Workshop Studio, create an IAM user with Bedrock permissions, and get your credentials loaded into your terminal.

→ [1-setup/README.md](1-setup/README.md)

## Tutorial 2 — Bedrock
**Do this after Tutorial 1.** Set up a Python virtual environment and call an Amazon Bedrock AI model using the two starter files.

→ [2-bedrock/README.md](2-bedrock/README.md)
