![Awesome Infrastructure Questions](/docs/CoverPicture.jpeg "Awesome Infrastructure Questions")

# Awesome Infrastructure Questions [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

We at dyrector.io curated this list of briefing questions that need to be cleared to lay out a game plan to work on a client's infrastructure, migrate applications to the cloud and so on.

Feel free to use them to better understand what needs to be done.

[What makes for an awesome list?](AWESOME.md)

Please read the [contribution guidelines](CONTRIBUTING.md) if you want to contribute.

---

## Questions

**Infrastructure-Specific questions**

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

**Application-Specific questions**

-   Is your application based on a monolithic or microservice architecture?
-   Do you use containers and/or containers orchestrators?
-   What programming languages are used in your application?
-   Have you set up a CI/CD process? If so, what tools did you use?
-   What version control system (VCS) do you use? Which branching strategies are in use? What triggers the CD/CD process?
-   Does your application require multi-region infrastructure?
-   What release strategies does your company use?
-   How do you communicate with customers about important changes to your platform or processes?

**Team-Specific questions**

-   Who big is your team?
-   In your team do you have DevOps Engineers?
-   Who is responsible for issuing and maintaining SSL certificates at your company?

**Security-Specific questions**

-   Do you do penetration test regularly?
-   How often do you perform third-party penetration tests on this application and when was the last one?
-   Do you have any static code analysis in your pipelines?
-   Do you have any security/vulnerability analysis in your pipelines?

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

**USA related**

-   Is your application FedRAMP authorized?
-   SOC2 audit?

### License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)