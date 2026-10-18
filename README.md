# salesforce-rest-integration-middleware
Automated B2B lead qualification, territory assignment, and opportunity-to-quote governance using native Salesforce declarative tools.
# Salesforce REST API & External System Middleware 🔗

Maintained by **Ankita Mahajan** — Secure integration architecture bridging external backend microservices with Salesforce custom objects via OAuth 2.0 and REST endpoints.

---

## 📌 Project Overview
Engineered a secure bi-directional synchronization bridge between an external order management service and Salesforce. The system handles external webhook payloads, authenticates via Connected Apps, and maps incoming JSON data directly into custom Salesforce objects using custom metadata configurations.

## 🛠️ Core Salesforce Components Built
- **API & Security Configuration:** Set up Connected Apps, OAuth 2.0 authentication flows, and Named Credentials.
- **Custom Metadata:** Managed endpoint configurations and environment variables securely using Custom Metadata Types.
- **Payload Mapping:** Designed field mapping structures to translate REST JSON responses into Salesforce records cleanly.
- **Error Logging:** Configured integration logs and exception handling tables to track synchronization failures.
