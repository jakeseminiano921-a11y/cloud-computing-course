# Reflection: Daily Cloud Services and Version Control

## Cloud Services I Use Regularly

In my daily routine as a student and developer, I rely on several cloud services to manage my workloads, personal tasks, and development projects.

**1. Google Drive**
* **Service Model:** Software as a Service (SaaS). I use Google Drive purely as an end-user to store files, organize notes, and collaborate on documents. Google manages the entire stack, from the physical hardware to the application interface.
* **Deployment Model:** Public Cloud. The infrastructure is owned by Google and shared among millions of users over the public internet.

**2. Messenger**
* **Service Model:** Software as a Service (SaaS). As an end-user, I utilize Messenger to communicate and share media with others. Meta provides the fully functional application, and I do not have to manage any of the underlying messaging servers, databases, or network infrastructure.
* **Deployment Model:** Public Cloud. The application runs on Meta's vast, shared cloud infrastructure, which is accessible to the general public globally via the internet.

**3. GCash**
* **Service Model:** Software as a Service (SaaS). As a mobile e-wallet, it provides a complete, ready-to-use financial application. Users interact entirely with the UI and do not manage any underlying banking databases or server logic.
* **Deployment Model:** Hybrid Cloud. Consumer-facing elements and standard transactions likely leverage public cloud infrastructure for scalability and high availability. However, highly sensitive financial records and core banking operations are typically maintained on secure private clouds to meet strict financial regulations and cybersecurity laws.

## The Role of Git & GitHub in Cloud Projects

Version control is critical when working with cloud infrastructure because modern cloud environments are largely managed through code (Infrastructure as Code). Using Git ensures that every configuration change, script update, or deployment is systematically documented, providing a precise history of modifications over time. 

GitHub serves as the collaborative backbone for these processes. It enables teams to work concurrently on separate branches, ensuring that experimental changes do not disrupt the main production environment. Through pull requests, team members can review proposed cloud resource modifications, catching syntax or logic errors before they are deployed. Furthermore, if a faulty deployment causes system issues, GitHub provides a transparent audit trail, allowing developers to execute a swift rollback to the last known stable state. This prevents extended downtime and safeguards the integrity of the cloud infrastructure.
