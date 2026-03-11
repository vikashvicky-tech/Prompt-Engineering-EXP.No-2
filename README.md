EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

AIM:

To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

SCENARIO:

You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:

1.Accuracy

2.Coherence

3.Simplicity

4.Speed

5.User experience

OUTPUT:
The Basics of Blockchain Technology: A Beginner’s Guide
Blockchain technology is often mentioned in the same breath as cryptocurrencies, but its potential extends far beyond digital money. At its core, blockchain is a revolutionary way of storing and sharing information securely, transparently, and without the need for a central authority.
What is a Blockchain?
Imagine a digital spreadsheet that is duplicated thousands of times across a network of computers. Then, imagine that this network is designed to regularly update this spreadsheet, mathematically verifying every single entry. That is the fundamental concept of a blockchain. It is a distributed ledger—a database that is shared, synchronized, and agreed upon across multiple locations and participants.
How Does It Work?
To understand the mechanics, it helps to break down the name itself: "block" and "chain."
The Blocks: Whenever new data is entered into the system (like a financial transaction or a medical record), it is grouped together into a "block." This block contains the specific data, a unique mathematical identifier called a "hash" (similar to a digital fingerprint), and the hash of the block that immediately preceded it.
The Chain: Because each block contains the previous block's hash, they are cryptographically linked together in chronological order, forming a continuous chain.
If someone attempts to tamper with the data in a specific block, that block's hash changes. This breaks the mathematical connection to the subsequent block, immediately signaling to the entire network that an unauthorized alteration has occurred.
Blockchain Core Pillars of 
Understanding blockchain requires grasping three main principles:
Decentralization: Traditional databases are typically owned and maintained by a single, central entity, like a bank or a tech company. A blockchain has no central authority. Instead, control and maintenance are distributed among all the users (called "nodes") on the network.

Shutterstock
Transparency: While individual participants can remain anonymous, the ledger itself is entirely public to the network. Anyone on that network can view the entire history of transactions, ensuring complete visibility.
Immutability: Once a block is verified by the network (through processes known as "consensus mechanisms") and added to the chain, its contents cannot be altered, reversed, or deleted. This creates an unshakeable, permanent record.
Beyond Cryptocurrency: Real-World Applications
While Bitcoin introduced blockchain to the world, the underlying technology is being adopted across various industries to solve complex problems:
Supply Chain Management: Companies can track products step-by-step from their origin to the consumer, verifying authenticity, ensuring ethical sourcing, and preventing fraud.
Smart Contracts: These are self-executing digital contracts where the terms of the agreement are written directly into code. They automatically trigger actions (like releasing a payment) when predefined conditions are met, eliminating the need for lawyers or escrow agents.
Healthcare: Medical networks are exploring blockchain to securely store patient records, allowing different hospitals to share critical data instantly while maintaining strict privacy standards.
The Bottom Line
Blockchain technology fundamentally shifts how we establish trust in the digital world. By replacing centralized control with cryptographic proof and distributed consensus, it offers a secure, transparent, and highly resilient way to handle data and transactions

1.	Zero-Shot Prompt:
Prompt:
"Summarize the provided text about blockchain technology in 100 words. Focus on defining what it is and its core pillars."

Gemini:
Blockchain Summary
Blockchain is a decentralized, distributed ledger technology that securely stores data across a global network of computers. Instead of relying on a central authority like a bank, it groups information into "blocks" that are cryptographically linked to form a permanent "chain."
 
Getty Images
Its foundation rests on three core pillars:
•	Decentralization: Control is spread across all users (nodes) rather than a single entity.
•	Transparency: The entire transaction history is visible to the network.
•	Immutability: Once verified, data cannot be altered or deleted.
This creates a high-trust environment, enabling secure applications ranging from smart contracts to supply chain tracking.

ChatGPT:
Blockchain is a distributed digital ledger that stores and shares information across a network of computers rather than a single central authority. Data is recorded in blocks, each containing transaction details and a unique hash, and these blocks are linked together to form a chain. This structure ensures that any attempt to alter data is immediately detected. Blockchain is built on three core pillars. Decentralization means control is shared among network participants (nodes) instead of a central organization. Transparency allows all participants to view the transaction history on the network. Immutability ensures that once data is verified and added to the blockchain, it cannot be changed or deleted.

Copilot:
Blockchain is a distributed ledger technology that securely records and shares data across a network without central authority. It works by grouping information into “blocks,” each containing a unique hash and the hash of the previous block, forming a tamper-proof “chain.” Its three core pillars are decentralization (no single owner, all nodes share control), transparency (the ledger is visible to all participants), and immutability (once verified, data cannot be altered). Together, these principles ensure trust, security, and resilience, making blockchain valuable beyond cryptocurrency in areas like supply chains, healthcare, and smart contracts.

2.	Few-Shot Prompt:
Prompt:
"I want you to summarize articles using a 'Key Takeaway' format.
Example 1: [Text about AI] -> Summary: AI mimics human intelligence to solve problems. Key Takeaways: Machine Learning, Neural Networks, Automation. Example 2: [Text about Solar Power] -> Summary: Solar power converts sunlight into energy. Key Takeaways: Photovoltaic cells, Renewability, Grid storage.
Task: Summarize the following text about Blockchain using this exact format: "

Gemini:
Blockchain is a decentralized, distributed ledger that securely records data across a global network. It functions by grouping information into "blocks" that are cryptographically linked using unique hashes to form a permanent, chronological "chain."
Its architecture is built on three core pillars:
•	Decentralization: Control is distributed among all network participants (nodes) rather than a single central authority.
•	Transparency: The entire transaction history is visible to all network members.
•	Immutability: Once verified, data cannot be altered or deleted, ensuring an unshakeable record.
This framework enables trust without intermediaries, impacting industries from finance to healthcare.
ChatGPT:
Summary:
Blockchain is a distributed digital ledger that records and shares data across a network of computers without relying on a central authority. Information is stored in blocks that are linked together using cryptographic hashes, forming a secure and chronological chain. This structure ensures that any attempt to modify stored data is easily detected by the network.
Key Takeaways:
Decentralization, Transparency, Immutability, Cryptographic Hashing, Distributed Ledger.
Copilot:
Summary:
Blockchain is a decentralized, distributed ledger that securely records and shares data across a network. It links blocks of information using cryptographic hashes, making the system tamper-resistant and transparent. Once verified, data cannot be altered, ensuring trust and permanence without a central authority.
Key Takeaways:
•	Decentralization: No single controlling entity; nodes share responsibility.
•	Transparency: Ledger is visible to all participants.
•	Immutability: Verified data cannot be changed or deleted
3. Chain-of-Thought (CoT) Prompt
Prompt:
"Read the text about blockchain.
1.	First, list the three most important technical components mentioned.
2.	Second, identify three real-world industries it impacts.
3.	Finally, using those points, write a 100-word summary that explains why blockchain is considered 'tamper-proof.'"
Gemini:

Technical Components and Industry Impact
Based on the text, here are the primary technical elements and the sectors being transformed by this technology:
Three Key Technical Components:
1.	The Hash: A unique mathematical identifier that acts like a digital fingerprint for each block.
2.	Cryptographic Linking: The process of including the previous block's hash in the current one to create an unbroken chain.
3.	Consensus Mechanisms: The network-wide verification process that must occur before any new data is permanently added.
Three Impacted Industries:
1.	Supply Chain Management: For tracking product authenticity and ethical sourcing.
2.	Legal/Finance (Smart Contracts): For self-executing agreements that trigger automatically.
3.	Healthcare: For the secure and instant sharing of patient records between providers.
________________________________________
Why Blockchain is Tamper-Proof
Blockchain is considered "tamper-proof" due to its cryptographic linking and decentralized verification. Each block contains a unique hash plus the hash of the preceding block, creating a mathematical dependency. If data within a block is altered, its hash changes instantly, breaking the connection to the rest of the chain and alerting the entire network.
Because the ledger is decentralized, no single entity controls the data. For an edit to be accepted, the majority of the network must reach consensus, making unauthorized, permanent alterations virtually impossible to execute.
ChatGPT:
1. Three Most Important Technical Components
•	Blocks and Chain Structure – Data is stored in blocks that are linked together chronologically to form a chain.
•	Cryptographic Hashing – Each block contains a unique hash and the hash of the previous block, creating a secure link.
•	Distributed Ledger (Decentralized Network/Nodes) – The database is shared and synchronized across many computers in the network.
2. Three Real-World Industries Impacted
•	Finance and Cryptocurrency
•	Supply Chain Management
•	Healthcare
3. 100-Word Summary
Blockchain is considered tamper-proof because of its secure structure and distributed design. Data is stored in blocks, and each block contains a cryptographic hash and the hash of the previous block, linking them together in a chain. If someone tries to alter the data in one block, its hash changes and breaks the connection with the next block, immediately alerting the network. In addition, the ledger is distributed across many computers, so no single authority controls it or can secretly modify records. These features create a transparent and immutable system used in industries such as finance, supply chain management, and healthcare to store and verify information securely.
Copilot:
Step 1 – Technical Components:
•	Blocks (data + hash + previous hash)
•	Chain (cryptographic linking of blocks)
•	Consensus mechanisms (network verification process)
Step 2 – Real-World Industries Impacted:
•	Supply Chain Management
•	Smart Contracts (legal/financial services)
•	Healthcare
Step 3 – 100-Word Summary:
Blockchain is considered tamper-proof because of its unique technical design. Data is grouped into blocks, each containing a hash and the hash of the previous block, forming a secure chain. Any attempt to alter a block changes its hash, breaking the chain and alerting the network. Consensus mechanisms ensure that only verified data is added, preventing unauthorized changes. This structure guarantees immutability, transparency, and decentralization. Industries like supply chain management, healthcare, and legal services use blockchain to maintain trust, authenticity, and security, proving its resilience against fraud and manipulation in real-world applications.
4. Role-Based Prompt
Prompt:
"Act as a Senior Technical Recruiter. Summarize this blockchain article for a candidate who is applying for a non-technical role. The summary should be professional, exactly 100 words, and emphasize the 'bottom line' value of the technology for a business."
Gemini:
Gemini said
Senior Recruiter’s Summary: Blockchain Fundamentals
Blockchain is a decentralized, distributed ledger that transforms how businesses establish digital trust. Unlike traditional databases, it groups information into "blocks" that are cryptographically linked, creating a chronological "chain."
The business value rests on three pillars: decentralization, which removes costly intermediaries; transparency, providing a visible audit trail; and immutability, ensuring data cannot be altered once verified.
The Bottom Line: By replacing centralized control with cryptographic proof and network consensus, blockchain offers a secure, resilient framework for complex operations like supply chain tracking and self-executing smart contracts, driving unprecedented operational integrity.
ChatGPT:
Blockchain is a secure digital system for recording and sharing information across many computers instead of relying on a single central authority. Data is stored in connected blocks that cannot easily be altered once verified, creating a reliable and transparent record of transactions. For businesses, the key value lies in building trust, reducing fraud, and improving transparency between partners without requiring intermediaries. This technology can streamline operations in industries such as finance, supply chain, and healthcare by enabling accurate tracking, automated agreements, and secure data sharing. Ultimately, blockchain helps organizations operate more efficiently while maintaining accountability, data integrity, and stronger confidence in digital transactions.

Copilot:
Blockchain is a secure, decentralized system for recording and sharing information across a network without a central authority. It works by linking blocks of data through cryptographic hashes, making records transparent, permanent, and resistant to tampering. For businesses, the bottom line is trust: blockchain ensures data integrity, reduces fraud, and streamlines processes. Industries like supply chain management, healthcare, and financial services already leverage it to improve transparency, efficiency, and compliance. By replacing traditional intermediaries with distributed consensus, blockchain offers organizations a resilient, cost-effective way to manage transactions and information in today’s digital economy. (100 words)



RESULT:
