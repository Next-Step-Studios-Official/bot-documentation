# NEXT STEP STUDIOS

# DISCORD BOT PRIVACY POLICY

**Document version:** 0.2.0  
**Status:** Draft for review. Not yet effective.  
**Prepared:** November 19, 2026  
**Operator:** Candler Shaw, operating under the public-facing name Next Step Studios  
**Contact:** [nextstepstudiosofficial.contact@gmail.com](mailto:nextstepstudiosofficial.contact@gmail.com)  
**Applies to:** The Next Step Studios Discord bot operating in the single private Next Step Studios Discord server

---

## 1. Introduction

Next Step Studios ("Studio," "we," "us," or "our") respects the privacy of individuals who interact with its Discord bot (the "Bot").

This Privacy Policy explains what information the Bot may receive, process, generate, and store; why that information may be used; who may have access to it; how it is intended to be retained; and how you can submit a privacy-related request.

The Bot is operated by **Candler Shaw**, using the public-facing name **Next Step Studios**.

The Bot is intended to operate exclusively in one private Next Step Studios Discord server. It is not currently offered for installation or use in unrelated Discord servers.

### 1.1 Important distinction between current and planned functionality

The Bot is under development and testing. Some Features are operational, some are partially implemented, some require further verification, and others are planned but not yet implemented.

This Privacy Policy distinguishes between:

- Information the Bot is currently understood to process or store.
    
- Information a Feature may process when used.
    
- Information associated with a partially implemented or unverified workflow.
    
- Information that may be processed if a planned Feature is implemented in the future.
    

A description of a planned Feature is not a statement that the Feature currently collects or stores information.

The Operator must verify actual behavior before making a definitive claim about a Feature's production data practices.

### 1.2 Scope

This Policy applies only to information processed in connection with the Next Step Studios Discord Bot and its Bot-operated workflows.

It does not apply to:

- Discord's own account, platform, or data practices.
    
- A Next Step Studios website. No website is currently covered by this Policy.
    
- Other websites, applications, games, or software operated by third parties.
    
- Independent communications or records that are not processed through the Bot.
    
- Services operated by another person or organization.
    

Discord's own Privacy Policy and other applicable Discord notices govern Discord's independent processing of information.

---

## 2. Information We May Process

The information processed depends on the Feature you use, the information you submit, the permissions granted to the Bot, and the Bot's actual implementation.

The categories below describe the current understanding of the Bot's data practices. They should not be interpreted as a claim that every category is collected or stored in every interaction.

### 2.1 Discord account and server identifiers

The Bot uses Discord identifiers to recognize the relevant account, associate interactions with records, and operate within the intended Server.

These identifiers may include:

- **Discord User ID:** A unique identifier associated with a Discord account.
    
- **Discord Server ID:** An identifier for the Server in which the Bot operates.
    
- **Channel identifiers:** Where needed to direct or associate a Bot workflow with a particular channel.
    
- **Role identifiers:** Where needed to determine or manage permissions and role-based workflows.
    
- **Message or interaction identifiers:** Where needed to associate an action with a particular message or interaction.
    

The current known data practices include the use of Discord User IDs and the Server ID.

Other identifiers may be processed as required by individual Features. Their actual use and storage must be confirmed against the deployed code and configuration.

### 2.2 Usernames, display names, and profile information

Discord may make certain account-related information available to the Bot when a User interacts with it.

Depending on the interaction and Discord's API behavior, this may include:

- Discord username.
    
- Server nickname or display name.
    
- User avatar or other profile-related information exposed through the relevant interaction.
    
- Other limited information made available by Discord for the operation of the Feature.
    

The Operator has not fully verified whether usernames and display names are persistently stored in the Bot's database or only processed temporarily during interactions.

Accordingly, this Policy does not promise that these values are never stored, nor does it claim that they are permanently stored in every case. That behavior must be checked and documented before final publication.

### 2.3 Application answers and staff information

The Bot includes application-related functionality.

When you submit an application, the information you provide may include:

- Answers to application questions.
    
- Information relevant to the position or opportunity for which you apply.
    
- Your Discord User ID.
    
- Information associated with the application review process.
    
- Review outcomes, reviewer comments, or administrative information, where implemented.
    
- Information needed to associate an application with a staff record, where applicable.
    

The current understanding is that application answers and staff-related information are stored in a local database during testing.

Access is currently limited to the Operator. If additional authorized reviewers are given access in the future, this Policy and the relevant access controls must reflect that change.

Application information is used for application review, staff administration, and related Server operations. It is not intended to be publicly displayed merely because you submit an application.

### 2.4 Tickets and support requests

The Bot includes a ticket or support workflow.

Information submitted through a ticket may include:

- Messages you send through the ticket.
    
- Your Discord User ID.
    
- Relevant channel or ticket identifiers.
    
- Attachments or other content you choose to submit.
    
- Responses from authorized staff.
    
- Timestamps and workflow status information.
    
- Transcript or administrative information, if generated by the implemented workflow.
    

**Important implementation qualification:** The precise ticket transcript-generation, transmission, and long-term persistence behavior has not been fully verified.

The Operator must inspect the actual ticket implementation to establish:

1. Whether transcripts are automatically generated.
    
2. Whether transcripts are sent to a Discord channel, saved locally, or both.
    
3. Whether ticket messages are stored in a database.
    
4. Whether closed tickets remain accessible.
    
5. Whether attachments are copied or retained separately.
    
6. Which individuals can access ticket records.
    
7. How ticket records and transcripts are deleted.
    

Until those checks are complete, this Policy does not make a definitive promise about the exact storage or deletion behavior of ticket conversations.

Do not submit passwords, authentication codes, payment information, or unnecessary sensitive information through a ticket.

### 2.5 Suggestions and feedback

Where the suggestion Feature is used, the Bot may process:

- The suggestion text.
    
- Your Discord User ID.
    
- Submission identifiers.
    
- Submission status.
    
- Review or administrative information.
    
- Publication information, where applicable.
    

The suggestion system may use temporary JSON files for certain workflow information. Announcement and publication history is intended to use SQLite, but the exact implementation state must be verified.

The Bot's suggestion and announcement workflows must be reviewed separately to establish exactly which information is temporary and which information becomes a persistent record.

### 2.6 Announcements and publication records

The Bot includes announcement-related functionality.

Depending on the workflow, information may include:

- Announcement drafts.
    
- Announcement text.
    
- The identity of the person who prepared or approved an announcement.
    
- Publication status.
    
- Publication timestamps.
    
- The Discord message or channel associated with a published announcement.
    
- Administrative history relating to publication.
    

Some announcement workflow information is understood to use temporary JSON storage. Announcement history is intended to be stored in SQLite.

Temporary drafts should not become permanent records merely because they were created. The intended lifecycle and actual cleanup behavior must be verified before a fixed retention commitment is made.

### 2.7 Moderation and infraction information

Moderation and persistent infraction recordkeeping are planned capabilities.

If implemented, these Features may process information such as:

- The Discord User ID of the affected individual.
    
- The Discord User ID of the staff member responsible for an action.
    
- The type of action.
    
- The reason recorded for the action.
    
- Relevant evidence or supporting information.
    
- Dates and timestamps.
    
- Expiration or review information.
    
- Related moderation history.
    

The Bot's persistent moderation and infraction recordkeeping is not currently confirmed as operational.

This section describes potential future processing, not a claim that the Bot currently maintains a complete moderation database.

### 2.8 Ban appeals

A dedicated ban appeal workflow is planned and is not currently confirmed as operational.

If implemented, an appeal may contain:

- The appellant's Discord User ID.
    
- The moderation action being appealed.
    
- The explanation provided by the appellant.
    
- Supporting information or attachments.
    
- Review notes and decisions.
    
- Relevant timestamps and administrative status.
    

The exact appeal workflow, storage arrangement, access permissions, and retention schedule must be established before the Feature is enabled and before this section is treated as a description of active processing.

### 2.9 Technical and diagnostic information

The Bot may generate technical information necessary to operate, troubleshoot, and maintain its software.

This may include:

- Error messages.
    
- Exception details.
    
- Timestamps.
    
- Feature or command names.
    
- Workflow status.
    
- Information about failed operations.
    
- Limited diagnostic context.
    

Technical logs should not contain passwords, bot tokens, authentication secrets, or unnecessary copies of User Content.

The exact logging configuration and retention behavior must be reviewed. This Policy does not claim that a particular logging system or retention period is already in place.

### 2.10 Information you choose not to provide

Some Features may require particular information to function.

If you choose not to provide information required by a Feature, the Bot may be unable to accept or process your submission.

You should provide only information reasonably necessary for the Feature you are using. Do not include unrelated personal details merely because a form or text field permits additional content.

---

## 3. How We Use Information

Information processed by the Bot is used for legitimate Bot and Server operational purposes, including the following.

### 3.1 Operating the Bot

Information may be used to:

- Identify the Discord account interacting with the Bot.
    
- Associate an interaction with the correct User or Server.
    
- Determine whether a User or staff member has permission to use a Feature.
    
- Route submissions to the appropriate workflow.
    
- Maintain the Bot's configuration and operational state.
    
- Prevent duplicate or invalid operations where supported.
    

### 3.2 Application administration

Application information may be used to:

- Receive and organize applications.
    
- Allow authorized reviewers to evaluate submissions.
    
- Communicate application outcomes.
    
- Maintain staff-related information where appropriate.
    
- Support the administration of staff positions and responsibilities.
    

### 3.3 Support and ticket handling

Ticket information may be used to:

- Receive support requests.
    
- Allow authorized individuals to respond.
    
- Track the status of an issue.
    
- Preserve relevant information while a request is being handled.
    
- Maintain a record where the implemented workflow requires one.
    

### 3.4 Suggestions and announcements

Suggestion and announcement information may be used to:

- Receive community feedback.
    
- Review suggestions.
    
- Track decisions or statuses.
    
- Prepare and publish announcements.
    
- Maintain relevant publication history.
    
- Prevent accidental duplication or loss of workflow information.
    

### 3.5 Moderation and Server administration

If and when the relevant Features are implemented, information may be used to:

- Review reported conduct.
    
- Record moderation decisions.
    
- Associate actions with the relevant accounts.
    
- Maintain relevant administrative history.
    
- Review eligible appeals.
    
- Protect the Server and its Users.
    

### 3.6 Security, troubleshooting, and reliability

Technical and operational information may be used to:

- Diagnose errors.
    
- Investigate failed operations.
    
- Maintain the Bot.
    
- Identify misuse or attempted interference.
    
- Protect records and systems.
    
- Improve the reliability of implemented Features.
    

### 3.7 Legal and compliance purposes

Information may be retained or processed where reasonably necessary to:

- Respond to a valid legal request.
    
- Comply with applicable law.
    
- Protect legal rights.
    
- Investigate suspected abuse or security incidents.
    
- Preserve information where a lawful obligation requires it.
    

Any such retention must be limited to the applicable purpose and legal requirement.

---

## 4. How Information Is Stored

### 4.1 Current testing arrangement

The Bot is currently being tested on the Operator's own computer.

The current understanding is:

- Application answers and staff-related information are stored in a local database.
    
- Some temporary workflow information is stored in JSON files.
    
- Announcement history is intended to be stored in SQLite.
    
- The precise ticket transcript and persistence behavior has not been fully verified.
    
- Persistent moderation and ban appeal recordkeeping are planned rather than confirmed operational Features.
    

The production hosting arrangement may change in the future. Any material change to storage, hosting, access, or external processing must be reviewed and reflected in this Policy before the change is treated as an established data practice.

### 4.2 Local storage does not mean risk-free storage

A local database or local file is not automatically secure merely because it is stored on a computer controlled by the Operator.

Security depends on the actual device configuration, operating system, account permissions, storage protection, backups, physical access, and other safeguards.

The Operator must verify which safeguards are implemented rather than relying on assumptions.

### 4.3 Database and file formats

The Bot may use structured databases and temporary files to support its Features.

The current development arrangement includes SQLite and JSON-based storage for certain workflows.

These formats describe how information may be organized. They do not, by themselves, establish whether information is encrypted, backed up, automatically deleted, or accessible only to a particular person.

### 4.4 Encryption

The encryption-at-rest status of the Bot's local database and related stored files has not been confirmed for purposes of this draft.

This Policy therefore does not claim that every database, JSON file, transcript, backup, or other stored record is encrypted at rest.

Before production use, the Operator must verify the applicable storage-protection requirements and implement the necessary safeguards.

Information transmitted through Discord is also subject to Discord's own platform and infrastructure practices. The Operator does not independently control Discord's transport security or internal storage.

---

## 5. Who Can Access Information

### 5.1 Operator access

The current access arrangement is that the Operator, Candler Shaw, is authorized to review stored User information for relevant Bot administration, application review, troubleshooting, and other legitimate operational purposes.

The Bot is intended to restrict access to records according to the permissions and administrative roles required by each Feature.

### 5.2 Authorized reviewers and staff

Some information may need to be shown to an authorized reviewer or staff member to perform a specific Server responsibility.

For example:

- Application information may be shown to individuals responsible for application review.
    
- Ticket information may be shown to individuals responsible for handling the ticket.
    
- Moderation information may be shown to individuals authorized to review or administer moderation matters, if that Feature is implemented.
    

The current confirmed access arrangement is limited to the Operator. Any expansion of access must be deliberate, limited to legitimate responsibilities, and reflected in the Bot's permissions and documentation.

Being a Server member or staff member does not automatically entitle someone to access every stored record.

### 5.3 Discord

The Bot operates through Discord. Discord may independently process information under its own Privacy Policy, Terms of Service, and other applicable policies.

The Operator does not control Discord's independent processing.

### 5.4 External service providers

The current development and testing arrangement does not establish a complete, verified inventory of external service providers that may process Bot Data.

If the Bot is later moved to a hosting provider, database provider, logging service, backup service, or another external service, the Operator must assess what information that provider receives and update this Policy where required.

The Operator should not provide identifiable User submissions or private User records to an external provider unless there is a legitimate, documented reason and appropriate safeguards.

### 5.5 AI tools and development assistance

The Operator may use AI-assisted development tools to help write, review, troubleshoot, or improve the Bot's code and documentation.

Using an AI tool for software development does **not** automatically authorize sending identifiable User information, application answers, private ticket conversations, appeal materials, or other private submissions to that tool.

The Operator should use synthetic examples, redacted excerpts, or non-identifying technical information when requesting AI assistance.

Private User records must not be supplied to an AI service merely because the Operator uses that service to assist with development.

This Policy does not claim that an AI provider has access to the Bot's database or User submissions. Any future integration that actually sends Bot Data to an AI service must be separately assessed, documented, and disclosed before it is enabled.

### 5.6 No public disclosure by default

Private application answers, ticket conversations, and other non-public submissions are not intended to be made publicly available merely because they were submitted through the Bot.

Information may be displayed in a Server channel when a Feature is specifically designed to publish it, such as an approved announcement or public suggestion. The intended audience and publication behavior should be clear from the Feature.

---

## 6. Sale, Advertising, and Unrelated Use

The Operator does not intend to sell Bot Data or use private User submissions for unrelated advertising.

The Bot's information is intended to support its operation and the administration of the private Server.

The Operator does not authorize the use of private application answers, ticket conversations, appeal submissions, or other private User Content for unrelated marketing or advertising.

The Operator also does not authorize the use of private User Content to train an AI or machine-learning model merely because AI tools may be used to assist with software development.

This does not prevent the Operator from using non-identifying technical examples or synthetic data for development and troubleshooting.

---

## 7. Data Retention

### 7.1 General rule

Information should be retained only for as long as reasonably necessary for the purpose for which it was collected, subject to applicable legal obligations and legitimate operational requirements.

The Operator should not retain information indefinitely merely because storage is available or because preserving a complete history is convenient.

Retention should take account of:

- The type of information.
    
- The purpose for which it was collected.
    
- Whether the relevant Feature remains active.
    
- Whether the record is still needed for administration or review.
    
- The sensitivity of the information.
    
- Security risks associated with continued retention.
    
- Applicable legal obligations.
    

### 7.2 No fixed retention periods are currently promised

Specific retention periods have not yet been finalized for every category of Bot Data.

This Policy therefore does not promise that applications, tickets, transcripts, suggestions, logs, backups, or other records will be deleted after a particular number of days or months.

A documented retention schedule must be established and implemented before the Operator makes fixed deletion-time commitments.

### 7.3 Temporary information

Temporary drafts and workflow files should not become permanent records accidentally.

For example, announcement drafts and other temporary JSON-based workflow data should be removed when no longer needed, subject to any legitimate recovery or operational requirement.

The actual cleanup behavior must be verified against the deployed implementation.

### 7.4 Backups

The backup process and backup-retention schedule have not been fully confirmed.

If backups are implemented, the Operator must document:

- What information is backed up.
    
- Where backups are stored.
    
- Who can access them.
    
- How backups are protected.
    
- How long backups are retained.
    
- How deletion requests are handled in relation to backup copies.
    

Deleting a record from the live database may not immediately remove an older copy contained in a backup. A reliable backup-expiration or deletion process must be established and accurately described.

### 7.5 Further details

The Data Retention and Deletion Policy provides the detailed retention framework and identifies the implementation decisions that remain outstanding.

---

## 8. Data Sharing and Disclosure

The Operator does not intend to disclose Bot Data indiscriminately.

Information may be disclosed or made available only where reasonably necessary for the Bot's operation, the relevant Server workflow, or another legitimate and lawful purpose.

Potential circumstances include:

### 8.1 Authorized Server administration

Relevant information may be made available to the Operator or an authorized reviewer who needs it to perform a legitimate administrative responsibility.

### 8.2 Discord platform operation

Information is processed through Discord as part of the Bot's operation. Discord's own data practices apply to information Discord independently processes.

### 8.3 Service providers

If an external provider is used to host, store, back up, monitor, or maintain the Bot, the provider may process information necessary to provide that service.

The Operator must identify the provider, determine what information it receives, and update this Policy where appropriate before relying on that arrangement in production.

### 8.4 Legal obligations and protection

Information may be disclosed where the Operator reasonably believes disclosure is required by applicable law or a valid legal process, or is necessary to protect the rights, safety, or security of the Operator, the Server, or another individual.

Where legally permitted and reasonably practicable, disclosure should be limited to the information necessary for the relevant purpose.

### 8.5 No unrelated sale or disclosure

The Operator does not intend to sell Bot Data, rent private User submissions, or disclose private User Content for unrelated advertising.

---

## 9. Your Privacy Rights and Requests

You may contact the Operator with questions or requests concerning information associated with your use of the Bot.

Depending on applicable law and the circumstances, you may request:

- Information about whether the Bot holds records associated with you.
    
- Access to relevant information.
    
- Correction of inaccurate information.
    
- Deletion of information.
    
- Clarification about how a particular Feature processes information.
    
- Review of a concern about the handling of your information.
    

Not every request can necessarily be granted in full. For example, certain information may need to be retained where required by law, necessary for a legitimate and documented operational purpose, or needed to protect another person's rights.

The Operator will assess each request individually and explain any material limitation where appropriate.

### 9.1 How to submit a privacy request

Send your request to:

[**nextstepstudiosofficial.contact@gmail.com**](mailto:nextstepstudiosofficial.contact@gmail.com)

Use a subject line such as:

**Privacy Request - Next Step Studios Discord Bot**

In your message, include:

1. Your Discord User ID, if you can safely obtain it.
    
2. The Bot Feature involved, if known. For example, an application, ticket, suggestion, or another workflow.
    
3. A clear description of what you are requesting.
    
4. Any relevant date, approximate timeframe, or reference that may help identify the record.
    

You do not need to send your password, authentication code, recovery code, or other account credentials.

Do not send unrelated sensitive information.

### 9.2 Why your Discord User ID may be requested

A Discord User ID is a stable account identifier that can help distinguish your account from other accounts with similar usernames or display names.

Usernames and display names can change. A User ID is generally a more reliable way to identify the relevant account when locating Bot records.

Only provide your User ID through the privacy-request email address above. Do not post it publicly unless there is a clear reason to do so.

### 9.3 How to enable Developer Mode

If you do not know how to find your Discord User ID, Discord provides an official guide explaining how to enable Developer Mode.

**Official Discord guide: Enable Developer Mode**

[Discord: Where can I find my User/Server/Message ID?](https://support.discord.com/hc/en-us/articles/206346498-Where-can-I-find-my-User-Server-Message-ID)

If Developer Mode is already enabled on your Discord account, you can skip this step.

**On desktop:**

1. Open Discord.
    
2. Open User Settings using the gear icon.
    
3. Select **Advanced**.
    
4. Find **Developer Mode**.
    
5. Turn Developer Mode on.
    

**On mobile:**

1. Open Discord.
    
2. Tap your avatar.
    
3. Open User Settings using the gear icon.
    
4. Find **Advanced** under App Settings.
    
5. Turn Developer Mode on.
    

Discord may change the layout or wording of its settings. Follow the current instructions displayed in Discord's official guide if the menu looks different.

### 9.4 How to copy your Discord User ID

After Developer Mode is enabled, use Discord's official instructions to copy your User ID.

**Official Discord guide: Find and copy a User ID**

[Discord: Where can I find my User/Server/Message ID?](https://support.discord.com/hc/en-us/articles/206346498-Where-can-I-find-my-User-Server-Message-ID)

**On desktop:**

1. Find your account in the Server, a direct message, or another Discord location where your profile is visible.
    
2. Right-click your username or avatar.
    
3. Select **Copy User ID**.
    
4. Paste the copied ID into your privacy-request email.
    

**On mobile:**

1. Find your account in Discord.
    
2. Tap your profile or avatar.
    
3. Open the three-dot menu in the profile.
    
4. Select **Copy User ID**.
    
5. Paste the copied ID into your privacy-request email.
    

If the menu options differ, use the official Discord guide linked above.

### 9.5 What happens after you submit a request

A privacy request may require the Operator to:

1. Review the request.
    
2. Determine what information is needed to identify the relevant records.
    
3. Verify that the request is associated with the relevant Discord account.
    
4. Search the applicable database, files, or workflow records.
    
5. Determine whether the requested action can be completed.
    
6. Identify any applicable legal or operational reason that may limit deletion or modification.
    
7. Respond using the contact method provided.
    

The time required may depend on the complexity of the request and the state of the Bot's records.

This email process is the documented method for submitting a privacy request. It should not be interpreted as an automated deletion command or an assurance that a request is completed immediately upon receipt.

### 9.6 Verification and protection against unauthorized requests

The Operator may request reasonable additional information to verify that a privacy request concerns the correct account.

The Operator should not request passwords, authentication codes, recovery codes, or account tokens to verify a request.

A request may be delayed or declined if the Operator cannot reasonably establish which records are involved or whether the requester is authorized to make the request.

---

## 10. Security and Data Protection

The Operator takes the protection of Bot Data seriously and intends to use safeguards appropriate to the nature of the information and the Bot's operational environment.

However, the exact security configuration is still subject to implementation and verification.

### 10.1 Access restrictions

Access to stored information should be limited to the Operator and any specifically authorized individual who requires access for a legitimate responsibility.

Administrative access should not be granted merely because someone is a Server member or holds a general staff role.

### 10.2 Credentials and secrets

Bot tokens, passwords, API keys, and other authentication secrets must be protected and must not be included in public policy documents, logs, support messages, or ordinary User-facing records.

### 10.3 Storage protection

The Operator must verify the security of the local computer, database files, temporary files, and any backups.

The use of a local database does not automatically establish that the data is encrypted or protected against unauthorized access.

### 10.4 Security incidents

If the Operator becomes aware of a suspected or confirmed incident involving unauthorized access, disclosure, alteration, or loss of Bot Data, the Operator should investigate and take reasonable steps to contain and address it.

Where applicable law or Discord's requirements impose notification or reporting obligations, those obligations must be followed.

### 10.5 No guarantee of absolute security

No software system, storage device, network, or online service can be guaranteed to be completely secure.

The Operator will work to protect Bot Data, but cannot promise that unauthorized access, software defects, platform failures, or other security incidents will never occur.

The Security and Data Protection Overview provides additional public-facing information about the intended safeguards.

---

## 11. International Processing

The Bot is operated through Discord, a platform that may process information using infrastructure located in different jurisdictions.

The Operator's current testing arrangement uses local storage on the Operator's own computer. The exact locations and arrangements of any future hosting, backup, or external service providers have not been finalized in this draft.

If the Bot moves to external hosting or begins using additional providers, the Operator must assess the relevant processing locations and update this Policy where necessary.

Applicable privacy laws may provide different rights depending on where a User lives.

---

## 12. Children's Privacy

The Bot is intended for use by members of the private Server who are eligible to use Discord and the relevant Server Features under applicable rules.

The Operator does not intend to use the Bot to knowingly collect information from children in violation of applicable law or Discord's requirements.

Users should not submit unnecessary sensitive information about themselves or other individuals, including children.

If a parent, guardian, or other authorized individual believes that information has been submitted in a way that raises a privacy concern, they may contact the Operator at the email address listed in this Policy.

The Operator will review the concern and determine what action is appropriate under applicable law and the circumstances.

---

## 13. Changes to This Privacy Policy

This Policy may be updated when:

- The Bot gains or loses a Feature.
    
- A Feature begins collecting or storing a new category of information.
    
- The storage or hosting arrangement changes.
    
- New external service providers are introduced.
    
- Retention periods or deletion procedures are established or changed.
    
- Security controls are implemented or materially changed.
    
- Applicable legal requirements change.
    
- A correction or clarification is necessary.
    

A substantive update should include a new document version and revision date.

Where a change materially affects Users or the handling of their information, the Operator should provide reasonable notice through an appropriate Server channel or Bot interaction where practicable.

The current version should be made available through an accessible Bot command, public policy document, or other clearly identified method.

---

## 14. Contact Information

For privacy questions, data requests, or concerns about the Bot's handling of information, contact:

**Next Step Studios**  
**Operator:** Candler Shaw  
**Email:** [nextstepstudiosofficial.contact@gmail.com](mailto:nextstepstudiosofficial.contact@gmail.com)

Please include enough information to identify the relevant Feature or record, but do not send passwords, authentication codes, or unnecessary sensitive information.

---

## 15. Related Policies

This Privacy Policy should be read alongside:

1. **Discord Bot Terms of Service**  
    Explains the terms governing use of the Bot.
    
2. **Acceptable Use Policy**  
    Explains permitted and prohibited use of the Bot and its Features.
    
3. **Community Guidelines**  
    Explains expected conduct within the Server.
    
4. **Moderation and Enforcement Policy**  
    Explains how potential violations may be reviewed and addressed.
    
5. **Data Retention and Deletion Policy**  
    Provides the detailed framework for retaining and deleting Bot records.
    
6. **Security and Data Protection Overview**  
    Provides public-facing information about the Operator's security approach.
    

---

## 16. Draft Status and Required Verification

This document is a working draft. It must not be presented as a final, legally reviewed Privacy Policy until the Operator has verified the actual implementation and approved the document.

Before publication, the Operator must complete the following checks:

### Data inventory

- Confirm every Discord identifier accessed by the Bot.
    
- Confirm whether usernames and display names are persistently stored.
    
- Identify every database and file used to store User information.
    
- Confirm what application information is stored and where.
    
- Confirm what staff information is stored and where.
    
- Inspect the ticket workflow and determine whether transcripts are generated.
    
- Determine whether ticket transcripts are sent to Discord channels, saved locally, or both.
    
- Determine whether ticket messages and attachments are stored separately.
    
- Confirm the actual storage and cleanup behavior of suggestion records.
    
- Confirm the actual storage and cleanup behavior of announcement drafts.
    
- Confirm whether announcement history is stored in SQLite.
    
- Identify any technical logs that may contain User information.
    
- Identify any backups and determine what they contain.
    

### Access and security

- Confirm which individuals can access each category of stored information.
    
- Confirm that permissions are limited to legitimate responsibilities.
    
- Verify how database files and temporary files are protected.
    
- Verify encryption-at-rest requirements and implementation.
    
- Review credential and secret handling.
    
- Identify any external hosting, storage, backup, or monitoring providers.
    
- Confirm whether any User Data is sent to external services.
    
- Confirm that private User submissions are not being sent to AI services as part of ordinary development assistance.
    

### Retention and deletion

- Establish a retention schedule for applications.
    
- Establish a retention schedule for staff records.
    
- Establish a retention schedule for tickets and transcripts.
    
- Establish a retention schedule for suggestions.
    
- Establish a retention schedule for announcement drafts and history.
    
- Establish a retention schedule for technical logs.
    
- Establish a retention schedule for backups.
    
- Define how deletion requests are handled across live databases, files, and backups.
    
- Verify that the documented deletion process can actually be carried out.
    

### User-facing process

- Confirm that the privacy-request email address is monitored.
    
- Establish a process for verifying privacy requests.
    
- Establish a process for searching and responding to requests.
    
- Make this Policy accessible to Server members.
    
- Provide an accessible way to request modification or deletion of personal information.
    
- Confirm that any Bot command described as a privacy-request feature actually exists before advertising it as functional.
    

**End of document.**