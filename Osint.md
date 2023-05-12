---
Title: Open Source Intelligence What Does the Internet Know About You?
extensions:
  - qrcode
---

# Who is this Guy?
## OSINT Engineer at AbbVie:
  - Primary Function is to Automate OSINT at AbbVie for Mergers and Acquisitions.
  - Currently automating a good set of processes developed by great engineers at AbbVie.

## Previously worked at AWS:
  - Security Engineer at AWS CloudFormation. 
  - Got to work at large scale and develop opinions on automation, testing,  and architecture. 
  - Wrote fixes for bugs and misconfigurations based on OSINT Findings. 

## Former Incident Responder for NCAR (The National Center for Atmospheric Research) 

## Recovering Java Developer 

## Dad and permaculturist:
  - Most important work for me is my family and passing on critical thinking skills.
  - Very involved in permaculture/homesteading. 
  - Fermentation and food cultures. 

##  Masters in Applied Intelligence from Georgetown University (Next Week). 

@051N70W1 on Twitter 
```qrcode
https://twitter.com/051N70W1
```

---

# Roadmap

- The Intelligence Lifecycle
- OSINT and the Intelligence Lifecycle
- Importance of OSINT for organizations:

## Overview of the goals of the session:
  - Risks associated with an organization's online presence.
  - The best practices for defending against online attacks. 
  - Policies and tools available to protect against data leaks. 
  - Benefits of integrating OSINT into your organization. 


---

# Intelligence Lifecycle

The Intelligence Lifecycle is a systematic process that intelligence analysts follow to gather, analyze, and disseminate intelligence. It consists of several stages:

## 1. Planning and Direction (Have a Plan):
   - Defining intelligence requirements and objectives.
   - Identifying potential sources of information.
   - Allocating resources and determining priorities.

## 2. Collection (A.K.A. Not Enough Disk Space):
   - Gathering data and information from various sources.
   - Conducting open-source research, interviews, surveillance, etc.
   - Dark Net Monitoring and Analysis
   - Social Media Collection

## 3. Processing and Exploitation (import pandas as pd):
   - Organizing and filtering collected information.
   - Evaluating the reliability and relevance of the data.
   - Extracting key insights and identifying patterns.

## 4. Analysis and Production (Get your analytical framework):
   - Assessing and interpreting the information.
   - Developing insights and actionable intelligence.
   - Formulating hypotheses and making predictions. 

## 5. Dissemination (Executive Summary + Visualizations):
   - Communicating intelligence findings to relevant stakeholders.
   - Presenting reports, briefings, or visualizations.
   - Providing recommendations for decision-making.

## 6. Feedback and Evaluation (The algorithm trained by your consumers):
   - Assessing the effectiveness of intelligence products.
   - Incorporating feedback from consumers.
   - Identifying areas for improvement and refining processes.

The Intelligence Lifecycle is a continuous and iterative process, allowing for ongoing intelligence gathering and refinement to support decision-making and mitigate risks.

---

# Open Source Intelligence (OSINT)

- Open Source Intelligence (OSINT) is the collection and analysis of publicly available information.
- It is a crucial Intelligence Discipline.
- Frequent problems include:
  - Data Quality
  - Data Reliability
  - Data Volume

## Collection Phase:

- Gather data from publicly accessible sources.
- Examples: websites, social media, news articles, government reports, public records.
- Utilize search engines, specialized OSINT tools, trainings, and manual investigation techniques.
  - https://osintcurio.us/
  - https://www.theosintion.com/
  - https://inteltechniques.com/
  - https://webbreacher.com/
  - https://obsidian.md/
  - RSS is a highly underrated tool, and everyone should be using it!
  - Learn programming language though I reccomend python or powershell 
  - Learn to do manual collection first, then automate

- Assess reliability, credibility, and cross-reference multiple sources.
  - If we believed everything we heard on the internet the world is flat and lizard people run the joint. 
  - Reliability relates to the source. 
  - Credibility refers to the content reported. 
  - These should be reevaluated constantly. 
 

## Processing and Exploitation Phase:

- Process and analyze OSINT data.
- Integrate with other intelligence sources.
- Extract insights, identify patterns, and evaluate significance.
- Intelligence should be Timely, Accurate, and Actionable. 

## Analysis and Production Phase:

- Synthesize OSINT with other intelligence disciplines.
- Develop comprehensive intelligence products.
- Can also be used for ad-hoc reporting
  - You are probably doing this now!

## Benefits of OSINT:

- Provides valuable context and supports decision-making.
- Enhances situational awareness.
- Applicable in various domains: national security, law enforcement, business intelligence, Information Security. 

## Ethical Considerations:

- Respect privacy rights and adhere to applicable laws and regulations.
- Maintain ethical standards in collection, analysis, and use of OSINT data.
- There are so many grey areas here, you need to prepare ahead of time for what the ethical thing to do is. 

---

# Risks of Oversharing Online 

## 1. Data Breaches:

- Sharing sensitive company information online, even inadvertantly,  increases the risk of data breaches.
- Example: This could be as simple as sharing a picture of a badge on the first day, a picture of a workspace, or where you all meet after work to blow off steam. 

#### Stories:

- /etc/shadow
- Everyone to Golden Sun for drinks and the cloned RFID Badge
- #firstday badge pictures
- The OT Network is publicly routable!

## 2. Brand Damage:
- Oversharing inappropriate or controversial content can harm the company's brand reputation.

#### News Story: 

NY Hospital fires Ex-Morgue worker for Allegedly posting Cadaver pics to Social Media. 
May 7th, 2023

## 3. Intellectual Property Theft:
- Sharing proprietary information online can expose the company to intellectual property theft.
- Example: Posting unreleased product designs can lead to unauthorized replication or counterfeiting.

#### Story: 

ITAR Satellite schematics, that thankfully were no longer ITAR

## 4. Phishing and Social Engineering:
- Cybercriminals can exploit overshared information for phishing and social engineering attacks. They will steal images or data from LinkedIn of your employees, search through first day posts to find out who sells you critical devices you use in your business and impersonate them in a phishing campaign. 

#### Story: 

The Million Dollar Mistake

---

# Risks of Oversharing Online (Cont.)

## 5. Legal and Compliance Risks:
- Oversharing confidential or regulated information online can lead to legal and compliance violations.

#### News Story: 

UK fines TikTok $15.8 million for UK's Data Protection Regulation Violations

## 6. Competitive Disadvantage:
- Overexposing internal processes or strategies can give competitors an advantage.

#### Hypothetical: 

Pretend with me for a moment that AbbVie decides to post our M&A targets on a website. It inadvertenly becomes publicly accessible our competitors would have a huge advantage as they could use this information to their advantage. 

---

# Defending Employees Online 

### 1. Employee Education and Awareness:
   - Provide comprehensive training on responsible online behavior and safe social media practices.
   - Raise awareness about the risks of oversharing personal or company information.

### 2. Strong Password Policies:
   - Enforce strong password requirements and enable two-factor authentication (2FA).
   - Encourage employees to use unique passwords for different accounts.
   - Track employee passwords in breaches haveibeenpwned.com and dehashed.com both are great options for employers. Dehashed will give you the password hash or cleartext when available. You can also monitor darknet markets and collect your domain credentials yourself. 

### 3. Privacy Settings and Personalization:
   - Educate employees on adjusting privacy settings to limit visibility of personal information.
   - Promote regular review and updates of privacy settings.
   - Include Privacy Engineering into your own products, processes, and procedures. 

### 4. Safe Online Practices:
   - Encourage employees to think before sharing personal or sensitive information online.
   - Remind employees to be cautious of social engineering tactics like phishing emails.
   - If you test users, consider gamification, and help them see phishing that may uniquely target your organization/industry. MAKE THIS A POSITIVE EXPERIENCE!

### 5. Incident Response and Reporting:
   - Establish an incident response plan for data breaches or privacy incidents.
   - Encourage employees to report suspicious activities to the IT or security teams.
   - People & Processes > Products. 
### 6. Empower Users:
   - Provide users with reccomendations for password managers or other tools. 
   - Provide links to information of credit freezes, mobile phone security, social media training.
   - Talk about privacy, it is a great tool to combat the effectiveness of OSINT by getting rid of the low-hanging fruit. 
   - Don't take your knowledge for granted, You work in a bubble learn what others do and help implement your knowledge into your customers needs. 

### Potential Resources:
- https://inteltechniques.com/links.html (please don't be down this time!) 
- https://www.amazon.com/Smart-Girls-Guide-Privacy-Practical/dp/1593276486


---

# Policies and Processes for Defending Employees Online

## 1. Social Media Usage Policy:
   - Guidelines on appropriate behavior and responsible use of social media platforms.
   - Clear instructions on what kind of information can be shared and what should be kept confidential.

## 2. Password Security Policy:
   - Requirements for creating strong passwords and guidelines for password management.
   - Encouragement to use password managers and enable two-factor authentication (2FA).

## 3. Privacy Policy:
   - Policies and procedures for protecting employee and customer personal information.
   - Guidelines on how to handle and share sensitive data, both internally and externally.

## 4. Phishing Awareness and Email Security Policy:
   - Training on identifying and reporting phishing attempts.
   - Procedures for handling suspicious emails and avoiding data breaches.

## 5. Incident Response Policy:
   - Clearly defined steps to follow in the event of a data breach or privacy incident.
   - Roles and responsibilities of employees during incident response and reporting.

## 6. Bring Your Own Device (BYOD) Policy:
   - Rules and guidelines for employees using personal devices for work-related activities.
   - Security requirements, such as password protection and device encryption.

## 7. Remote Work and Wi-Fi Security Policy:
   - Guidelines for securing remote work environments and using public Wi-Fi safely.
   - Recommendations for using virtual private networks (VPNs) and securing home networks.

## 8. Data Classification and Handling Policy:
   - Procedures for classifying and handling sensitive data based on its level of confidentiality.
   - Instructions on data encryption, storage, and sharing practices.

## 9. Employee Monitoring and Acceptable Use Policy:
   - Clear communication on employee monitoring practices, if applicable.
   - Guidelines on acceptable use of company resources, including internet and email.

---

# Tasks for a Dedicated OSINT Analyst or Team

## 1. Gathering and Analyzing Open Source Intelligence:
   - Conducting comprehensive research and collecting relevant information from publicly available sources.
   - Monitoring social media platforms, news articles, forums, and other online sources for potential threats or actionable intelligence.


## 2. Threat Intelligence and Risk Assessment:
   - Assessing the organization's digital footprint and identifying potential vulnerabilities.
   - Monitoring and analyzing emerging threats, attack trends, and indicators of compromise.
   - Providing regular reports and updates on the threat landscape to support proactive defense strategies.


## 3. Investigating Security Incidents and Data Breaches:
   - Conducting OSINT investigations to gather information about potential attackers, their methods, and motivations.
   - Correlating open-source data with internal security logs and incident response activities.
   - Assisting in incident response efforts by providing relevant intelligence and insights.


## 4. Monitoring Brand Reputation and Online Presence:
   - Tracking online mentions and sentiment about the organization, its products, and key personnel.
   - Identifying and addressing potential reputational risks, social engineering attempts, or misinformation campaigns.
   - Providing recommendations and strategies to manage and enhance the organization's online reputation.


## 5. Competitive Intelligence and Market Research:
   - Monitoring competitors' activities, product launches, and market trends.
   - Gathering intelligence on competitors' strategies, partnerships, and potential threats to the organization's market position.
   - Providing insights and recommendations for strategic decision-making.


## 6. Supporting Due Diligence and Mergers & Acquisitions:
   - Conducting OSINT investigations on potential business partners, competitors, or acquisition targets.
   - Assessing risks, reputational issues, financial stability, and regulatory compliance of target organizations.
   - Providing intelligence reports to support informed decision-making in mergers and acquisitions processes.


## 7. Training and Awareness:
   - Developing and delivering training programs on OSINT tools, techniques, and best practices.
   - Educating employees on responsible online behavior, privacy protection, and social engineering awareness.


## 8. Collaboration and Information Sharing:
   - Working closely with internal teams such as incident response, threat intelligence, and legal departments.
   - Sharing relevant intelligence with relevant stakeholders within the organization and external partners or agencies when necessary.


---

# Job Roles Where OSINT Plays a Role


## 1. Cyber Threat Intelligence Analyst:
   - Leverages OSINT to gather information on threat actors, their tactics, techniques, and infrastructure.
   - Provides actionable intelligence to support proactive defense and incident response efforts.

## 2. Digital Forensics Investigator:
   - Utilizes OSINT to collect evidence, conduct investigations, and analyze digital artifacts.
   - Supports legal and incident response teams in digital crime investigations.

## 3. Fraud Analyst:
   - Utilizes OSINT techniques to gather information on potential fraudulent activities and actors.
   - Conducts investigations and identifies patterns to mitigate fraud risks.

## 4. Security Researcher:
   - Relies on OSINT to gather intelligence on emerging threats, vulnerabilities, and attack trends.
   - Contributes to vulnerability assessments, security advisories, and threat intelligence reports.

## 5. Vulnerability Management Specialist:
   - Utilizes OSINT to identify and assess vulnerabilities in systems, applications, and infrastructure.
   - Performs vulnerability scans, analyzes results, and provides recommendations for remediation.

## 6. Risk Analyst:
   - Utilizes OSINT to assess potential risks, including reputational, operational, and cybersecurity risks.
   - Conducts research on geopolitical factors, industry trends, and regulatory changes.

## 7. Due Diligence Investigator:
   - Leverages OSINT to gather information on companies, individuals, and business partners.
   - Conducts background checks, assesses reputational risks, and supports due diligence processes.

## 8. Market Research Analyst:
   - Utilizes OSINT to gather insights on market trends, customer preferences, and competitor activities.
   - Conducts competitive analysis and supports strategic decision-making.

## 9. Social Media Analyst:
   - Leverages OSINT techniques to monitor and analyze social media platforms for brand mentions, sentiment, and emerging trends.
   - Identifies potential reputation risks and supports social media marketing strategies.


---

# Conclusion

- This session aimed to provide an in-depth understanding of Open Source Intelligence (OSINT) and its importance for organizations.

- We explored the risks associated with an organization's online presence, including social engineering, phishing, and data breaches.

- We discussed best practices for defending against online attacks, such as using strong passwords, enabling two-factor authentication, etc. .

- We highlighted the importance of implementing policies and utilizing tools to protect against data leaks and enhance organizational security.

- By integrating OSINT into your organization, you can gather valuable intelligence, identify potential threats, and make informed decisions.

- Leveraging OSINT provides numerous benefits, including improved threat intelligence, enhanced situational awareness, and better decision-making.

- Remember to continuously educate your employees on the importance of online security and promote a culture of responsible online behavior.

- Stay updated on the latest advancements in OSINT techniques and tools to maximize its potential and strengthen your organization's security posture.

---

# Any Questions?


Slides are available at https://github.com/5A4B48/BSIDESKnoxville23OSINT
