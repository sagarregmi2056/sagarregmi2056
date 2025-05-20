
<div align="center" style="background: linear-gradient(135deg, #1a1c2c 0%, #4a569d 100%); color: white; padding: 40px; border-radius: 20px; margin: 20px; min-height: 100vh; width: 100%;">

# <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="30px"> Hi, I'm Sagar Regmi

<div align="center" style="background: linear-gradient(135deg, #1a1c2c 0%, #4a569d 100%); padding: 20px; border-radius: 10px;">
  
  <!-- Custom badges with gradient backgrounds -->
  <a href="https://nodejs.org" target="_blank">
    <img src="https://img.shields.io/badge/Node.js-Developer-gradient?style=for-the-badge&logo=node.js&logoColor=white&labelColor=339933&color=000000"/>
  </a>
  <a href="https://solana.com" target="_blank">
    <img src="https://img.shields.io/badge/Solana-Developer-gradient?style=for-the-badge&logo=solana&logoColor=white&labelColor=14F195&color=000000"/>
  </a>
  <a href="https://ethereum.org" target="_blank">
    <img src="https://img.shields.io/badge/Ethereum-Developer-gradient?style=for-the-badge&logo=ethereum&logoColor=white&labelColor=3C3C3D&color=000000"/>
  </a>
  
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=28&duration=4000&pause=1000&color=61DAFB&center=true&vCenter=true&width=435&lines=Full+Stack+Developer;Blockchain+Developer;Smart+Contract+Expert;Web3+Innovator" alt="Typing SVG" />
  
  [![GitHub followers](https://img.shields.io/github/followers/sagarregmi2057?label=Follow&style=social)](https://github.com/sagarregmi2057)
  [![Linkedin: sagar-regmi](https://img.shields.io/badge/-Sagar%20Regmi-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/sagar-regmi-60b377216/)](https://www.linkedin.com/in/sagar-regmi-60b377216/)
</div>

<div align="center">
  <!-- Gradient line -->
  <img src="https://i.imgur.com/dBaSKWF.gif" height="20" width="100%">
</div>

<img align="right" alt="Coding" width="400" src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExNmZiMzM2ZTBkMzBmZGY5ZDM4NjQ2ZjM5NzY0NmM1NzM0ZmJiZjNlYiZlcD12MV9pbnRlcm5hbF9naWZzX2dpZklkJmN0PWc/qgQUggAC3Pfv687qPC/giphy.gif">

## 🚀 About Me

```javascript
const developer = {
    name: "Sagar Regmi",
    location: "Nepal",
    company: "TrustledgerAi.com",
    roles: [
        "Full Stack Developer",
        "Blockchain Developer",
        "Smart Contract Engineer"
    ],
    focus: [
        "Node.js",
        "React",
        "Solana",
        "Ethereum",
        "Rust",
        "Web3"
    ],
    currentLearning: "Zero Knowledge Proofs",
    funFact: "I debug smart contracts in my dreams"
};
```

<div align="center" style="background: linear-gradient(135deg, #1a1c2c 0%, #4a569d 100%); padding: 20px; border-radius: 10px;">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=sagarregmi2057&theme=radical&hide_border=true&background=0D1117&stroke=0D1117&ring=61DAFB&fire=61DAFB&currStreakLabel=61DAFB" alt="GitHub Streak Stats"/>
</div>

## 🛠️ Tech Stack

<div align="center">
  <!-- Blockchain & Web3 -->
  ![Solana](https://img.shields.io/badge/-Solana-000000?style=for-the-badge&logo=solana&logoColor=14F195)
  ![Ethereum](https://img.shields.io/badge/-Ethereum-000000?style=for-the-badge&logo=ethereum&logoColor=3C3C3D)
  ![Rust](https://img.shields.io/badge/-Rust-000000?style=for-the-badge&logo=rust&logoColor=B7410E)
  ![Web3.js](https://img.shields.io/badge/-Web3.js-000000?style=for-the-badge&logo=web3.js&logoColor=F16822)
  
  <!-- Full Stack -->
  ![Node.js](https://img.shields.io/badge/-Node.js-000000?style=for-the-badge&logo=node.js&logoColor=339933)
  ![React](https://img.shields.io/badge/-React-000000?style=for-the-badge&logo=react&logoColor=61DAFB)
  ![TypeScript](https://img.shields.io/badge/-TypeScript-000000?style=for-the-badge&logo=typescript&logoColor=3178C6)
  ![MongoDB](https://img.shields.io/badge/-MongoDB-000000?style=for-the-badge&logo=mongodb&logoColor=47A248)
  
  <!-- DevOps & Cloud -->
  ![Docker](https://img.shields.io/badge/-Docker-000000?style=for-the-badge&logo=docker&logoColor=2496ED)
  ![AWS](https://img.shields.io/badge/-AWS-000000?style=for-the-badge&logo=amazon-aws&logoColor=FF9900)
</div>

## 💻 Code Showcase

```rust
// Solana Program Example
#[program]
pub mod defi_protocol {
    use super::*;
    
    pub fn initialize_vault(ctx: Context<InitializeVault>) -> Result<()> {
        let vault = &mut ctx.accounts.vault;
        vault.authority = ctx.accounts.authority.key();
        vault.total_balance = 0;
        msg!("🚀 DeFi vault initialized successfully!");
        Ok(())
    }
}

// Smart Contract Example (Ethereum)
contract TokenVault {
    mapping(address => uint256) private balances;
    
    function deposit() public payable {
        balances[msg.sender] += msg.value;
        emit Deposit(msg.sender, msg.value);
    }
}

// Full Stack Integration
const initializeBlockchain = async () => {
    try {
        const connection = await setupConnection();
        const wallet = await connectWallet();
        return {
            success: true,
            message: "Blockchain connection established"
        };
    } catch (error) {
        console.error("Initialization failed:", error);
        throw error;
    }
};
```

## 💫 Performance Metrics

<div align="center" style="background: linear-gradient(135deg, #1a1c2c 0%, #4a569d 100%); padding: 20px; border-radius: 10px;">

```mermaid
%%{init: {'theme': 'base', 'themeVariables': { 'fontFamily': 'monospace', 'primaryColor': '#61DAFB', 'primaryTextColor': '#000000', 'lineColor': '#61DAFB', 'fontSize': '16px'}}}%%
graph LR
    A[API Response] -->|Optimization| B[<50ms]
    C[Database Queries] -->|Efficiency| D[<10ms]
    E[Frontend Load] -->|Performance| F[<2s]
    style A fill:#FFFFFF,stroke:#61DAFB,stroke-width:2px,color:#000000
    style B fill:#FFFFFF,stroke:#61DAFB,stroke-width:2px,color:#000000
    style C fill:#FFFFFF,stroke:#61DAFB,stroke-width:2px,color:#000000
    style D fill:#FFFFFF,stroke:#61DAFB,stroke-width:2px,color:#000000
    style E fill:#FFFFFF,stroke:#61DAFB,stroke-width:2px,color:#000000
    style F fill:#FFFFFF,stroke:#61DAFB,stroke-width:2px,color:#000000
```

</div>

## 🌟 Project Highlights

<div align="center">
  <table>
    <tr>
      <td align="center">
        <img src="https://img.shields.io/badge/DeFi-Protocol-14F195?style=for-the-badge&logo=solana" alt="DeFi"/>
        <br />
        "Smart contract solutions"
      </td>
      <td align="center">
        <img src="https://img.shields.io/badge/NFT-Marketplace-61DAFB?style=for-the-badge&logo=ethereum" alt="NFT"/>
        <br />
        "Web3 innovations"
      </td>
      <td align="center">
        <img src="https://img.shields.io/badge/Full--Stack-Apps-FF69B4?style=for-the-badge&logo=react" alt="Apps"/>
        <br />
        "Modern applications"
      </td>
    </tr>
  </table>
</div>

## 🎯 Current Focus

```mermaid
mindmap
  root((Developer))
    Blockchain
      Solana
      Ethereum
      Smart Contracts
    Backend
      Node.js
      Express
      MongoDB
    Frontend
      React
      Next.js
      TypeScript
    Web3
      DeFi
      NFTs
      DAOs
```

## 🎵 Development Playlist:

<div align="center">
```ascii
♪♫•*¨*•.¸¸♫•*¨*•.¸¸♪
🎧 Now Playing: Web3 Symphony in Full Stack Major
═══════════════════ ⠂▶
◄◄⠀▐▐⠀►►⠀⠀ ▇:𝟙𝟚:𝟛𝟘⠀►⠀∞:∞/∞:∞⠀⠀ ▌ ▌⠀⠀ ♫ ♪ ♫

🎼 Dev Playlist:
├── 01. Blockchain Beat
├── 02. Solana Sonata
├── 03. Ethereum Etude
├── 04. React Remix
└── 05. Node.js Nocturne
```
</div>

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=sagarregmi2057&label=Profile%20views&color=61DAFB&style=flat" alt="Profile views"/>
</div>

<div align="center">
  <sub>Built with ❤️ and 🦀 Rust | Powered by ⚡ Solana and 🌐 Web3 | Crafted by Sagar Regmi</sub>
</div>

</div>
