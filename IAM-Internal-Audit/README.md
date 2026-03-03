User Access Control Audit: Production Database
Organization: Carraway IT Consultants Auditor: Tia Mitchell, GRC Analyst Date: January 2026 

Executive Summary
This internal audit resulted in a rating of Needs Improvement for the Production Database access controls. The review identified five high-risk findings that expose the organization to unauthorized data access and potential regulatory non-compliance. Remediation is required to align the IAM lifecycle with NIST SP 800-53 and ISO 27001 standards.

Key Audit Findings
The audit compared active system accounts against HR records and the internal Role-Based Access Control (RBAC) matrix:
Orphaned Accounts: Two accounts (Alice and Bob) remained "Active" despite the employees being terminated.
Privilege Creep: Admin-level access was identified for non-DevOps roles, including a Developer and an Intern.
Process Failure: A communication gap exists between HR and IT, resulting in a failure of the deprovisioning workflow.
Manual Provisioning Risks: Access levels are manually assigned without automated guardrails, allowing improper permission inheritance.
Management Action Plan
To resolve these findings, the following actions were mandated:
Immediate Deactivation: All orphaned accounts were flagged for deactivation by EOD of the audit date.
Access Recertification: A full review of all Admin permissions is scheduled for completion by February 20, 2026.
Automation: Implementation of an automated ticketing trigger between HR software and Active Directory to ensure deprovisioning occurs within 24 hours of termination.
📄 View Full Internal Audit Report (PDF)
