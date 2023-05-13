# Honeypot Assignment

**Time spent:** **5** hours spent in total

**Objective:** Create a honeynet using MHN-Admin. Present your findings as if you were requested to give a brief report of the current state of Internet security. Assume that your audience is a current employer who is questioning why the company should allocate anymore resources to the IT security team.

### MHN-Admin Deployment (Required)

**Summary:** I deployed the instances using GCP.

<img src="mhn-admin.gif">

### Dionaea Honeypot Deployment (Required)

**Summary:**  Dionaea serves as a decoy designed to attract potential attackers, gather information about their tactics, and enhance overall cybersecurity by learning from their activities.

<img src="dionaea-honeypot.gif">

### Database Backup (Required) 

**Summary:** MHN-Admin uses MongoDB, a NoSQL database system, to store and retrieve information. The uploaded JSON file records timestamps and source IP addresses.

## Notes

The challenges I encountered include setting up the honeypots in GCP; it took me the most time since I had to run the scripts provided several times.

