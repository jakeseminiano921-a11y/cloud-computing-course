# Reflection: Daily Cloud Services and Version Control

## Cloud Services I Use Regularly

In my daily routine as a student and developer, I rely on several cloud services to manage my workloads, personal tasks, and development projects.

**1. Google Drive**
* **Service Model:** Software as a Service (SaaS). I use Google Drive purely as an end-user to store files, organize notes, and collaborate on documents. Google manages the entire stack, from the physical hardware to the application interface.
* **Deployment Model:** Public Cloud. The infrastructure is owned by Google and shared among millions of users over the public internet.

**2. Heroku**
* **Service Model:** Platform as a Service (PaaS). When deploying web backends like Django applications, Heroku provides the runtime environment, databases, and necessary deployment tools. I only need to manage my application code, while Heroku completely handles the underlying servers, networking, and operating systems.
* **Deployment Model:** Public Cloud. Heroku operates on shared cloud infrastructure accessible to the public, even though individual application instances remain securely isolated.

**3. GCash**
* **Service Model:** Software as a Service (SaaS). As a mobile e-wallet, it provides a complete, ready-to-use financial application. Users interact entirely with the UI and do not manage any underlying banking databases or server logic.
* **Deployment Model:** Hybrid Cloud. Consumer-facing elements and standard transactions likely leverage public cloud infrastructure for scalability and high availability. However, highly sensitive financial records and core banking operations are typically maintained on secure private clouds to meet strict financial regulations and cybersecurity laws.

## The Role of Git & GitHub in Cloud Projects

Version control is critical when working with cloud infrastructure because modern cloud environments are largely managed through code (Infrastructure as Code). Using Git ensures that every configuration change, script update, or deployment is systematically documented, providing a precise history of modifications over time. 

GitHub serves as the collaborative backbone for these processes. It enables teams to work concurrently on separate branches, ensuring that experimental changes do not disrupt the main production environment. Through pull requests, team members can review proposed cloud resource modifications, catching syntax or logic errors before they are deployed. Furthermore, if a faulty deployment causes system issues, GitHub provides a transparent audit trail, allowing developers to execute a swift rollback to the last known stable state. This prevents extended downtime and safeguards the integrity of the cloud infrastructure.
