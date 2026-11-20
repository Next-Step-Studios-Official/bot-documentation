# NEXT STEP STUDIOS

# SECURITY AND DATA PROTECTION OVERVIEW

**Document version:** 0.2.0  
**Status:** Draft for review. Not yet effective.  
**Prepared:** November 19, 2026  
**Operator:** Candler Shaw, operating under the public-facing name Next Step Studios  
**Contact:** [nextstepstudiosofficial.contact@gmail.com](mailto:nextstepstudiosofficial.contact@gmail.com)  
**Applies to:** The Next Step Studios Discord bot operating in the single private Next Step Studios Discord server

---

## 1. Purpose

Next Step Studios takes the security and responsible handling of information processed by its Discord bot seriously.

This Security and Data Protection Overview (the **"Overview"**) explains the general principles guiding the protection of Bot-related information, the current operating context, and the safeguards that should be maintained as the Bot develops.

The Bot is operated by **Candler Shaw**, using the public-facing name **Next Step Studios** (the **"Operator"**).

The Bot is intended exclusively for one private Next Step Studios Discord server (the **"Server"**).

This document is intended for Server members and other individuals who want to understand the Operator's general approach to security.

It is not a technical security manual and does not disclose sensitive internal configuration, credentials, infrastructure details, or incident-response procedures.

---

## 2. Current Operating Context

The Bot is under development and testing.

Its current testing arrangement involves hosting it on the Operator's own computer rather than relying on a confirmed production hosting provider.

The current understanding is:

- Application answers and staff-related information are stored in a local database.
    
- Some temporary workflow information is stored in JSON files.
    
- Announcement history is intended to be stored in SQLite.
    
- Ticket transcript generation and persistence have not been fully verified.
    
- Persistent moderation and infraction recordkeeping are planned.
    
- A dedicated ban appeal workflow is planned.
    
- The encryption-at-rest status of the local database and related files has not been confirmed.
    
- The backup lifecycle and backup-retention schedule have not been finalized.
    

These details are included to avoid suggesting that the Bot already operates with a mature production security environment.

The Operator must verify the actual implementation before making stronger public security commitments.

---

## 3. Security Principles

The Operator's intended security approach is based on the following principles.

### 3.1 Access limitation

Information should be accessible only to the Operator and individuals who have a legitimate reason and appropriate authorization to access it.

Server membership or a general staff role should not automatically provide access to every private record.

### 3.2 Data minimization

The Bot should process and retain only the information reasonably necessary for its intended Features.

Unnecessary personal information should not be collected or retained merely because it is technically available.

### 3.3 Protection of credentials

Bot tokens, passwords, API keys, and other authentication secrets must be protected.

They should not be included in public documents, ordinary User-facing messages, or logs that do not require them.

### 3.4 Responsible storage

Databases, temporary files, logs, and backups should be protected according to the sensitivity of the information they contain.

A local file or database is not automatically secure simply because it is stored on a computer controlled by the Operator.

### 3.5 Controlled changes

Changes to the Bot's code, permissions, storage, and configuration should be reviewed and tested to reduce the risk of introducing security problems.

### 3.6 Accurate disclosure

The Operator should describe security measures honestly.

A safeguard should not be represented as implemented merely because it is planned, recommended, or supported by the underlying software.

---

## 4. Access to Bot Data

The current confirmed access arrangement is that the Operator is authorized to review stored User information for legitimate Bot administration, application review, troubleshooting, and related responsibilities.

Access to information should be limited according to the purpose of each Feature.

For example:

- Application information should be accessible to individuals responsible for application review.
    
- Ticket information should be accessible to individuals responsible for handling the relevant ticket.
    
- Administrative records should be accessible only to individuals with the required permissions.
    
- Technical records should be accessible only to individuals who need them for maintenance or security purposes.
    

Any expansion of access beyond the current Operator-only arrangement should be deliberate and supported by appropriate permissions.

The Operator should review access when responsibilities change or when someone no longer needs access.

---

## 5. Storage and Data Protection

### 5.1 Local testing environment

The Bot is currently being tested on the Operator's own computer.

This means that the security of the testing environment depends in part on the security of that computer, its user accounts, storage, operating system, and access controls.

Local storage should not be interpreted as a guarantee that information cannot be accessed by another person.

### 5.2 Databases and files

The Bot's development and testing arrangement includes SQLite and JSON-based storage for certain workflows.

The security of these records depends on the actual configuration of the storage location, file permissions, device security, backups, and other safeguards.

### 5.3 Encryption

The encryption-at-rest status of the Bot's local database and related files has not been confirmed for this draft.

Accordingly, this document does not claim that every database, JSON file, transcript, log, or backup is encrypted at rest.

The Operator must verify the applicable requirements and implement the necessary safeguards before production use.

### 5.4 Backups

The backup system and its lifecycle have not been fully verified.

Before relying on backups for production recovery, the Operator should establish:

- What information is backed up.
    
- Where backups are stored.
    
- Who can access them.
    
- How backups are protected.
    
- How long they are retained.
    
- How outdated backups are removed.
    
- How deletion requests are handled in relation to backups.
    

### 5.5 Temporary information

Temporary workflow data should not remain indefinitely after its purpose has ended.

Temporary files, announcement drafts, and other intermediate records should have defined cleanup behavior.

Cleanup mechanisms must be tested rather than assumed to work.

---

## 6. Credentials and Administrative Access

Authentication secrets are particularly sensitive.

The Operator should protect:

- Discord bot tokens.
    
- API keys.
    
- Database credentials, if used.
    
- Hosting credentials, if applicable.
    
- Administrative account credentials.
    
- Other secrets that could allow unauthorized access.
    

Credentials should not be placed in public repositories, policy documents, screenshots, support requests, or ordinary diagnostic messages.

Where a credential may have been exposed, the Operator should assess whether it needs to be revoked or rotated.

The Bot's permissions should follow the principle of least privilege: the Bot should receive only the Discord permissions reasonably required for its intended Features.

---

## 7. Development and AI-Assisted Work

The Operator may use AI-assisted development tools to help create, review, troubleshoot, or improve the Bot's software.

This does not mean that private User information should be shared with those tools.

The Operator should use:

- Synthetic test data.
    
- Redacted examples.
    
- Non-identifying error messages.
    
- Technical descriptions that do not reveal private User submissions.
    

Identifiable application answers, private ticket conversations, appeal materials, and other private User records should not be supplied to an AI service merely because that service is being used to assist with software development.

If a future Feature directly integrates an AI service or sends Bot Data to an external AI provider, the data flow must be assessed and disclosed before the integration is enabled.

---

## 8. Software Maintenance and Updates

The Bot is software that requires ongoing maintenance.

The Operator should:

- Review code changes before deployment.
    
- Test important workflows.
    
- Keep dependencies reasonably current.
    
- Review permission changes.
    
- Investigate unexpected errors.
    
- Avoid exposing internal configuration through error messages.
    
- Preserve data integrity during database changes.
    
- Review changes that affect personal information.
    
- Maintain appropriate recovery procedures.
    

Not every software update can be guaranteed to be free of defects.

If an update introduces a problem, the Operator should take reasonable steps to investigate and correct it.

---

## 9. Discord Platform Security

The Bot relies on Discord's platform and APIs.

The Operator does not control Discord's internal infrastructure, account security systems, platform availability, or independent data practices.

Users should:

- Protect their Discord accounts.
    
- Use strong, unique credentials.
    
- Enable available account security protections.
    
- Never share passwords or authentication codes.
    
- Be cautious of suspicious links and files.
    
- Report suspected account compromise through Discord's official support channels.
    

The Operator will not ask Users to provide their Discord password, account token, or authentication codes as part of a Bot support or privacy request.

---

## 10. Reporting a Security Concern

If you believe you have discovered a security issue involving the Bot, report it privately to the Operator.

**Security contact:** [nextstepstudiosofficial.contact@gmail.com](mailto:nextstepstudiosofficial.contact@gmail.com)

Please provide:

- A concise description of the issue.
    
- The affected Bot Feature, if known.
    
- The approximate date and time.
    
- The steps needed to understand or safely reproduce the issue, if available.
    
- Any relevant error message or non-sensitive technical information.
    

Do not:

- Exploit the issue beyond what is reasonably necessary to demonstrate it.
    
- Access another person's private records.
    
- Attempt to extract credentials or tokens.
    
- Disrupt the Bot or Server.
    
- Publish sensitive details before the Operator has had a reasonable opportunity to assess the report.
    

Do not include passwords, API keys, Bot tokens, authentication codes, or other secrets in a security report.

The Operator may request additional non-sensitive information to understand the concern.

---

## 11. Security Incidents

A security incident may involve suspected or confirmed:

- Unauthorized access.
    
- Unauthorized disclosure.
    
- Loss of stored information.
    
- Unauthorized modification of records.
    
- Compromised credentials.
    
- Malicious software.
    
- Exploitation of a software vulnerability.
    
- Unexpected exposure of private User information.
    

If the Operator becomes aware of a suspected or confirmed incident, the Operator should assess the situation and take reasonable steps to:

1. Understand what happened.
    
2. Limit ongoing exposure or unauthorized access.
    
3. Protect affected systems and records.
    
4. Determine what information may be involved.
    
5. Preserve relevant information needed for investigation.
    
6. Correct the underlying issue where possible.
    
7. Determine whether Users, Discord, or another party must be notified.
    
8. Follow applicable legal and contractual obligations.
    

Not every technical error constitutes a personal-data breach. The circumstances and information involved must be assessed.

The detailed internal procedures for responding to incidents are maintained separately and are not included in this public Overview.

---

## 12. User Responsibilities

Users also play a role in protecting their information.

You should:

- Avoid submitting information that a Feature does not require.
    
- Never send passwords or authentication codes through the Bot.
    
- Avoid sharing another person's private information.
    
- Use the Bot only for its intended purpose.
    
- Report suspicious Bot behavior.
    
- Report suspected unauthorized access.
    
- Avoid opening suspicious files or links.
    
- Contact the Operator if you believe a private submission has been exposed.
    

Users should not attempt to investigate security incidents by accessing systems or records without authorization.

---

## 13. Security Limitations

The Operator cannot guarantee that the Bot, Discord, a computer, a database, or any connected service will be completely secure or continuously available.

Potential risks include:

- Software defects.
    
- Incorrect permissions.
    
- Human error.
    
- Device compromise.
    
- Credential exposure.
    
- Internet or platform outages.
    
- Unauthorized access.
    
- Storage failures.
    
- Vulnerabilities in third-party software.
    

The Operator will work to reduce these risks through reasonable safeguards and maintenance, but no system can be represented as risk-free.

---

## 14. Changes to This Overview

This Overview may be updated when:

- The Bot moves to a different hosting arrangement.
    
- Storage or backup systems change.
    
- Security controls are implemented or materially changed.
    
- External service providers are introduced.
    
- New Features create additional security considerations.
    
- A security review identifies a need for clarification.
    
- Applicable requirements change.
    

Substantive revisions should be reflected in the document version and revision date.

The published document should describe the actual security posture rather than planned or unverified measures.

---

## 15. Contact Information

Questions or concerns about the security of the Bot may be sent to:

**Next Step Studios**  
**Operator:** Candler Shaw  
**Email:** [nextstepstudiosofficial.contact@gmail.com](mailto:nextstepstudiosofficial.contact@gmail.com)

For security reports, use a clear subject line such as:

**Security Concern - Next Step Studios Discord Bot**

Do not include passwords, authentication codes, API keys, Bot tokens, or other authentication secrets.

---

## 16. Related Policies

This Overview should be read alongside:

1. **Discord Bot Terms of Service**
    
2. **Privacy Policy**
    
3. **Acceptable Use Policy**
    
4. **Community Guidelines**
    
5. **Moderation and Enforcement Policy**
    
6. **Data Retention and Deletion Policy**
    

The Privacy Policy describes the information the Bot may process. The Data Retention and Deletion Policy explains how records should be retained and removed. This Overview describes the general approach to protecting those records.

---

## 17. Draft Status and Publication Checklist

This document is a working draft for review.

Before publication, the Operator should:

- Verify the current hosting arrangement.
    
- Verify which local databases and files contain User information.
    
- Verify encryption-at-rest requirements and implementation.
    
- Verify database and file access permissions.
    
- Review Bot permission requirements.
    
- Review credential and secret handling.
    
- Verify whether backups exist and how they are protected.
    
- Establish backup rotation and deletion procedures.
    
- Review technical logging for unnecessary personal information.
    
- Confirm that private User submissions are not sent to AI services as part of ordinary development assistance.
    
- Identify external service providers, if any.
    
- Establish an incident-response process.
    
- Confirm applicable Discord reporting obligations.
    
- Ensure that the Privacy Policy accurately describes security and storage practices.
    
- Make this Overview accessible to Server members.
    
- Update the version and effective date after approval.
    

**End of document.**
