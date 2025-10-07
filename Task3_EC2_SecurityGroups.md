# 🧠 Task 3: AWS EC2 & Security Groups - Cheat Sheet
## Week 1 - 90 Days of DevOps

---

### 🚀 Launch EC2 Instance (Free Tier)

1. **Login to AWS Console** → Services → EC2  
2. **Launch Instance**  
   - Choose AMI (Amazon Linux 2)  
   - Instance Type: t2.micro (Free Tier)  
3. **Configure Instance Details** → Defaults OK for learning  
4. **Add Storage** → 8 GB default  
5. **Add Tags** → Optional (Name tag)  

---

### 🔐 Configure Security Groups

1. **Create Security Group** → Name + Description  
2. **Add Inbound Rules**  
   | Protocol | Port | Source |  
   |----------|------|--------|  
   | SSH      | 22   | Your IP / Anywhere (0.0.0.0/0 for learning) |  
   | HTTP     | 80   | Anywhere |  
   | HTTPS    | 443  | Anywhere |  
3. **Outbound Rules** → Default allows all (no change needed)  
4. **Review & Launch** → Select/create Key Pair → Launch  

---

### 🔑 Key Points

- Security Groups are **stateful**  
- Multiple rules can be added per group  
- Only open required ports (avoid 0.0.0.0/0 in production)  
- Can attach one or more groups to an EC2 instance  

---

### ✅ Learning Outcome
- Launched EC2 instance (free tier)  
- Created & configured Security Groups  
- Learned inbound/outbound traffic rules  
- Understood which ports/protocols are needed for secure access  

---

#AWS #EC2 #SecurityGroups #CloudSecurity #90DaysOfDevOps
