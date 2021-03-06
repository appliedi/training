# HIPAA Cheatsheet

We go into more detail in the rest of this book but, if you're in a rush, here's the shortest checklist we could come up with for HIPAA from an app developers perspective.

1. Assign a **Security Officer** and clearly define their responsibilities (probably managing the 11 items below this on this list). It would be smart to do this in conjuction with drafting policies.
1. **Document** everything, starting with a formal [**risk assessment**](http://www.cms.gov/Research-Statistics-Data-and-Systems/CMS-Information-Technology/InformationSecurity/downloads/IS_RA_Procedure.pdf). Documentation should be retained for 6 years. Believe it or not, you need a policy on how to manage your policies and procedures.
2. Conduct HIPAA **training** for all the people that work for you. Document completion and links to training content.
1. Get a **BAA** from all the cloud vendors you work with that process, maintain, or transmit PHI (this is pretty much any vendor you work with). Our auditors, at Coalfire, read this to mean every cloud vendor that touches ePHI, even if just as a pass through.
2. Follow **good information security practices** in your application (default to no access, turn off ports, etc).
3. **Encrypt** everything, both in transit and at rest.
4. Define and document **access controls** and rules, both at the system as well as the application level.
5. **Log everything**, and retain your logs, even if they are archived and not immediately accessible. If there might be PHI in your logs, encrypt them.
6. **Backup** data, and have a disaster recovery plan in place and tested annually.
7. Setup **monitoring** using an IDS or some other automated monitoring tool.
8. **Document all changes** to your environment, and consider a risk assessment for major changes.
9. **Revisit** policies and risk assessments **annually**.

If you want to be more thorough, go through the [CMS Audit Protocol](http://www.hhs.gov/ocr/privacy/hipaa/enforcement/audit/protocol.html). It's pretty lengthy but it will tell you your gaps between what you do and what is compliant. This is particularly important if you plan to do a 3rd party audit.
