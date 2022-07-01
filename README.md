![Awesome Infrastructure Questions](/docs/CoverPicture.jpeg "Awesome Infrastructure Questions")

# Awesome Infrastructure Questions 

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen?logo=github)](CONTRIBUTING.md)


We wish we had asked our first clients these questions during sysadmin onboarding. We curated this list based on our experience with clients.

This list of questions serves as a checklist for sysadmins and ops staff. It's extremely useful for newly onboarded teams without knowledge and understanding of an application's structure and features.

These questions can serve as a base to have a better understanding of what your ops staff will be dealing with.

[What makes for an awesome list?](AWESOME.md)

Please read the [contribution guidelines](CONTRIBUTING.md) if you want to contribute.

---

## Questions

**Infrastructure-Specific questions**

-   Where is your data center located?
-   Where do you host your application: on-premises, in a cloud or in a hybrid environment?
-   Have you set up an Infrastructure as a Code approach? If so, please specify.
-   Have you set up a Configuration Management approach? If so, please specify.
-   How many environments do you operate?
-   Do you use load balancing?
-   Is your infrastructure highly available?
-   Is it monitored accordingly with alerting setup?
-   What type of alerting do you prefer?
-   Do you have key metrics? Please describe it.
-   Did you perform performance tests before provisioning your infrastructure?
-   Do you have any disaster recovery strategies in place for the infrastructure?
-   What is the level of data center redundancy?
-   What is the level of Internet access redundancy?

**Application-Specific questions**

-   Is your application based on a monolithic or microservice architecture?
-   Do you use containers and/or containers orchestrators?
-   What programming languages are used in your application?
-   Have you set up a CI/CD process? If so, what tools did you use?
-   What version control system (VCS) do you use? Which branching strategies are in use? What triggers the CD/CD process?
-   Does your application require multi-region infrastructure?
-   What release strategies does your company use?
-   How do you communicate with customers about important changes to your platform or processes?
-   Does the application log user access activity?
-   Does the application force new users to change their password upon first login?
-   Does the application support Multi-Factor Authentication?
-   Does the application provide API documentation?

**Team-Specific questions**

-   How big is your team?
-   In your team do you have DevOps Engineers?
-   Who is responsible for issuing and maintaining SSL certificates at your company?
-   Is there a scheduled maintenance window? If yes, what is the frequency?

**Security-Specific questions**

-   Do you do penetration test regularly?
-   How often do you perform third-party penetration tests on this application and when was the last one?
-   Do you have any static code analysis in your pipelines?
-   Do you have any security/vulnerability analysis in your pipelines?
-   Is there a hardware-based firewall that protects your data from the Internet?
-   Is there virus protection on the servers?
-   How promptly are security patches applied?
-   Does your organization use a third-party security assessment firm for penetration testing? If so, please provide a Letter of Attestation or proof of services rendered.
-   Do you have a documented software development lifecycle process (SDLC), and is security integrated into this process?
-   What application security methods (e.g. application level firewall or database auditing) are used?

**Data-Specific questions**

-   What types of data does this application store or process?
-   For the data types listed above, where does the data come from, and how does it make its way into the application?
-   What methods does your solution use to send/transfer our data out to other systems?
-   Do you encrypt data at rest or in transit?
-   What encryption algorithms do you use to encrypt data at rest?
-   What encryption algorithms do you use to encrypt data in transit?
-   How do you manage the encryption keys?
-   Who has access to the encryption keys?
-   For both data stored in the application and backups, in which countries is our data stored?
-   Who can see or have access to your information?
-   Please describe your security incident response process.
-   What is the timeline for customer notification in the case of a breach?
-   What activities/actions within your application are logged?
-   How do you allow to view audit and access logs?
-   What happens to your data when service is terminated?
-   Any backup processes?
-   How many copies of your data are stored, where are they stored, and are they encrypted?
-   Do you have disaster recovery processes?

**Disaster Recovery Continuity**
- Do you have a business continuity/disaster recovery plan?
- How often do you test your BCP/DRP?
- Backups and Failover - How long is the backup history maintained?
- Can the database be restored to a specific day and time?
- Do you have a documented Incident Response Plan?

**USA related**

-   Is your application FedRAMP authorized?
-   SOC2 audit?

### License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/licenses/by/4.0/)
