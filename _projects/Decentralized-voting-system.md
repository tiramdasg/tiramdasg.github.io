---
name: Blockchain-based Decentralized Voting System
tools: [Angular, HTML, SCSS/CSS, TypeScript, MySQL, Nodejs, Ganache, Solidity, Truffle, Ethereum, Web3.0, GCP (Google Cloud Platform), Docker]
image: ../assets/images/decentralized-architechture.png
style: fill
color: info
description: A decentralised voting system using blockchain smart contracts. Part of the Project Based Learning module of the Advanced Internet Computing course at the TUHH, SoSe, 2023.
---

# Blockchain-based Decentralized Voting System

Within this project, the goal is to implement a decentralized, high-availability voting system using smart contracts on a private Ethereum blockchain. 
The system should be able to authenticate users, register them for voting on the network, handle the actual voting process and finally provide 
the results to an administrator. Each voting session has to be initiated by an administrator, who registers the election candidates in the system and also sets the duration of the election campaign. The system needs to be set up as a Web app that has two frontends: one for the voters and one for the administrator.

The architechture looks like follows:

![architechture](../assets/images/decentralized-architechture.png)

## Design Decisions

We made the following design decisions <br>
1. Authentication process for the users: Voter ID, Email, Password, OTP, Admin Approval<br>
![auth](../assets/images/decentral-auth.png)
2. Storing user and candidate information: user data is stored on MySQL database; candidate data is stored on blockchain.<br>
![mysql](../assets/images/mysql.png) ![ethereum](../assets/images/ethereum.png)
3. Preventing voters from voting more than once: handled in the smart contract. Upon reset (repetition of election), voter will be able to vote again<br>
![solidity](../assets/images/solidity.png)
4. Preserving privacy and fairness: Votes cannot be seen by anyone, only a transaction hash is generated. Handled in the smart contracts.<br>
![blockchain](../assets/images/blockchain.png)
5. Each user assigned with a wallet: The list of address from Ganache are obtained and assigned automatically to each user in the backend.<br>
![ganache](../assets/images/ganache.png)
6. Functionalities in the smart contract:
    - Add candidates
    - Start and Stop Election
    - Cast Vote
    - Get Statistics
    - Reset to restart the Election
<br><img src="../assets/images/smart-contract.jpg" alt="smart-contract" width="80">
7. Number of Docker containers used: 3
    - Frontend
    - Database
    - Backend
<br>
![docker](../assets/images/docker.png)
8. Google Cloud Platform Service<br>
![auth](../assets/images/gcp.png)


## My Contributions
As the team coordinator, I gained valuable leadership experience. I discovered my ability to effectively coordinate with team members, assign tasks, resolve conflicts, and motivate the team. Additionally, I was adept at identifying and addressing any issues that arose. My contributions included developing the user interface and assisting with backend and blockchain development.

<p class="text-center">
{% include elements/button.html link="https://github.com/tiramdasg/Blockchain-Decentralised-Voting.git" text="See the Project" %}
</p>