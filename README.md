

# 🗳️ Simple Decentralized Voting System (Solidity)

A beginner-friendly smart contract written in **Solidity** that demonstrates how a **voting system** can be built on the **Ethereum blockchain**.
It allows the contract owner to add candidates, start and end elections, and voters to securely cast their votes — all in a transparent, decentralized manner.

---

## 🚀 Features

* 🧑‍⚖️ **Owner-Controlled Election** – Only the deployer (owner) can add candidates or start/end the election.
* 🗳️ **One Voter, One Vote** – Prevents double voting using mappings.
* 🪪 **Transparent Results** – Anyone can view total votes and winner on-chain.
* 💡 **Beginner Friendly** – Clean code, no external dependencies, easy to understand.

---

## 🧩 Smart Contract Details

**Language:** Solidity
**Compiler Version:** `^0.8.20`
**License:** MIT

### Functions Overview

| Function                     | Description                                                |
| ---------------------------- | ---------------------------------------------------------- |
| `addCandidate(string _name)` | Owner adds a candidate before the election starts.         |
| `startElection()`            | Starts the election (only owner).                          |
| `vote(uint _candidateId)`    | Allows a voter to vote for a candidate once.               |
| `endElection()`              | Ends the election (only owner).                            |
| `getWinner()`                | Returns the name and total votes of the winning candidate. |

---

## 🧠 How It Works

1. **Deploy** the contract using the owner account.
2. **Add candidates** using `addCandidate("CandidateName")`.
3. **Start the election** using `startElection()`.
4. **Switch to different accounts** and **vote** using `vote(candidateId)`.
5. **End the election** using `endElection()`.
6. **Call `getWinner()`** to see the final result.

---

## ⚙️ Testing on Remix

1. Go to [Remix IDE](https://remix.ethereum.org)
2. Create a new file → `SimpleVoting.sol`
3. Paste the contract code
4. Compile with **Solidity 0.8.20**
5. Deploy → Interact with the contract using the steps above

---

## 🧾 Example Flow

```text
addCandidate("Alice")
addCandidate("Bob")
startElection()
vote(1)   // Voter 1 votes for Alice
vote(2)   // Voter 2 votes for Bob
endElection()
getWinner()
```

---

## 🔐 Future Improvements

* Add voter registration / whitelist system
* Include candidate descriptions & symbols
* Store results off-chain using IPFS
* Add a front-end (React + Web3.js or Ethers.js)

---

## 🪪 License

This project is licensed under the **MIT License** — free to use, modify, and share.

---

Would you like me to write a **short GitHub project description** and **tags** (for SEO visibility on your repo page)?
contract link- https://celo-sepolia.blockscout.com/address/0xb8BaD7394c40e0646C7A5e356CFd1212f1F8cE09

<img width="1470" height="956" alt="Screenshot 2025-10-29 at 4 27 14 PM" src="https://github.com/user-attachments/assets/28a5ab8b-5e21-486e-804b-66b5d19f8aba" />


