# DevSecOps Interview Questions

A curated list of DevSecOps interview questions across key focus areas: security, automation, cloud, containers, and incident response.

---

## 🔐 Security Fundamentals

1. What is the principle of least privilege and how do you apply it in practice?
2. How do you perform threat modeling during the development lifecycle?
3. Can you explain the OWASP Top 10 and how you mitigate those risks in DevSecOps workflows?
4. How do you handle secrets in a CI/CD pipeline?
5. What’s your approach to auditing and rotating secrets/keys/tokens?

---

## ⚙️ CI/CD & Automation

6. How do you integrate static (SAST) and dynamic (DAST) security testing into CI/CD pipelines?
7. What tools do you use to manage vulnerability scanning in your pipelines?
8. How would you ensure that a build pipeline fails if a critical vulnerability is detected?
9. Can you describe a secure deployment workflow from code commit to production?
10. How do you secure CI/CD tools themselves (e.g., Jenkins, GitHub Actions)?

---

## ☁️ Cloud Security & Infrastructure as Code

11. How do you secure cloud infrastructure deployed via Terraform or CloudFormation?
12. What tools do you use for Infrastructure as Code scanning and compliance checks?
13. What are Cloud Security Posture Management (CSPM) tools, and have you used any?
14. Explain the shared responsibility model in the context of AWS/Azure/GCP.
15. How would you handle a scenario where a misconfigured S3 bucket was publicly exposed?

---

## 🐳 Container & Kubernetes Security

16. What tools do you use to scan container images for vulnerabilities?
17. How do you secure Kubernetes clusters in a production environment?
18. What are Kubernetes network policies and how do they enhance security?
19. How would you detect and respond to suspicious behavior in a running pod?
20. Can you explain how you handle pod security policies and runtime security (e.g., using Falco)?

---

## 💣 Incident Response & Real-world Scenarios

21. A developer accidentally commits a secret to GitHub. Walk me through your incident response.
22. Describe a time when you found a security flaw in production. What did you do?
23. How do you monitor for lateral movement or privilege escalation attempts in your infrastructure?
24. What would you do if a container in production starts behaving unusually?
25. What’s your process for post-incident reviews and implementing long-term fixes?

---

Feel free to contribute more questions or suggest improvements via pull requests!
