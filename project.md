# E-commerce Business Risk Assessment
This is my project about assessing the risk, threat,... giving new proposed business's model, advising technology solutions. Every secure solutions proposed in this project have been searched on **[g2.com](https://www.g2.com/)**

## I. Goal
- Data Loss Prevention is one of the biggest threats in the field of corporate information security. Statistics on Proofpoint's methods that can cause data loss in 2010.

![image](https://github.com/hoangbui24/Risk-Assessment/assets/71567852/74c68903-185b-42a1-bc1e-8978f8070a37)
![image](https://github.com/hoangbui24/Risk-Assessment/assets/71567852/5f26d532-fc14-45fc-97e6-b9c76881207e)

- Currently, in Vietnam, this issue is of concern to businesses. Realizing the "heat" of this problem, let's research and come up with solutions to overcome this problem.

## II. Current status of the enterprise's network system

- Currently the business has about 100 users. For detailed information about the services running in the system, see the image below. Detailed information about the system:
   - Administration according to the Domain model
   - Cisco router integrates firewall
   - Load balancing device connected to the internet
   - There is no antivirus software, specialized firewall or other security policies.
   - There is no policy for operating the system
   - There is no policy on information security issues in the system
   - There is no data backup and recovery policy
   - All servers are located at the Data Center
 
  ![image](https://github.com/hoangbui24/Risk-Assessment/assets/71567852/fd5eee39-bf83-49bd-8cae-8e97e1adfe53)

## III. Risk Assessment Process

### 1. Determine the Scope of the Risk Assessment
- The scope encompass an entire organization
  
### 2. Threat and Vulnerability Identification
- Weaknesses and risks in the current network model

  **Weakness**
  - There is no anti-virus software, specialized firewalls or other security policies: This is the weakest point of the current network model. The absence of basic security measures such as anti-virus and firewall systems is vulnerable to malware, malicious code, cyber attacks, etc.
  - There is no policy operating system: This leads to the system possibly operating incorrectly, causing security risks. For example, employees may accidentally install malware or malicious code on the system or configure the system incorrectly, making the system vulnerable to attack.
  - There is no policy on information security in the system: This creates many difficulties in managing and protecting the system. For example, businesses do not have regulations on password use, mobile device use, system access, etc., making the system easily attacked.
  - There is no data backup and recovery policy: This leaves businesses vulnerable to data loss in the event of an incident.
  - Using Cisco routers with integrated firewalls: Cisco routers with integrated firewalls can provide some basic security features, but cannot meet current security requirements.
  - No network separation: The absence of network separation makes computers in the system accessible to each other, facilitating network intrusion attacks.
  - All servers located in the Data Center: Having all the servers located in the Data Center makes the system vulnerable if the Data Center is attacked or destroyed.
  - No Endpoint Security: Not having endpoint security can easily lead to endpoint devices being attacked, thereby escalating privileges to obtain information.
  - No physical security: No camera systems, sensors, HVAC, UPS, fire detection systems, etc.
  - Not equipped with IDPS: This leads to traffic coming from strange addresses, or malicious code execution that is not detected and can enter the system if bypassed through the firewall.
  
  **Risks**
  - Risk of data loss: This is the biggest risk for businesses. Business data can be lost due to cyber attacks, human error, or other causes.
  - Data leak risk: Business data can be leaked due to cyber attacks, human error, or other causes. Data leaks can cause many damages to businesses, including loss of reputation, loss of competitive advantage, or even compensation to related parties.
  - Risk of operational disruption: The network system may be attacked, leading to disruption of business operations. Operational disruptions can cause a lot of damage to a business, including loss of revenue, loss of reputation, or even bankruptcy.
  - Risk of cyber attack: Network systems can be attacked by hackers, leading to data theft, data leakage, or even system destruction

- Risks related to data loss
  - Attacker
    - Cyberattack: Attacker can use network attack techniques such as network attack, system attack, application attack to penetrate the system. system and data theft.
    - Malware attack: Attacker can use malicious software such as viruses, trojans, worms, ransomware,... to penetrate the system and steal data.
    - Denial of service attack (DoS attack): Attacker can use denial of service attack techniques (DoS attack) to paralyze the system, making it inaccessible, causing damage, reduced reputation.
    - Social engineering attack: Attackers can use social engineering attack techniques to trick users into providing sensitive information, thereby stealing data.
    - Physical attack: Attacker can attack physical systems, such as stealing computers, data storage devices,... to steal data.
   
  - Staff
    - Human error: Employees may accidentally delete data, overwrite data, or improperly configure the system, leading to data loss.
    - Security policy violation: Employees may violate security policies, such as using weak passwords, storing sensitive data on personal devices,... leading to loss cool data.
    - Corruption: Employees can be corrupt, using their access rights to steal data.
    - Intentional sabotage: Employees can intentionally sabotage the system, leading to data loss.
    - Internal threat: Employees can be attacked by hackers or rival organizations, leading to data loss, lack of solidarity, and lack of availability.
   
  ### 3. Analyze Risks and Determine Potential Impact


> [!IMPORTANT]
  This is current risk score table of system, as you can see, the risk classification column is dominated by High Risk.
  
  ![image](https://github.com/hoangbui24/Risk-Assessment/assets/71567852/866147c3-65a7-40d5-9403-afaa3587cff2)

  > For a better view, please visit: [My Google Sheet](https://docs.google.com/spreadsheets/d/1mHe1lyoyAHyuWpTBZVprVDSxwErfx3lVJW9FW-Mvfn4/edit#gid=0)

  ### 4. Reconstructing system and giving solutions
> [!NOTE]
  New model
  ![image](https://github.com/hoangbui24/Risk-Assessment/assets/71567852/725f2ffb-7a35-4f3b-bd7a-1cfa90ec6917)

  #### a. Host Security
  ![image](https://github.com/hoangbui24/Risk-Assessment/assets/71567852/bc858f23-ef09-4b81-b006-c72871c360a1)
  - **ESET Protect Advanced** is a comprehensive security solution that provides advanced protection for endpoints, servers, and mobile devices.
    - **Endpoint Protection:** real-time malware detection, advanced behavioral analysis, and exploit prevention. It helps protect endpoint devices from a large number of threats such as viruses, ransomware, spyware, phishing attacks.​
    - **Stop zero-day threats:** Protect against ransomware and new, never-before-seen threat types using adaptive scanning, machine learning, cloud sandboxing, and deep behavioral analytics. ​
    - **Limit data loss:** Protect Advanced includes Data Loss Prevention capabilities, which help protect sensitive data from unauthorized access or leaks. It allows administrators to define and enforce policies to control the transmission or storage of sensitive information, reducing the risk of data breaches.​
    - **Device Control:** With device control, administrators can manage and control the use of portable devices such as USB drives, external hard drives, and optical media. This helps prevent data leaks, malware infections through external devices, and unauthorized data transfers.
   
  #### b. Network Security
  ![image](https://github.com/hoangbui24/Risk-Assessment/assets/71567852/aba570b1-6b14-4167-82d5-d3e67e4908a1)
  - **IBM Security QRadar Suite** is a comprehensive security solution provided by IBM. It combines advanced technologies such as threat identification, intelligence analysis, incident classification and prioritization to provide organizations with a powerful platform to detect, respond and prevent threats security.
    - **Network threat analytics:** QRadar SIEM seamlessly integrates network behavior data into threat analysis, enabling threat alignment and detection.
    - **User behavior analytics (UBA):** QRadar SIEM provides user behavior analytics, providing greater visibility into insider threats, anomalous behavior, and generating meaningful information .
    - **Threat intelligence integration:** QRadar SIEM integrates with threat intelligence sources, including IBM X-Force Threat Intelligence, to understand the latest threat landscape and leverage malicious IP addresses, URLs, and file hashes malware. malware.
    - **Network and user threat hunting:** QRadar SIEM enables comprehensive threat hunting by generating intelligence from diverse data sets and assisting analysts in hunting cyber threats in real time.
    - **Compliance support:** QRadar SIEM helps organizations demonstrate compliance and compliance with legal regulations and internal audits by providing evidence of compliance to the environment.
    - **Seamless analyst experience:** QRadar SOAR provides a seamless experience for analysts, allowing them to respond quickly to threats and handle incidents through a single dashboard.
    - **Efficient analyst response:** QRadar SOAR helps speed up the response process by applying comprehensive case management, including custom layouts, flexible playbooks, and personalized responses.
    - **Automation:** QRadar SOAR uses automation to minimize the skills gap. Automation capabilities include linking elements, investigating and prioritizing cases, and automatically updating the playbook as the investigation progresses, with the addition of threat intelligence at each stage of the process. procedure.
    - **Breach response:** QRadar SOAR helps prepare for and respond to privacy breaches by integrating privacy reporting tasks into overall incident response playbooks. At the same time, it helps work together with privacy, HR and legal teams to meet the requirements of more than 180 privacy regulations.
      
  ![image](https://github.com/hoangbui24/Risk-Assessment/assets/71567852/966ab4b8-dbe9-4637-8d8d-431549999af6)

  #### c. Identity Security
  ![image](https://github.com/hoangbui24/Risk-Assessment/assets/71567852/7781c56a-f283-4e97-83f8-42a335f4b5c0)
  - **Microsoft Defender for Identity** (formerly Azure Advanced Threat Protection, also known as ATP) is a cloud-based security solution that uses Active Directory signals to identify, detect, and investigate threats, Compromised identities and malicious behavior directly impact the organization.
    - **Monitor and record user behavior and activities:** Monitor and analyze user activities and information within the intranet, such as permissions and group memberships, creating a behavioral baseline for per user.
    - **Defender for Identity:** identifies anomalies, provides suspicious information and events, assesses threats, monitors domain controllers, providing a comprehensive view of all user activities from any location. equipment.​
    - **Protect user identities & reduce attack surface:** Defender for Identify provides detailed information about user identities and recommends security methods. Through cve and user profile analysis.​ Identify and analyze Lateral Movement Paths of attackers and prevent them. Statistics identify users and devices authenticating with cleartext passwords and provide additional insights to improve enterprise-wide security policies and models.​
    - **Protect Active Directory Federation Services:** plays an important role in authentication in hybrid environments. Defender for Identity provides protection by monitoring and identifying on premises attacks on ADFS and providing the ability to log events from ADFS.​
    - **Reconnaissance:** Identify fake users trying to exploit information. Objects search for information about user names, user roles, device IP addresses, and resources using different methods.
  ![image](https://github.com/hoangbui24/Risk-Assessment/assets/71567852/9810922c-e4ff-411a-b81c-a0c6c7d4bbe6)

  #### d. App Security
  ![image](https://github.com/hoangbui24/Risk-Assessment/assets/71567852/6aa5b25b-a91c-4eae-aafb-79855538a498)
  - **Zed Attack Proxy (ZAP)** is an open source tool developed by OWASP, a non-profit organization specializing in web application security. ZAP is designed to help security professionals and developers test and improve web and API application security.
    - **Proxy Intercept:** ZAP allows viewing and modifying HTTP requests and responses between the browser and web server, assisting in finding web application security vulnerabilities​
    - **Active Scanner:** ZAP provides an automatic scanning tool to detect common security vulnerabilities such as SQL injection, XSS (Cross-Site Scripting) and many others.​
    - **Passive Scanner:** ZAP monitors and detects security vulnerabilities in the requests and responses that the browser and server exchange without intervention.​
    - **API testing:** In addition to web application testing, ZAP also supports security testing of API applications (RESTful and SOAP)​
    - **Plug-ins and Extensions:** ZAP allows customization and extension of features and tools to enhance performance in improving application security.
   
  ![image](https://github.com/hoangbui24/Risk-Assessment/assets/71567852/1344c316-fe85-4e7a-9917-8cb1fbe6f8b0)

  #### e. Database Security
  ![image](https://github.com/hoangbui24/Risk-Assessment/assets/71567852/fd180b16-ff06-42a4-8861-9da565191d63)
  - **Satori Data Security Platform** helps organizations protect data effectively and automatically. It provides the ability to detect, classify, and protect sensitive data, while also helping to monitor and control data access. Satori also integrates with popular data analytics tools, helping to increase security and privacy for data users.
    - **Automatic data classification:** Satori has the ability to detect and classify sensitive data automatically and quickly. The platform can scan and discover data in various data sources, including semi-structured data like JSON.​
    - **Apply security policies:** Satori allows automatically applying security policies to newly discovered sensitive data. This helps ensure that data is protected and complies with security regulations.​
    - **Data access monitoring and control:** Satori provides data access monitoring and control capabilities for users. The platform allows management of who accesses data, when and how. This helps minimize the risk of data leak or misuse.​
    - **Secure data in various storage platforms:** Satori integrates with various data storage platforms such as Amazon Redshift, helping to protect data in diverse environments. The platform also supports on-demand data anonymization, based on user, role, and dataset.​
    - **Integration with data analytics tools:** Satori integrates with data analytics tools such as Amazon QuickSight, Tableau, Power BI, helping to monitor and apply security and privacy policies for data consumers Whether .
   
  ![image](https://github.com/hoangbui24/Risk-Assessment/assets/71567852/f6216d2d-1970-4fb9-9a24-c19d72e7f067)

  #### f. Database Firewall
  ![image](https://github.com/hoangbui24/Risk-Assessment/assets/71567852/c5c3cc4c-d3d8-4021-a9b9-5403a54ce801)
  - **Oracle Database Firewall** acts as the first line of defense for databases, helpinp prevent internal and external attacks from reaching the database. Highly accurate SQL grammar-based technology monitors and blocks unauthorized SQL traffic on the network before it reaches the database. Oracle Database Firewall is easy to configure and can be deployed with no changes to existing applications.
  ![image](https://github.com/hoangbui24/Risk-Assessment/assets/71567852/2b6a9ce7-ead3-420e-a450-6868259b1949)
    - **Detect and prevent SQL attacks:** Oracle Database Firewall uses SQL behavioral analysis to detect and prevent SQL attacks, including injection attacks such as SQL injection and PL/SQL injection. It provides the ability to detect attack patterns and prevent anomalous queries from SQL query execution.
    - **Record and control database activity:** Oracle Database Firewall logs all database access activities, including SQL queries and data operations. This helps create a detailed record of database activities and supports monitoring, compliance testing, and security analysis.
    - **Integration with security event management (SIEM) systems:** Oracle Database Firewall has the ability to integrate with security event management (SIEM) solutions. This enhances the ability to detect and respond to security threats.
      
  #### g. Server Firewall
  ![image](https://github.com/hoangbui24/Risk-Assessment/assets/71567852/5edc901e-c490-4014-be97-9a4a53defeca)
  - **Cloudflare Spectrum** provides security and acceleration for any application that relies on TCP or UDP protocols
    - **DDoS Protection:** Cloudflare Spectrum provides anti-DDoS protection for attacks at layers 3-4 of the OSI model, especially against TCP and UDP protocol-based DDoS attacks
    - **Hide source IP:** By using Cloudflare Spectrum in front of your application, the source IP address is hidden, preventing attackers from directly attacking the server.
    - **Protocol and port filtering:** Cloudflare Spectrum rejects packets targeting unknown protocols or ports that have not been specified. This helps prevent unauthorized access.
   
  #### h. Physical Security
  ![image](https://github.com/hoangbui24/Risk-Assessment/assets/71567852/db5e5275-c930-45a8-976f-762b3c726a5e)
  - **APC** provides physical protection solutions for data centers, including UPS (Uninterruptible Power Supply) systems to ensure uninterrupted power supply, automatic power transfer switches (ATS - Automatic Transfer Switch) to convert power automatically when an incident occurs, fire alarm system and temperature incident management solutions.
    - **APC Smart-UPS**
      
      ![image](https://github.com/hoangbui24/Risk-Assessment/assets/71567852/2da2234d-d1ae-4ec8-93b0-3124ab0c5436)
      - APC's Smart-UPS product line includes many different models suitable for different sizes of data centers. For example, the Smart-UPS 1500VA is a popular model used for small or medium office applications, while the Smart-UPS 3000VA or 5000VA is used for larger data centers.
     
    - **APC Environmental Monitoring Unit (AP9340)**

      ![image](https://github.com/hoangbui24/Risk-Assessment/assets/71567852/776cf571-91db-4e69-a152-c4e6027608a0)
      - This is a multi-function environmental management device from APC. It provides fire sensors, temperature sensors, humidity sensors and door sensors, allowing monitoring and warning of environmental incidents in data centers.
     
  ![image](https://github.com/hoangbui24/Risk-Assessment/assets/71567852/f2e54252-3b23-4ba4-998a-a1699d8ed680)
  - **Honeywell** is a multi-industry technology company providing security and environmental monitoring solutions for data centers. They provide IP camera products, temperature and humidity sensors, fire sensors, alarm systems, and management software.
      - **Honeywell IPCAM-WIC1**
   
        ![image](https://github.com/hoangbui24/Risk-Assessment/assets/71567852/86b75a11-a2ed-460f-8611-7faf96e6cad2)
        - Honeywell's high-end IP camera line with high resolution, ability to observe in low light conditions and sharp image quality. Camera models in this line include pan-tilt cameras, outdoor cameras, infrared cameras, and PTZ (pan-tiltzoom) cameras.
       
      - **Honeywell's Air Quality C7355 Multi Sensor**
        
        ![image](https://github.com/hoangbui24/Risk-Assessment/assets/71567852/dd8dc683-c59c-43d0-bfb0-1fb9b6e3e5d7)
        - The C7355 is an advanced, configurable device for commercial buildings. It monitors PM2.5/PM10, CO2, TVOC, temperature and relative humidity. This device communicates using the Modbus protocol over RS-485 and easily integrates with the building management operation.

  ## IV. Policy development

  ### 1. Network policy
  - The network system is divided into separate areas, including at least: Internet connection area, intermediate area between the internal network and the Internet (DMZ area), user area, administration area and server (DataCenter area). Servers that serve information on the Internet are located in the DMZ area, while servers that store and process important data are located in the DataCenter area.
  - Sensitive data is not stored in the Internet connection partition and DMZ partition.
  - Security policies are periodically reviewed, including access, connections, devices, and illegal software installation on the network, at least every three months.

  ### 2. SIEM policy
  - Build a SIEM system for centralized information and event management, responsible for collecting log and event information throughout the enterprise system and synthesizing it all on a single interface.
  - Track and monitor network traffic of important devices.
  - Analyze abnormalities in network traffic and handle them. Focus on common data leak protocols (FTP, HTTP, DNS)
  - Monitor user behavior (especially for accessing sensitive data)
  - Define the types of data that can be collected by a SIEM system and the sources it can be collected from.
  - Determine retention periods for different types of data, considering legal requirements and regulatory compliance.
  - Establish processes to periodically delete and remove obsolete or unnecessary log data across the log management database to reduce storage risk

  ### 3. SOAR policy
  - Presents the step-by-step workflow for the incident response process, including incident triage, control, suppression, and recovery. Define communication, coordination, and collaboration processes between team members and external stakeholders.
  - Define how sensitive data is handled during incident response, ensuring compliance with privacy regulations. Specify data collection, storage, and destruction procedures, as well as mechanisms to protect personal information (PII) and other sensitive data.
  - Define training requirements for incident response teams, including initial onboarding and ongoing training to stay informed about the latest threats, tools and techniques.
  - Continuously update incident response processes for emerging threats and dangerous attack methods that threaten the company's information security. Periodically every 3 months or immediately after notification of the latest dangerous attack.

  ### 4. Firewall policy
  - Firewall located in front of the server performs detailed inspection of every request and response for all types of traffic to detect and block anything malicious.
  - Firewalls also use signatures to identify types of attacks.
  - Combine with whitelist, blacklist and in-depth analysis of data. When detecting attack data, put it in blacklist and vice versa with whitelist. Administrators also focus on policy management for more optimal operations.
  - Firewall rules must be reviewed and updated to prevent new attack methods from the provider periodically once a month.

  ### 5. Database policy
  - Apply encryption to sensitive data.
  - Use encryption during data transfer between the application and the database.
  - Database administrators must have a mechanism to protect and decentralize access rights to database resources, granting only necessary rights to each group of access objects.
  - The unit must have measures to monitor and log database access and operations when accessing the database
  - Do not allow any direct physical access to the company's storage system without approval from authorized parties.
  - Continuously update patches for database management software.

  ### 6. Backup & Recovery policy
  - The system must have a backup database at the Disaster Recovery Backup Center. The standby database must be located somewhere away from the current database location and must be updated no more than one hour from the main database.
  - The network line connecting the backup center must be a private network line, highly available and not used for other purposes.
  - The database must be backed up periodically every day. Backup copies must be managed and stored safely at a backup center.
  - The disaster recovery backup center must be inspected once a month and ensure all operations are 100%.
  - Backup data must be classified for importance and security. Ensure privacy of user data.
  - When an incident occurs, there must be a mechanism to prioritize the recovery of important data related to system availability before recovering the remaining data.

  ### 7. Personal management policy
  - Employees, including interns, are required to participate and
complete information security and awareness training courses and regularly update regulations, policies, and procedures relevant to their duties.
  - The information safety and security awareness training program is divided into two main parts: General awareness of information security and relationship with Policies and Standards on information safety and security.
  - Non-compliance with Information Safety and Security Policies and Standards may result in disciplinary measures, depending on the severity of the violation, there will be corresponding sanctions.
  - The employee's manager needs to notify the entire team of the employee's termination.
  - Employees who plan to resign or change jobs need to notify the manager 1 month in advance from the official date of resignation, to help the manager have time to arrange a replacement for that position.
  - Accounts and access to all company systems must be adjusted or canceled 24 hours prior to the end of the employment contract.
  - An employee's access rights are reviewed whenever that employee's role is changed. Management is responsible for this review, that is, it does not completely delete but only disables, and when necessary, it can be re-authorized to others.
  - Leaving employees must hand over assets, including assets belonging to the company such as keys, computers, employee cards, data or documents related to the company, etc.

  ### 8. Physical security policy
  - Security surveillance systems, including cameras, surveillance devices, and recording devices, require their strategic placement and continuous operation to ensure effective surveillance. Both wired and wireless systems, depending on specific requirements, must be deployed at entry and exit points throughout the facility and in vulnerable areas.
  - Entry controls should be in place to limit and monitor physical access to systems that store, process, or transfer data.
  - Cameras placed in departments should not be pointed directly at employees and their work screens.
  - Except in the case of maintenance, do not tamper with or interact with the equipment, and maintenance must be supervised by authorized personnel.
  - A safe distance between employees should be maintained, with the use of partitions and appropriate seating arrangements depending on each employee's job.
  - In case of damage to property, notification should be immediately given to the competent department for inspection and handling.
  - Security equipment should be inspected and maintained at least every 6 months to ensure best performance.
  - The room containing the power source needs to be locked tightly and patrolled regularly, placed in a location where security staff can quickly check when an incident occurs.

> [!IMPORTANT]
  After applying solutions, services and policies. The model has many considerable changes, as table below
  ![image](https://github.com/hoangbui24/Risk-Assessment/assets/71567852/323b37aa-9ede-4a61-91d5-efff8e719315)

>  For a better view, please visit: [My Google Sheet](https://docs.google.com/spreadsheets/d/1mHe1lyoyAHyuWpTBZVprVDSxwErfx3lVJW9FW-Mvfn4/edit#gid=0)

## V. Conclusion
- In conclusion, security risk assessment is a vital process for organizations to identify, analyze, and mitigate potential risks and vulnerabilities. By systematically evaluating threats, vulnerabilities, and their potential impact, organizations can make informed decisions and implement appropriate security measures to protect their assets, systems, and operations.
- Through the steps of asset identification, threat identification, vulnerability assessment, risk analysis, and risk evaluation, organizations gain a comprehensive understanding of their security landscape. This understanding enables them to prioritize risks and allocate resources effectively, focusing on the most critical areas that require attention.
- Moreover, conducting regular security risk assessments promotes a proactive approach to security management. It allows organizations to stay ahead of emerging threats, adapt to evolving technologies and business environments, and continuously improve their security posture. Ongoing monitoring and review of implemented controls ensure that security measures remain effective and aligned with changing circumstances.
- By effectively managing security risks, organizations can minimize the potential for security breaches, data loss, disruption to operations, financial losses, and damage to reputation. Security risk assessment serves as a foundation for developing robust security strategies, implementing appropriate controls, and fostering a culture of security awareness within the organization.
- Ultimately, security risk assessment empowers organizations to make informed decisions, allocate resources wisely, and maintain a strong defense against potential threats. It is an essential component of a comprehensive security program, enabling organizations to safeguard their assets, protect their stakeholders, and maintain trust in an increasingly complex and interconnected digital landscape.







  



  










  
  




