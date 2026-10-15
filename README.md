# Hi, I'm Josh

<a href="https://www.linkedin.com/in/joshua-wilson-a270b9269/"><img src="https://img.shields.io/badge/-LinkedIn-0072b1?&style=for-the-badge&logo=linkedin&logoColor=white" /></a>

Security analyst working where AI meets governance. I build the controls that make AI agents accountable: non-human identity, least privilege, immutable evidence, and a trail that ties every action back to the agent that took it.

## What I do

I'm the sole information security analyst at a regulated financial institution, where I:
- Built the AI agent governance program on the NIST AI RMF (intake, risk assessment, design records, exception register)
- Lead third-party risk management
- Own security awareness and training
- Cover blue team operations and support regulatory exam preparation

My focus is **AI GRC engineering**: turning governance requirements into technical controls that actually run, and proving they work.

## Featured project

### [Attributable AI Agent](https://github.com/CyberneticJosh96/attributable-ai-agent)
A read-only AI agent on Microsoft Foundry that answers security questions from tamper-proof data, holds no secrets, and leaves a trail tying every read back to it.
- Secretless collector under a managed identity, writing to immutable storage
- Published agent with its own Entra agent identity and federated credential
- Negative-tested: denied before access, writes refused, planted prompt injection blocked
- **Finding:** the agent's tool authenticated as a shared resource identity, so per-agent attribution required correlating traces with storage logs

## Other projects

| Project | What it is |
| --- | --- |
| KRI Collection Agent (Microsoft 365 Copilot) | An AI agent to automate key risk indicator collection across the Microsoft environment, replacing a manual process that depended on a single analyst. Includes data source mapping, least privilege service account design, agent operating constraints, and output validation against the manual baseline |
| AI Governance Document Set | Templates that can be used to govern AI systems: agent design records, a centralized agent inventory, a requirements exception register with risk acceptance and review dates, and an agent security assessment checklist covering identity, attribution, data handling, and human review checkpoints |
| Active Directory Homelab | Windows Server domain with DHCP and RAS/NAT, simulating an enterprise environment |


## Tools

### AI and cloud
<div>
  <img src="https://img.shields.io/badge/-Microsoft_Foundry-0078D4?&style=for-the-badge&logo=microsoft&logoColor=white" />
  <img src="https://img.shields.io/badge/-Microsoft_Azure-0078D4?&style=for-the-badge&logo=microsoftazure&logoColor=white" />
  <img src="https://img.shields.io/badge/-Microsoft_Entra_ID-0078D4?&style=for-the-badge&logo=microsoft&logoColor=white" />
  <img src="https://img.shields.io/badge/-Logic_Apps-0062AD?&style=for-the-badge&logo=microsoft&logoColor=white" />
  <img src="https://img.shields.io/badge/-Defender_for_Cloud-00A4EF?&style=for-the-badge&logo=microsoft&logoColor=white" />
</div>

### SIEM and detection
<div>
  <img src="https://img.shields.io/badge/-Microsoft_Sentinel-0078D4?&style=for-the-badge&logo=microsoft&logoColor=white" />
  <img src="https://img.shields.io/badge/-KQL-0078D4?&style=for-the-badge&logo=microsoft&logoColor=white" />
  <img src="https://img.shields.io/badge/-Splunk-000000?&style=for-the-badge&logo=splunk&logoColor=white" />
</div>

### Endpoint and network
<div>
  <img src="https://img.shields.io/badge/-Defender_for_Endpoint-00A4EF?&style=for-the-badge&logo=microsoft&logoColor=white" />
  <img src="https://img.shields.io/badge/-Velociraptor-4B275F?&style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/-Wireshark-1679A7?&style=for-the-badge&logo=wireshark&logoColor=white" />
  <img src="https://img.shields.io/badge/-Suricata-EF3B2D?&style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/-Zeek-777BB4?&style=for-the-badge&logoColor=white" />
</div>

### Frameworks
<div>
  <img src="https://img.shields.io/badge/-NIST_AI_RMF-333333?&style=for-the-badge" />
  <img src="https://img.shields.io/badge/-NIST_CSF-333333?&style=for-the-badge" />
  <img src="https://img.shields.io/badge/-OWASP_LLM_Top_10-000000?&style=for-the-badge&logo=owasp&logoColor=white" />
</div>

## Certifications
<div>
  <img src="https://img.shields.io/badge/-CompTIA_Security%2B-C8202F?&style=for-the-badge&logo=comptia&logoColor=white" />
  <img src="https://img.shields.io/badge/-CompTIA_Network%2B-C8202F?&style=for-the-badge&logo=comptia&logoColor=white" />
  <img src="https://img.shields.io/badge/-CompTIA_CySA%2B-C8202F?&style=for-the-badge&logo=comptia&logoColor=white" />
  <img src="https://img.shields.io/badge/-Splunk_Core_Certified_Power_User-000000?&style=for-the-badge&logo=splunk&logoColor=white" />
  <img src="https://img.shields.io/badge/-Microsoft_Certified:_Azure_Fundamentals_(AZ--900)-0089D6?&style=for-the-badge&logo=microsoft&logoColor=white" />
</div>
