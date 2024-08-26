# Border Gateway Protocol
- Routing protocol of the Internet
- Rising use in Datacenter Applications
  - EVPN (VxLAN)
- Used to replace Interior Protocols

![image](https://github.com/user-attachments/assets/31f44d21-3f8b-49ec-af72-ec6e67119ed2)

![image](https://github.com/user-attachments/assets/6fd1c180-0b66-4034-96b5-77a5284b40b3)

![image](https://github.com/user-attachments/assets/0e56a9a5-d916-4435-ba99-3b77c01c8c66)

![image](https://github.com/user-attachments/assets/aa94fa55-1707-4a1d-9b43-d4c003562667)

![image](https://github.com/user-attachments/assets/00e09e38-5216-4f25-b1ce-90d6a6c173c9)

![image](https://github.com/user-attachments/assets/5f9f3318-3b78-43a2-917b-ece64aebfac4)

![image](https://github.com/user-attachments/assets/f436c82d-b1a6-4841-928a-010868bdcc23)

- Only applies to 1 local router; not propagated to other routers

![image](https://github.com/user-attachments/assets/08a5778a-5436-43fa-93c4-f83e3c783152)

- Applies within the entire autonomous system (AS)

![image](https://github.com/user-attachments/assets/980f8849-f61e-44d7-bab0-17c09fd65528)

![image](https://github.com/user-attachments/assets/4140775c-f960-4337-b3cb-0a996c4bd478)

![image](https://github.com/user-attachments/assets/9b200279-ad2d-4fe6-a43e-ce703d40a3a1)

- IGP - Internal Gateway Protocol

![image](https://github.com/user-attachments/assets/ceaab025-1400-483f-84f6-56936462dafe)

- Accept MED or zero out MED because it is redistributed to IGP

![image](https://github.com/user-attachments/assets/2c2d2654-da4c-4f48-8dd0-7bb9d06444c8)

- Help to avoid possible loops

![image](https://github.com/user-attachments/assets/40bd337b-4aa1-48de-a294-5bcbd325965f)

![image](https://github.com/user-attachments/assets/e5430100-0516-46ef-9eb8-bb2752cf647c)

![image](https://github.com/user-attachments/assets/2e3e160f-0e41-4dc1-81dc-e7bf84bf8215)

![image](https://github.com/user-attachments/assets/4e06f574-2f49-44b9-bda8-c696fc135832)

![image](https://github.com/user-attachments/assets/4dec5213-e807-4be2-862e-e9f1711c15e1)

- Origin - IGP, EGP, or incomplete
- AS-Path - mandatory for loop avoidance
- Next-Hop - have to know where to send packets

Discretionary - are identified by all routers and Can be included
- Local Preference - 
- Atomic Aggregate - way to alert over BGP speakers that a route is summarized and a more specific path may be available




