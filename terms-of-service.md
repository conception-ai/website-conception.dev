---
layout: default
title: Terms of Service - Point&Click
---

# Point&Click Terms of Service

*Version Effective Date: October 23, 2025*

## Preamble

These Terms of Service govern Your use of Point&Click services provided by Conception AI Inc., a Delaware corporation registered with principal place of business at 2261 Market Street STE 85701, San Francisco, CA 94114, United States, operating at [pointandclick.ai](http://pointandclick.ai/).

By accessing or using Point&Click, You accept these Terms of Service applicable to You. You must read these Terms of Service carefully before using Point&Click. We recommend You download these Terms of Service and keep a copy.

## Definitions

The capitalized words in this document shall have the meaning set forth below:

**Account:** means the personalized user account required to access and use Point&Click.

**Actions:** means, to the exclusion of Input and Output, any and all content, decisions, browsing, recommendations, interactions, operations, actions and transactions executed by the Automation Flows in Your browser and in Your name, including screenshots and screen recordings of Your browser during execution, content of websites visited as part of the Flow execution, and all actions performed on third-party websites that appear to those websites as if You personally performed them, in response to an Input. All Actions are legally and practically attributed to You as the account holder.

**Point&Click Service or Services:** means the browser extension and automation platform that automates web actions where no API exists, enabling automation for business workflows requiring UI interactions rather than API calls, provided by Conception AI Inc. at [pointandclick.ai](http://pointandclick.ai/).

**Building Block:** means a deterministic, pre-written automation script for a specific action that executes with high reliability and speed, created from successful agent executions and made available to the community for reuse.

**Automation Flow or Flow:** means an automated workflow composed of one or more Building Blocks or real-time agent actions to perform tasks on websites, including but not limited to downloading invoices and receipts, data scraping, form filling, website navigation, and system synchronization.

**Creator:** means a tech-savvy User who creates and optionally shares Automation Flows on the Platform for use by other Users, and may earn royalties for shared Flows when such feature is available.

**User or Prosumer:** means a person who executes Automation Flows on the Platform for personal or business purposes.

**Flow Data:** means data generated, used, or processed by or in connection with the Automation Flows, including Inputs, Actions, and Outputs.

**Input:** means any data, file, document or content You put into the Automation Flows, including natural language prompts, configuration parameters, text commands, website credentials, target URLs, or other instructions and queries.

**Output:** means the results, responses, or deliverables produced by the Automation Flows, including but not limited to downloaded files such as invoices or receipts, extracted data, execution reports, textual, and visual outputs.

**Force Majeure Events:** means events beyond the reasonable control of a Party that prevent or delay the fulfillment of contractual obligations, including but not limited to natural disasters, government actions, strikes, pandemics, or technological failures.

**Point&Click, We, Our, Us:** means the provider of the Services, operating as Point&Click at [pointandclick.ai](http://pointandclick.ai/), a product of Conception AI Inc., as described in the preamble of this Agreement.

**You, Your:** means the person, whether a natural or legal person, accessing and using the Services provided by Point&Click under this Agreement.

**Terms of Service, ToS, Agreement:** means the present terms of service, and any agreement of any nature applicable to Your use of the Services included by cross reference therein.

## Purpose and Scope

### Purpose

The purpose of the Agreement is to describe the rights and responsibilities of the Parties in connection with the provision and use of Point&Click Services.

### Contractual Documents

These Terms of Service apply to any subscription, access to or use of the Services by You. Where Point&Click processes personal data on Your behalf as Data Processor, You may contact us at [contact@conception.dev](mailto:contact@conception.dev) to enter into a Data Processing Agreement with Us. Otherwise, for any processing of personal data that We carry out as Data Controller, please refer to our Privacy Policy available at [pointandclick.ai/privacy](http://pointandclick.ai/privacy). In case of any conflicts or discrepancies between these Terms of Service and any document included by cross-reference therein, the latter shall prevail.

## Our Services

### Description of Point&Click

Point&Click is a browser extension designed to automate web actions where no API exists. Unlike general-purpose automation tools such as Zapier or N8N that rely on API integrations, Point&Click is specifically built to handle automation requiring UI interactions directly within Your browser. The platform operates on a hybrid model combining deterministic Building Blocks with real-time agent execution to provide reliable, cost-efficient automation.

The workflow operates as follows: Users prompt the platform in natural language to request a task, for example "Download all my Uber invoices from last month." Point&Click converts this request into an automation plan composed of Building Blocks. If a Building Block for the requested action already exists in our library, the platform executes it instantly with high reliability, speed, and cost-efficiency. If no Building Block exists for the requested action, our agent attempts the task in real-time using AI. When the agent successfully completes a new task, we convert it into a reusable Building Block that becomes available to the entire community.

Building Blocks represent our core differentiation in the market. Rather than promising generalist autonomous agents with uncertain success rates, we focus on creating and maintaining a library of deterministic, pre-written scripts that execute specific actions reliably. This approach enables us to deploy automation that is significantly more cost-efficient and faster than our competitors, as we do not need to rebuild an end-to-end agent flow every time an automation is reused. We are transparent with our users about what works reliably today through established Building Blocks versus what is still being tested through new agent-executed tasks.

All execution happens directly in Your browser, which provides several critical advantages. We never store Your website credentials on our servers. The automation naturally bypasses anti-bot systems since traffic originates from Your real browser session. You maintain full control over what the automation can access at all times.

We are currently focused on invoice retrieval as our initial use case, representing a simple and universal pain point that classic automation platforms do not address out of the box. The Services include a Chrome extension for browser-based automation, natural language task prompting, a community Building Block library that grows over time, automated downloading of documents including invoices and receipts, data extraction and web scraping capabilities, system synchronization without API access, and form filling and website navigation functionality.

### Early Stage Warnings and Limitations

Point&Click is in early development and currently has a LIMITED number of established Building Blocks in our library. This fundamental fact has critical implications for how You must use the Services during this beta period.

Because our Building Block library is still growing, most tasks You request will be executed by our agent in real-time for the first time, without pre-written scripts. Agent-executed tasks have uncertain success rates and may fail, execute incorrectly, or produce unexpected results. Once our agent successfully completes a task, it becomes converted into a Building Block with significantly higher reliability for all future uses. However, until that conversion occurs, You are essentially allowing our agent to attempt a novel automation task without the safety and reliability guarantees of established Building Blocks.

You must actively supervise the agent during execution, especially during the first time You run any task, any task that has not yet been converted to a Building Block, any task involving sensitive data or high-value accounts, and any task with financial, legal, or regulatory implications. Do not run automations in the background unattended during this beta period. We strongly recommend starting with non-critical, low-risk tasks to understand how the platform works before progressing to more sensitive use cases.

### Browser Access and Single Sign-On (SSO) Risks

When You grant Point&Click access to Your browser and authorize it to perform actions on a website, You are providing access that extends far beyond that single website. Because Point&Click operates with full control over Your browser session, including control over the Single Sign-On function, the platform may automatically gain access to all services and accounts connected via SSO to the primary account You have authorized.

### Critical Understanding of Browser Control

By installing and using Point&Click, You grant Us the ability to execute automations in Your browser at any time while the extension is active, not only when You explicitly initiate a Flow. This means that We may initiate Flow executions, test Building Blocks, perform diagnostics, or conduct platform testing using Your browser session without requiring Your explicit approval for each individual execution, particularly during the beta period.

When an automation is running in Your browser, Point&Click acts in Your name and on Your behalf. All actions performed by Flows appear to third-party websites as if You personally performed them. Websites cannot distinguish between actions You take manually and actions Point&Click takes automatically. This means that any Flow execution is legally and practically attributed to You as the account holder, regardless of whether You initiated the specific action or whether it was executed automatically by Our platform.

During Flow execution, Point&Click records Your screen, capturing all visual content displayed in Your browser, including but not limited to website content You access, personal information visible on screen, data from all browser tabs and windows, notifications and pop-ups that appear, and any other visual elements present during execution. These screen recordings are stored by Us and may be reviewed by Our team for debugging, Building Block creation, quality assurance, security monitoring, and platform improvement purposes, particularly during the beta period.

You acknowledge and consent that screen recordings may capture sensitive information that happens to be visible in Your browser during Flow execution, including personal messages or emails, financial information or account balances, private documents or files, confidential business information, or any other data visible on screen. We recommend closing or minimizing sensitive content before running automations, or using dedicated browser profiles for Point&Click.

This is a critical security consideration that You must understand before using Point&Click. For example, if You ask Point&Click to download invoices from Gmail and You are logged into Your Google account, the agent may automatically gain access through SSO to Google Drive, Google Calendar, Google Analytics, YouTube, Google Cloud Platform, and any other Google services linked to that account. The agent does not need to request separate authorization for these connected services because Your browser session already contains the necessary authentication tokens and cookies that enable SSO.

This SSO behavior means that the agent could unintentionally access more services than You explicitly intended to authorize. Actions could be performed across multiple connected platforms without Your explicit awareness. Data from connected services could be accessed, read, modified, or deleted as part of Flow execution. You may not realize which services are being accessed or affected until after execution has completed or failed.

The same SSO risk applies to any identity provider or account system that uses Single Sign-On. If You authorize Point&Click on a Microsoft account, it may access Office 365, Azure, Teams, and all Microsoft services. If You authorize it on an Okta-authenticated service, it may access all services connected through Okta. If You use social login through Facebook or LinkedIn, Point&Click may access any service where You have used that social login.

To mitigate these SSO risks, You should consider using dedicated browser profiles specifically for Point&Click, using incognito or private browsing mode when running automations, logging out of unnecessary services before running automations, carefully reviewing which services are connected via SSO to any account You plan to automate, actively monitoring the agent's actions during execution in real-time, starting with low-risk, isolated accounts before automating critical services, and considering the full ecosystem of connected services rather than just the primary target of Your automation request.

We strongly recommend that during this early beta period, You always watch the agent execute tasks in real-time, do not run automations in the background unattended, start with non-critical and low-risk tasks to understand platform behavior, test new tasks on sandbox or test accounts before using production accounts, and immediately stop execution if the agent accesses unexpected services or data.

As our Building Block library grows and more tasks become deterministic rather than agent-executed, the reliability and predictability of the platform will increase significantly. We will update this section as the platform matures and as we implement additional safeguards to manage SSO access more granularly.

### Business Purpose

The Services are designed for both professional and personal use. Users may automate tasks for business purposes such as expense management, invoice collection, and data gathering, or for personal purposes such as receipt organization and price monitoring.

### Creating an Account

To access Point&Click, You must create an Account on Our website at [pointandclick.ai](http://pointandclick.ai/) or through the Chrome extension. To do so, You must provide accurate and complete information to register to use Our Services. If You create an Account or use the Services on behalf of another person or entity, You must have the authority to accept this Agreement on their behalf. To create Your Account, You must be at least 18 years old or the minimum age required in Your country to be considered as an adult person.

You are responsible for maintaining the confidentiality of Your Account credentials, including Your password, and for all activities that occur under Your Account, whether authorized by You or not. You must notify Us immediately at [contact@conception.dev](mailto:contact@conception.dev) of any unauthorized access to Your Account or any other security breach. We are not liable for any loss or damage arising from Your failure to maintain Account security. We reserve the right to suspend or terminate Your Account immediately if We detect suspicious or unauthorized activity, if Your Account is used in violation of these Terms, if Your Account poses a security risk to Us or other users or third parties, or if You fail to maintain adequate Account security measures.

### Account Security Responsibilities

You are solely responsible for the security of Your Account and must take all reasonable measures to protect it. You must create a strong and unique password for Your Account and never share Your password with others or use the same password across multiple services. You should use a password manager if You are storing multiple credentials within Point&Click. You must change Your password immediately if You suspect it has been compromised.

You must restrict access to Your Account to authorized personnel only if using Point&Click for business purposes. You must log out of Your Account when using shared or public computers. You should enable two-factor authentication when such functionality becomes available in Point&Click. You must monitor Your Account activity regularly for any suspicious behavior or unauthorized Flow executions.

Regarding credential storage within Point&Click, You must understand that while website credentials stored in the Services are encrypted, no system is completely risk-free. You should only store credentials for websites where You have explicit authorization to automate access. You must regularly review and remove stored credentials You no longer need. You should carefully consider the risks before storing credentials for high-value or sensitive accounts such as banking, primary email, or administrative accounts.

You must notify Us immediately at [contact@conception.dev](mailto:contact@conception.dev) if You detect any unauthorized access to Your Account, if Your password or any stored credentials have been compromised, if You notice suspicious Flow executions that You did not authorize, or if You receive security alerts or warnings related to Your Account.

### Subscriptions and Payment

Access to certain features of the Services may require a paid subscription. Current pricing information is available at [pointandclick.ai/pricing](http://pointandclick.ai/pricing). By subscribing to Our Services, You agree to pay the applicable fees for Your selected plan. All fees are exclusive of taxes unless stated otherwise. Payments are processed through third-party payment processors, and You are responsible for providing accurate payment information.

Subscriptions automatically renew at the end of each billing cycle unless cancelled before the renewal date. You may cancel Your subscription at any time through Your Account settings or by contacting [contact@conception.dev](mailto:contact@conception.dev). Cancellation will take effect at the end of Your current billing period. We reserve the right to change Our pricing upon reasonable notice of at least thirty days. Price changes will not apply retrospectively and will only apply to subscription renewals and new subscriptions after the notice period.

### Beta Period and Free Access

The Services are currently in beta testing phase. During this beta period, access to the Services is provided free of charge regardless of features used. We reserve the right to transition from beta to general availability at any time with at least thirty days notice to users, to introduce paid subscription requirements after the beta period ends, to modify features, functionality, or service levels during beta testing, and to suspend or discontinue the Services during beta testing if necessary.

Users will be notified at least thirty days before any transition from free beta access to paid subscriptions. You will have the opportunity to subscribe or discontinue use before charges apply. During the beta period, the Services are provided "AS IS" without any guarantees of uptime, data retention, feature stability, or continued availability.

By using the Services during beta, You acknowledge and accept that the Services may be unstable, incomplete, or subject to significant changes without notice, that Your data including Flow configurations, execution history, and stored credentials may be lost or corrupted without warning or ability to recover, that features may be added, modified, or removed without advance notice, that We may reset, modify, or delete user accounts and data during testing as necessary for platform development, and that no service level agreements or uptime guarantees apply during the beta period.

### Beta Monitoring and Data Access

During the beta period, We reserve the right to monitor, access, review, and analyze all Flow executions, Inputs, Actions, Outputs, and any other data generated through Your use of the Services in unencrypted, plain-text form. This comprehensive monitoring is necessary for debugging, platform development, quality assurance, Building Block creation, security monitoring, and service improvement.

By using the Services during beta, You expressly acknowledge and consent that We may access and review all content processed through Point&Click, including but not limited to the natural language prompts You provide, the websites You automate, the data You extract or download, the credentials You store (which remain encrypted at rest but may be accessed in decrypted form during execution monitoring), screenshots and screen recordings of Flow executions capturing all visual content in Your browser including personal information, private messages, financial data, or any other information visible on screen during execution, all data transmitted to or from third-party websites, error logs and debugging information, and any other information generated or processed during Your use of the Services.

This monitoring may be performed by Our engineers, developers, quality assurance personnel, and authorized contractors for purposes of identifying and fixing bugs or errors, improving Flow reliability and success rates, creating and optimizing Building Blocks from successful agent executions, detecting and preventing security threats or abuse, understanding user behavior and improving platform usability, training and improving Our AI models and agents, and complying with legal obligations or responding to security incidents.

You acknowledge that this level of access is significantly broader than will be maintained after the beta period ends, and that upon transition to general availability, We will implement stricter data access controls and limitations. If You are not comfortable with this level of monitoring and data access, You should not use the Services during the beta period.

We strongly recommend that You do not rely on the beta Services for critical business operations or workflows where failures would cause significant harm or disruption. You should maintain backups of any important data, Flow configurations, or credentials outside of Point&Click during the beta period. You should not use the Services to process highly sensitive, confidential, or regulated data during the beta period, including but not limited to protected health information, financial account numbers, social security numbers, or other regulated personal information.

### Automatic and Unsolicited Flow Execution During Beta

During the beta period, We reserve the right to initiate and execute Flows in Your browser at any time while the Point&Click extension is active and You are logged into Your Account, without requiring Your explicit approval or initiation for each individual execution. This means that automations may run in Your browser without Your direct action or knowledge, for purposes including testing new Building Blocks, optimizing existing automations, performing quality assurance and debugging, monitoring platform performance and reliability, detecting security threats or abuse, and conducting product development activities.

All such automatic executions are performed using Your browser session, Your authentication credentials with third-party websites, and in Your name. Third-party websites cannot distinguish between Flows You explicitly initiate and Flows We initiate automatically for testing purposes. You are legally responsible for all Actions performed during automatic executions as if You had personally performed them.

If You are not comfortable with Point&Click initiating automations in Your browser without Your explicit per-execution approval, You must disable or uninstall the extension when You are not actively using it, use a dedicated browser profile exclusively for Point&Click that is not used for other activities, or not use the Services during the beta period. Keeping the extension active constitutes Your ongoing consent to automatic Flow execution.

## Your Use of the Services

### License Grant

Subject to Your compliance with these Terms of Service, We grant You a limited, non-exclusive, non-transferable, revocable license to access and use the Services for Your personal or internal business purposes only. This license does not grant You any ownership rights in the Services or any right to sublicense, sell, rent, or transfer access to the Services to third parties without Our explicit written permission.

By installing and activating Point&Click in Your browser, You grant Us permission to execute Flows and automations in Your browser at any time while the extension is active and You are logged into Your Account. This includes but is not limited to executing Flows You explicitly initiate, testing and optimizing Building Blocks using Your browser session, performing platform diagnostics and quality assurance testing, and conducting security monitoring and abuse prevention activities. During the beta period, this permission is particularly broad to enable rapid platform development and improvement.

You acknowledge and agree that all Flow executions, whether explicitly initiated by You or automatically executed by Our platform, are performed in Your name and on Your behalf, using Your browser session and Your authentication credentials with third-party websites. You are legally responsible for all Actions performed by Point&Click in Your browser as if You had personally performed them.

### Prohibited Uses

You agree to use the Services in compliance with all applicable laws and regulations. You shall not use the Services to violate any applicable law or regulation, to infringe the intellectual property rights, privacy rights, or any other rights of others, or to violate the terms of service of third-party websites You access through Point&Click.

You shall not create or execute Flows that engage in unauthorized access to computer systems, hacking, or circumvention of security measures. You shall not use the Services to collect, store, or process sensitive personal information including health data, financial account credentials such as credit card numbers or bank account details, social security numbers, passport numbers, or other government identifiers without proper authorization, security measures, and compliance with applicable data protection laws.

You shall not create Flows that send spam, distribute malware, viruses, ransomware, or other harmful code, or engage in fraudulent activities, phishing, or financial crimes. You shall not abuse, harass, threaten, impersonate, or harm others using the Services. You shall not attempt to reverse engineer, decompile, disassemble, or discover the source code of the Services or any component thereof.

You shall not use the Services in any manner that could damage, disable, overburden, impair, or interfere with Our systems, servers, or networks, or that could interfere with any other party's use and enjoyment of the Services. You shall not sell, rent, lease, or sublicense access to the Services without Our written permission. You shall not create Flows that violate the terms of service, robots.txt files, or acceptable use policies of third-party websites.

You shall not scrape or collect data from third-party websites in violation of their terms of service, bypass rate limits, paywalls, or access restrictions of third-party services, automate interactions with websites that explicitly prohibit automation in their terms of service, or ignore or circumvent robots.txt directives or other technical measures designed to control automated access.

You shall not access or attempt to access other users' Accounts, data, or Flows without authorization. You shall not share, sell, distribute, or misuse data obtained through the Services. You shall not create multiple Accounts to circumvent limitations, restrictions, or terminations imposed by Us. You shall not impersonate other users, individuals, or entities, misrepresent Your affiliation with any person or entity, or provide false or misleading information during registration or use of the Services.

### High-Risk Use Cases and Financial Services Warning

<div class="warning">We strongly discourage using Point&Click to automate interactions with financial services, banking platforms, investment accounts, brokerage services, payment systems, or cryptocurrency exchanges where Flow failures could result in significant financial harm.</div>

You acknowledge and agree that Flow execution may fail due to website changes, network connectivity issues, browser incompatibilities, or other technical problems beyond Our reasonable control. Failed or incorrect Flows on financial platforms could result in unintended transactions or transfers of funds, missed payments resulting in late fees or penalties, missed trading opportunities resulting in financial losses, account locks or security flags imposed by financial institutions, financial losses or penalties, and violations of regulatory compliance requirements.

We are not responsible for and expressly disclaim all liability for any financial losses, damages, or consequences resulting from failed Flow executions on financial platforms, incorrect, delayed, or duplicate transactions, security incidents involving stored financial credentials, violations of financial institution terms of service resulting in account termination or legal action, or any other financial harm arising from Your use of Point&Click with financial services.

Many financial institutions explicitly prohibit automation, screen scraping, or use of automated tools to access accounts in their terms of service. Using Point&Click for financial automation may result in immediate account termination by the financial institution, legal action by the financial institution, loss of access to Your funds during investigation, and potential regulatory consequences. You are solely responsible for ensuring Your use of Point&Click complies with the terms of service of any financial institution You automate.

If You choose to use the Services with financial platforms despite these warnings, You do so entirely at Your own risk and accept full responsibility for all consequences including financial losses. You agree to indemnify, defend, and hold harmless Point&Click and Conception AI Inc. from any claims, damages, losses, or expenses arising from Your use of the Services with financial platforms. You must implement additional verification and monitoring safeguards when automating financial tasks. You should never automate high-stakes financial transactions without thorough manual review and verification of results.

We also strongly discourage using the Services for healthcare or medical systems where errors could impact patient safety or health outcomes, legal or compliance systems where errors could result in regulatory violations or legal liability, critical infrastructure or emergency systems where failures could endanger public safety, government systems or services with strict access policies or security requirements, or any other system where automation failures could cause significant harm to persons or property.

For these high-risk use cases, We disclaim all liability to the maximum extent permitted by applicable law, and You assume all responsibility for consequences arising from Your use of the Services in these contexts.

### Third-Party Websites and Interactions

The Services enable You to interact with and automate actions on third-party websites that are not owned, controlled, or operated by Point&Click. You are solely responsible for complying with the terms of service, privacy policies, acceptable use policies, and all other policies of third-party websites You access through the Services. You are responsible for ensuring You have the legal right and proper authorization to automate interactions with third-party websites, including ensuring You have permission from website owners when required. You are responsible for all consequences resulting from Your automated interactions with third-party websites, including but not limited to account termination, legal action, data loss, or damages.

We do not control third-party websites and are not responsible for their content, practices, policies, availability, or actions. We make no representations or warranties regarding third-party websites. Your use of third-party websites through Point&Click is at Your own risk.

### Website Credentials and Storage

When You choose to store website credentials within Point&Click to enable automated login to third-party services, You represent and warrant that You are authorized to use such credentials, that You have the legal right to automate access to the associated accounts using such credentials, that You will use stored credentials only for lawful purposes and in compliance with applicable terms of service, and that You understand and accept the security risks associated with storing credentials in any system including Point&Click.

We encrypt and store credentials securely using industry-standard encryption methods. However, You acknowledge that no system is completely secure and that there is always some risk associated with storing credentials electronically. We are not liable for unauthorized access to stored credentials resulting from security breaches, hacking attempts, or other circumstances beyond Our reasonable control.

You should carefully consider which credentials You store in Point&Click, regularly review and remove stored credentials You no longer need, use strong and unique passwords for accounts You automate, monitor accounts for unauthorized access or suspicious activity, and avoid storing credentials for Your most sensitive or high-value accounts unless absolutely necessary.

### Account Suspension and Termination by Point&Click

We reserve the right to suspend or terminate Your Account and Your access to the Services immediately, without prior notice or liability, if You violate these Terms of Service or any policies incorporated by reference, if Your use of the Services poses a security risk or legal liability to Us, other users, or third parties, if You engage in fraudulent, abusive, or harmful behavior, if Your Account has been inactive for an extended period and We need to free up resources, or if required by law or legal process.

We will make reasonable efforts to provide notice before suspension or termination when circumstances permit. However, in cases of serious violations, security threats, legal requirements, or emergency situations, We may suspend or terminate access immediately without advance notice. Upon termination for cause, You will not be entitled to any refund of fees paid.

## How to Contact Us

**By email:** [contact@conception.dev](mailto:contact@conception.dev)

**By mail:**
Conception AI Inc.
2261 Market Street STE 85701
San Francisco, CA 94114
United States

© 2025 Conception AI Inc. All rights reserved.
