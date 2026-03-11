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
# Evaluation of Prompting Techniques for Blockchain Text Summarization

## Aim
To evaluate and compare the effectiveness of prompting techniques (Zero-shot, Few-shot, Chain-of-Thought, Role-based) across different AI platforms such as **ChatGPT, Gemini, and Microsoft Copilot** in a text summarization task.

The evaluation focuses on the following criteria:

- Accuracy
- Coherence
- Simplicity
- Speed
- User Experience

---

# The Basics of Blockchain Technology: A Beginner’s Guide

Blockchain technology is often mentioned in connection with cryptocurrencies, but its potential extends far beyond digital money. At its core, blockchain is a revolutionary method of storing and sharing information securely, transparently, and without relying on a central authority.

## What is Blockchain?

Imagine a digital spreadsheet duplicated thousands of times across a network of computers. This network continuously updates and verifies every entry mathematically. This concept forms the basis of blockchain technology.

A **blockchain** is a **distributed ledger**, meaning a database that is shared, synchronized, and maintained across multiple participants and locations.

## How Blockchain Works

The name "blockchain" comes from two key components:

### Blocks
When new data enters the system, such as a financial transaction or medical record, it is grouped into a **block**. Each block contains:
- The data itself
- A **hash** (a unique digital fingerprint)
- The hash of the previous block

### Chain
Because each block contains the previous block's hash, they are **cryptographically linked** together in chronological order.

If someone attempts to alter the data inside a block, its hash changes. This breaks the connection with the next block and alerts the entire network about the tampering.

---

# Core Pillars of Blockchain

Understanding blockchain requires knowledge of three major principles:

### 1. Decentralization
Traditional databases are controlled by a central authority such as a bank or company. Blockchain distributes control among all users in the network called **nodes**.

### 2. Transparency
Although participants may remain anonymous, the ledger itself is visible to everyone in the network, allowing complete transaction history visibility.

### 3. Immutability
Once a block is verified and added to the blockchain, its data **cannot be altered or deleted**, creating a permanent record.

---

# Real-World Applications of Blockchain

Although blockchain became popular through Bitcoin, its applications extend into many industries.

### Supply Chain Management
Companies can track products from origin to consumer, ensuring authenticity and preventing fraud.

### Smart Contracts
Smart contracts are **self-executing digital agreements** written in code. When predefined conditions are met, actions such as payments are automatically executed.

### Healthcare
Blockchain allows hospitals and medical institutions to securely share patient records while maintaining privacy.

---

# The Bottom Line

Blockchain changes how digital trust is established. By replacing centralized control with cryptographic verification and distributed consensus, it creates a secure, transparent, and reliable system for managing transactions and data.

---

# Prompting Techniques Experiment

## 1. Zero-Shot Prompt

### Prompt
> "Summarize the provided text about blockchain technology in 100 words. Focus on defining what it is and its core pillars."

### Gemini Response
Blockchain is a decentralized distributed ledger technology that securely stores data across a network of computers. Instead of relying on a central authority, information is grouped into blocks that are cryptographically linked to form a permanent chain.

Core pillars include:

- **Decentralization** – Control is shared among network participants.
- **Transparency** – Transaction history is visible to the network.
- **Immutability** – Once verified, data cannot be changed.

This system enables secure applications such as smart contracts and supply chain tracking.

### ChatGPT Response
Blockchain is a distributed digital ledger that stores and shares information across a network of computers rather than a single central authority. Data is recorded in blocks containing transaction details and a unique hash. These blocks are linked together to form a chain.

Its core pillars are:

- Decentralization
- Transparency
- Immutability

These properties ensure that once data is verified and added to the blockchain, it cannot be altered.

### Copilot Response
Blockchain is a distributed ledger that securely records data across a network without central authority. Information is grouped into blocks containing unique hashes linked together into a chain.

Its three pillars are:

- Decentralization
- Transparency
- Immutability

These principles create a trustworthy system used in industries like supply chains, healthcare, and smart contracts.

---

# 2. Few-Shot Prompt

### Prompt
Summarize articles using a **Key Takeaway format**.

Example:
- AI → Key Takeaways: Machine Learning, Neural Networks
- Solar Power → Key Takeaways: Photovoltaic cells, Renewability

Task: Summarize the blockchain article using the same format.

### Gemini Response

Blockchain is a decentralized distributed ledger that securely records data across a global network. Information is grouped into blocks and cryptographically linked to form a permanent chain.

Core principles:

- Decentralization
- Transparency
- Immutability

This system allows trusted transactions without intermediaries.

### ChatGPT Response

**Summary**

Blockchain is a distributed digital ledger that records data across a network of computers without central authority. Blocks are linked using cryptographic hashes forming a secure chain.

**Key Takeaways**

- Decentralization
- Transparency
- Immutability
- Cryptographic Hashing
- Distributed Ledger

### Copilot Response

**Summary**

Blockchain is a decentralized ledger that records information across a network using cryptographic hashes. The system ensures transparency and tamper resistance.

**Key Takeaways**

- Decentralization
- Transparency
- Immutability

---

# 3. Chain-of-Thought Prompt

### Prompt Steps

1. Identify three technical components.
2. Identify three industries impacted.
3. Write a 100-word explanation of why blockchain is tamper-proof.

### Key Technical Components

- Cryptographic Hash
- Block Linking
- Consensus Mechanism

### Industries Impacted

- Supply Chain Management
- Healthcare
- Finance / Smart Contracts

### Summary

Blockchain is considered tamper-proof because each block contains a cryptographic hash and the hash of the previous block. If someone attempts to change the data inside a block, the hash changes and breaks the chain, alerting the network. Since the ledger is distributed across many computers, no single entity can secretly modify the records. Network consensus ensures that only verified transactions are added to the blockchain. These features create a transparent and secure system used in industries such as finance, supply chains, and healthcare to maintain reliable digital records.

---

# 4. Role-Based Prompt

### Prompt
Act as a **Senior Technical Recruiter** and summarize blockchain for a **non-technical candidate** focusing on business value.

### Gemini Response

Blockchain is a decentralized system that records data securely without relying on a central authority. Information is stored in blocks linked together through cryptography.

For businesses, the major benefits include transparency, trust, and elimination of intermediaries. Blockchain helps companies track supply chains, execute smart contracts automatically, and maintain secure records.

### ChatGPT Response

Blockchain is a secure system for recording and sharing information across many computers rather than relying on a central authority. Data stored in blocks cannot easily be changed once verified.

For businesses, this technology builds trust, reduces fraud, and improves transparency between partners. Industries like finance, healthcare, and supply chains use blockchain to streamline operations and ensure reliable record-keeping.

### Copilot Response

Blockchain is a decentralized technology that records and shares data securely across a network. Records are linked through cryptographic hashes making them permanent and transparent.

For businesses, blockchain improves trust, reduces fraud, and increases efficiency. Organizations use it to track supply chains, manage contracts, and securely store important information.

---

# Conclusion

This experiment compared four prompting techniques across multiple AI platforms.

Key findings:

- **Chain-of-Thought prompting** produced the most detailed and structured summaries.
- **Few-shot prompting** improved formatting and consistency.
- **Role-based prompting** generated summaries better suited for specific audiences.
- **Zero-shot prompting** was the fastest but sometimes less detailed.

Overall, **ChatGPT and Gemini produced the most coherent summaries**, while **Copilot provided concise business-focused outputs**.

Prompt engineering plays a crucial role in improving the quality of AI-generated summaries and should be carefully designed depending on the task and audience.

---

# References

1. Nakamoto, S. (2008). *Bitcoin: A Peer-to-Peer Electronic Cash System*
2. OpenAI Prompt Engineering Documentation
3. Blockchain Technology Research Articles



RESULT:
after testing four prompting techniques (**Zero-shot, Few-shot, Chain-of-Thought, and Role-based**) across multiple AI platforms such as **ChatGPT, Gemini, and Microsoft Copilot**, the outputs were evaluated using the following criteria:

- Accuracy  
- Coherence  
- Simplicity  
- Speed  
- User Experience  

### Zero-Shot Prompting
The **Zero-shot prompting technique** produced quick summaries with minimal instructions. All three platforms successfully defined blockchain and highlighted its core pillars. However, the summaries were sometimes less structured compared to other prompting methods. **Gemini** generated concise responses, while **ChatGPT** produced slightly more detailed explanations.

### Few-Shot Prompting
The **Few-shot prompting technique** improved the structure and consistency of the summaries. Because examples were provided in the prompt, the models followed the required format more effectively. **ChatGPT** performed particularly well by clearly separating the *summary* and *key takeaways*, while **Copilot** produced simple and easy-to-understand bullet points.

### Chain-of-Thought Prompting
The **Chain-of-Thought prompting technique** resulted in the most detailed and logically organized responses. By breaking the task into steps (technical components, industries impacted, and summary), the models demonstrated better reasoning and explanation. **ChatGPT and Gemini** both generated structured outputs that clearly explained why blockchain is considered *tamper-proof*.

### Role-Based Prompting
The **Role-based prompting technique** generated summaries tailored to a specific audience. By asking the AI to act as a **Senior Technical Recruiter**, the responses focused on the business value of blockchain rather than technical complexity. This method produced highly readable and professional summaries suitable for non-technical readers.

### Final Observation
Overall, **Chain-of-Thought prompting produced the most accurate and structured responses**, while **Role-based prompting generated the most audience-friendly summaries**. **Zero-shot prompting** was the fastest but slightly less detailed, and **Few-shot prompting** improved formatting consistency.

Among the platforms tested:

- **ChatGPT:** Best balance of clarity, detail, and structure  
- **Gemini:** Concise and fast outputs  
- **Microsoft Copilot:** Straightforward summaries focused on business value
