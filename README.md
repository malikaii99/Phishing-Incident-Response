# Phishing Incident Response; Using a Playbook
<h1>Description</h1>

A security audit will be done on Botium Toys to align their operational practices with industry standards and best practices. The audit will assess the company's adherence to cybersecurity norms, identify potential gaps, and enhance the overall security posture of the organization.

<h2>Scenario</h2>

This scenario is based on a fictional company:

Botium Toys is a small U.S. business that develops and sells toys. The business has a single physical location. However, its online presence has grown, attracting customers in the U.S. and abroad. Their information technology (IT) department is under increasing pressure to support their online market worldwide. 

The manager of the IT department has decided that an internal IT audit needs to be conducted. She expresses concerns about not having a solidified plan of action to ensure business continuity and compliance as the business grows. She believes an internal audit can help better secure the company’s infrastructure and help them identify and mitigate potential risks, threats, or vulnerabilities to critical assets. The manager is also interested in ensuring that they comply with regulations related to accepting online payments and conducting business in the European Union (EU).

The IT manager starts by implementing the National Institute of Standards and Technology Cybersecurity Framework (NIST CSF), establishing an audit scope and goals, and completing a risk assessment. The goal of the audit is to provide an overview of the risks the company might experience due to the current state of their security posture. The IT manager wants to use the audit findings as evidence to obtain approval to expand his department. 

Your task is to review the IT manager’s scope, goals, and risk assessment. Then, perform an internal audit to complete a control assessment and compliance checklist. 

- <a> Required Documents </a>
  - [Playbook](https://github.com/malikaii99/Security-Audit-Botium-Toys/blob/e0549c8f436c765d70ff8ecd57e45f92ade54da8/IT%20Email%20SS.png)


  
<h2> Summary</h2>

The alert indicated that an employee had downloaded and opened a suspicious file from a phishing email. Notably, there were inconsistencies among the sender's email address, which was "76tguy6hh6tgftrt7tg.su," the name mentioned in the email body, which was "Clyde West," and the sender's claimed name, "Def Communications." The email exhibited grammatical errors in both its body and subject line. Of particular concern was the presence of a password-protected attachment labeled "bfsvc.exe," which the user downloaded and accessed on the affected machine. Our previous investigation revealed that the file hash of this attachment is associated with a known malicious file. Additionally, the alert's severity rating was categorized as medium. Given these significant findings, I decided to escalate this issue to a level-two SOC analyst for further action and investigation.
