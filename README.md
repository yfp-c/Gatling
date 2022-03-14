## **Testing -**

### **Load Testing -**
- Standard performance testing technique
- Evaluates a system and its behaviour while exposed to a specific load, which is usually the expected volume of traffic 

### **Stress Testing -**
- Usually the next step after load test
- Aim is to assess the upper limits of the system by simulating an exceptional amount of traffic
- Provides info on the maximum capabiilities, scalability and breaking points of the product

### **Soak Testing -**
- Can be executed to assess whether memory leaks and performance degradation would by triggered by continuous usage
- System is exposed to a constant, average level of stress for an extended period

### **Spike Testing -**
- Simulates a sudden increase or decrease in the amount of users and transactions applied to a system
- This form of testing aims to assess whether the infrastructure is able to handle intense changes in load and that performance is maintained in fluctuating conditions.

## **SLO,SLI, and SLA -**

![sl](slo-vs-sla-vs-sli-1.jpg)

### **What is an SLA? -**
- An SLA (service level agreement) is an agreement between provider and client about measurable metrics like uptime, responsiveness, and responsibilities. 

### **The challenge of SLAs -**
- SLAs are notoriously difficult to measure, report on, and meet. These agreements—generally written by people who aren’t in the tech trenches themselves—often make promises that are difficult for teams to measure, don’t always align with current and ever-evolving business priorities, and don’t account for nuance. 
- For example, an SLA may promise that teams will resolve reported issues with Product X within 24 hours. But that same SLA doesn’t spell out what happens if the client takes 24 hours to send answers or screenshots to help your team diagnose the problem. Does it mean the team’s 24-hour window been eaten up by client slow-downs or does the clock start and stop based on when clients respond? SLAs need to answer these questions, but they often fail to do so—a fact that has created a lot of animosity toward them from IT managers.
- For many experts, the answer to this challenge is, first and foremost, that tech should be involved in the creation of SLAs. The more IT and DevOps collaborate with legal and business development to develop SLAs that address real-world scenarios, the more SLAs will start to reflect key realities, such as clients delaying their own issue resolution.

### **Who needs SLA? -**
- An SLA is an agreement between a vendor and a paying customer. Companies providing a service to users for free are unlikely to want or need an SLA for those free users.

### **What is an SLO? -**
- An SLO (service level objective) is an agreement within an SLA about a specific metric like uptime or response time. So, if the SLA is the formal agreement between you and your customer, SLOs are the individual promises you’re making to that customer. SLOs are what set customer expectations and tell IT and DevOps teams what goals they need to hit and measure themselves against.

### **The challenges of SLOs -**
- SLOs get less hate than SLAs, but they can create just as many problems if they’re vague, overly complicated, or impossible to measure. The key to SLOs that don’t make your engineers want to tear their hair out is simplicity and clarity. Only the most important metrics should qualify for SLO status, the objectives should be spelled out in plain language, and, as with SLAs, they should always account for issues such as client-side delays.

### **Who needs SLOs? -**
- Where SLAs are only relevant in the case of paying customers, SLOs can be useful for both paid and unpaid accounts, as well as internal and external customers. 
- Internal systems, such as CRMs, client data repositories, and intranet, can be just as important as external-facing systems. And having SLOs for those internal systems is an important piece of not only meeting business goals but enabling internal teams to meet their own customer-facing goals.

### **What is an SLI? -**
- An SLI (service level indicator) measures compliance with an SLO (service level objective). So, for example, if your SLA specifies that your systems will be available 99.95% of the time, your SLO is likely 99.95% uptime and your SLI is the actual measurement of your uptime. Maybe it’s 99.96%. Maybe 99.99%. To stay in compliance with your SLA, the SLI will need to meet or exceed the promises made in that document.

### **The challenges of SLIs -**
- As with SLOs, the challenge of SLIs is keeping them simple, choosing the right metrics to track, and not overcomplicating IT’s job by tracking too many metrics that don’t actually matter to clients.

### **Who needs SLIs? -**
- Any company measuring their performance against SLOs needs SLIs in order to make those measurements. You can’t really have SLOs without SLIs.