# Phishing Incident Response; Using a Playbook
<h1>Description</h1>

In this activity, I will respond to a phishing incident that involves a malicious file hash. This is the same SHA256 file hash that I investigated and verified as malicious in a 
[Suspicious File Hash Investigation](https://github.com/malikaii99/Phishing-Incident-Response/blob/4e0ec96574c799ebc5b5882ef4aa5d1bf688563f/Phishing%20incident%20response%20playbook.docx). I'll follow playbook instructions to investigate and resolve the incident's alert ticket.

A playbook can help security teams minimize the impact of an incident and reduce the incident response time. As a security analyst, playbooks can help guide you to effectively support an organization's incident response efforts.

<h2>Scenario</h2>

Review the scenario. Then complete the step-by-step instructions

You are a level-one security operations center (SOC) analyst at a financial services company. Previously, you received a phishing alert about a suspicious file being downloaded on an employee's computer. After investigating the email attachment file's hash, the attachment has already been verified malicious. Now that you have this information, you must follow your organization's process to complete your investigation and resolve the alert.

Your organization's security policies and procedures describe how to respond to specific alerts, including what to do when you receive a phishing alert. 

In the playbook, there is a flowchart and written instructions to help you complete your investigation and resolve the alert. At the end of your investigation, you will update the alert ticket with your findings about the incident.
Your task is to review the IT manager’s scope, goals, and risk assessment. Then, perform an internal audit to complete a control assessment and compliance checklist. 

- <a> Required Documents </a>
  - [Playbook](https://github.com/malikaii99/Phishing-Incident-Response/blob/4e0ec96574c799ebc5b5882ef4aa5d1bf688563f/Phishing%20incident%20response%20playbook.docx)

  
<h2> Summary</h2>

The alert indicated that an employee had downloaded and opened a suspicious file from a phishing email. Notably, there were inconsistencies among the sender's email address, which was "76tguy6hh6tgftrt7tg.su," the name mentioned in the email body, which was "Clyde West," and the sender's claimed name, "Def Communications." The email exhibited grammatical errors in both its body and subject line. Of particular concern was the presence of a password-protected attachment labeled "bfsvc.exe," which the user downloaded and accessed on the affected machine. Our previous investigation revealed that the file hash of this attachment is associated with a known malicious file. Additionally, the alert's severity rating was categorized as medium. Given these significant findings, I decided to escalate this issue to a level-two SOC analyst for further action and investigation.
