# Smart Contract Diagram

<figure><img src="../../.gitbook/assets/Blank diagram (2).png" alt=""><figcaption></figcaption></figure>

*   **Course Token**

    This smart contract is the NFT itself that represents the course as a token. Each NFT can have multiple copies of itself which is created via minting. Each of these NFTs has its own attributes like URI to locate the course material for talents to use.
*   **Course Token Factory**

    The course token factory will be called by IGS Admins in this current stage to create new NFT tokens. This token factory will do the deployment of new smart contracts and will keep track of all the NFTs that have been created.
*   **Course Token Event**

    This smart contract is a helper to the course token smart contract that emits events when major events have occurred in the NFT. It can be a tool for IGS as well as other stakeholders to get information about updates and changes.
*   **Talent Match**

    The talent match smart contract will be used as a queue system for processing the hiring system. When talent and company are starting their hiring process, IGS will create a ticket where a talent match process is created. After the company hires the talent, the talent matching is confirmed and the smart contract will receive the fees and distribute the funds accordingly.
