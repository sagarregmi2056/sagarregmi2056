
# <div align="center"><img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="30px"> Hi, I'm Sagar Regmi</div>

<div align="center">
  
  <!-- Custom badges with gradient backgrounds -->
  <a href="https://solana.com" target="_blank">
    <img src="https://img.shields.io/badge/Solana-Developer-gradient?style=for-the-badge&logo=solana&logoColor=white&labelColor=14F195&color=000000"/>
  </a>
  <a href="https://www.rust-lang.org/" target="_blank">
    <img src="https://img.shields.io/badge/Rust-Expert-gradient?style=for-the-badge&logo=rust&logoColor=white&labelColor=B7410E&color=000000"/>
  </a>
  
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=28&duration=4000&pause=1000&color=14F195&center=true&vCenter=true&width=435&lines=Solana+Developer;Rust+Enthusiast;Web3+Innovator;Blockchain+Architect" alt="Typing SVG" />
  
  [![GitHub followers](https://img.shields.io/github/followers/sagarregmi2057?label=Follow&style=social)](https://github.com/sagarregmi2057)
  [![Linkedin: sagar-regmi](https://img.shields.io/badge/-Sagar%20Regmi-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/sagar-regmi-60b377216/)](https://www.linkedin.com/in/sagar-regmi-60b377216/)
</div>

<div align="center">
  <!-- Gradient line -->
  <img src="https://i.imgur.com/dBaSKWF.gif" height="20" width="100%">
</div>

<img align="right" alt="Coding" width="400" src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExNmZiMzM2ZTBkMzBmZGY5ZDM4NjQ2ZjM5NzY0NmM1NzM0ZmJiZjNlYiZlcD12MV9pbnRlcm5hbF9naWZzX2dpZklkJmN0PWc/qgQUggAC3Pfv687qPC/giphy.gif">

## 🚀 About Me

```rust
struct Developer {
    name: String,
    location: String,
    company: String,
    role: String,
    focus: Vec<String>,
    current_learning: String,
    fun_fact: String
}

impl Developer {
    fn new() -> Self {
        Developer {
            name: String::from("Sagar Regmi"),
            location: String::from("Germany"),
            company: String::from("TrustledgerAi.com"),
            role: String::from("Solana Developer"),
            focus: vec![
                String::from("Rust"),
                String::from("Solana"),
                String::from("Web3"),
                String::from("DeFi")
            ],
            current_learning: String::from("Zero-Knowledge Proofs"),
            fun_fact: String::from("I dream in Rust")
        }
    }
}
```

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=sagarregmi2057&theme=radical&hide_border=true&background=0D1117&stroke=0D1117&ring=14F195&fire=14F195&currStreakLabel=14F195" alt="GitHub Streak Stats"/>
</div>

## 🛠️ Tech Arsenal

<div align="center">
  
  ![Rust](https://img.shields.io/badge/-Rust-000000?style=for-the-badge&logo=rust&logoColor=B7410E)
  ![Solana](https://img.shields.io/badge/-Solana-000000?style=for-the-badge&logo=solana&logoColor=14F195)
  ![Anchor](https://img.shields.io/badge/-Anchor-000000?style=for-the-badge&logo=anchor&logoColor=14F195)
  ![Web3.js](https://img.shields.io/badge/-Web3.js-000000?style=for-the-badge&logo=web3.js&logoColor=F16822)
  ![TypeScript](https://img.shields.io/badge/-TypeScript-000000?style=for-the-badge&logo=typescript&logoColor=3178C6)
  ![React](https://img.shields.io/badge/-React-000000?style=for-the-badge&logo=react&logoColor=61DAFB)
  
</div>

## 🎨 Solana Program Showcase

```rust
/// A glimpse into my Solana development style
#[program]
pub mod defi_protocol {
    use super::*;
    
    #[derive(Accounts)]
    pub struct Initialize<'info> {
        #[account(init, payer = authority, space = 8 + 32)]
        pub vault: Account<'info, Vault>,
        #[account(mut)]
        pub authority: Signer<'info>,
        pub system_program: Program<'info, System>,
    }

    pub fn initialize(ctx: Context<Initialize>) -> Result<()> {
        let vault = &mut ctx.accounts.vault;
        vault.authority = ctx.accounts.authority.key();
        msg!("🚀 Vault initialized successfully!");
        Ok(())
    }
}
```

## 💫 Performance Metrics

<div align="center">

```mermaid
graph LR
    A[Program Size] -->|Optimization| B[3.2 KB]
    C[CPI Calls] -->|Efficiency| D[0.576 ms]
    E[Memory Usage] -->|Zero-Copy| F[1.8 KB]
    style A fill:#14F195,stroke:#14F195,stroke-width:2px
    style B fill:#000000,stroke:#14F195,stroke-width:2px
    style C fill:#14F195,stroke:#14F195,stroke-width:2px
    style D fill:#000000,stroke:#14F195,stroke-width:2px
    style E fill:#14F195,stroke:#14F195,stroke-width:2px
    style F fill:#000000,stroke:#14F195,stroke-width:2px
```

</div>

## 🌌 Solana Ecosystem Contributions

<div align="center">
  <table>
    <tr>
      <td align="center">
        <img src="https://img.shields.io/badge/SPL--Token-Contributions-14F195?style=for-the-badge&logo=solana" alt="SPL-Token"/>
        <br />
        "Enhanced token standards"
      </td>
      <td align="center">
        <img src="https://img.shields.io/badge/Anchor-Optimizations-B7410E?style=for-the-badge&logo=anchor" alt="Anchor"/>
        <br />
        "Framework improvements"
      </td>
      <td align="center">
        <img src="https://img.shields.io/badge/Metaplex-Innovations-FF69B4?style=for-the-badge&logo=solana" alt="Metaplex"/>
        <br />
        "NFT infrastructure"
      </td>
    </tr>
  </table>
</div>

## 🎯 Current Focus

```mermaid
mindmap
  root((Solana))
    Rust
      Smart Contracts
      Program Architecture
    DeFi
      Yield Optimization
      AMM Protocols
    NFTs
      Metaplex
      Candy Machine
    Performance
      Zero-Copy
      CPI Optimization
```

## 🎵 Vibing to the Sound of Solana:

<div align="center">

```ascii
♪♫•*¨*•.¸¸♫•*¨*•.¸¸♪
🎧 Now Playing: Solana Symphony in Rust Major
═══════════════════ ⠂▶
◄◄⠀▐▐⠀►►⠀⠀ ▇:𝟙𝟚:𝟛𝟘⠀►⠀∞:∞/∞:∞⠀⠀ ▌ ▌⠀⠀ ♫ ♪ ♫

🎼 Playlist: Sounds of Solana
├── 01. Rust Rhapsody
├── 02. Solana Sonata
├── 03. Program Prelude
├── 04. Zero-Copy Zen
└── 05. Anchor Anthem
```

<details>
<summary>🎵 Why these tracks?</summary>

> Each "song" represents a different aspect of Solana development:
> - **Rust Rhapsody**: The elegant patterns of Rust programming
> - **Solana Sonata**: The high-performance blockchain symphony
> - **Program Prelude**: The art of smart contract composition
> - **Zero-Copy Zen**: The efficiency of memory management
> - **Anchor Anthem**: The framework that brings it all together

</details>
</div>

<div align="center">
  <!-- Gradient line -->
  <img src="https://i.imgur.com/dBaSKWF.gif" height="20" width="100%">
  
  <img src="https://komarev.com/ghpvc/?username=sagarregmi2057&label=Profile%20views&color=14F195&style=flat" alt="Profile views"/>
</div>

## 🌠 Solana Development Journey

<div align="center">

```ascii
                      .─────────────.                      
                    ,'             ,'`.                    
                  ,'             ,'    `.                  
                ,'             ,'        `.                
              ,'             ,'            `.              
            ,'             ,'     ⭐         `.            
          ,'             ,'                   `.          
        ,'  SOLANA     ,'          ⭐           `.        
      ,'  ECOSYSTEM  ,'                          `.      
    ,'             ,'            ⭐                `.    
  ,'   ⭐         ,'                                `.  
,'             ,'                                    `.
`.           ,'                                     ,'
  `.       ,'                            ⭐       ,'  
    `.   ,'                                    ,'    
      `,'                                    ,'      
        `.                                 ,'        
          `.                ⭐           ,'          
            `.                        ,'            
              `.                    ,'              
                `.     ⭐         ,'                
                  `.            ,'                  
                    `.       ,'                    
                      `─────'                      
```

<table>
  <tr>
    <td align="center" width="33%">
      <img src="https://img.shields.io/badge/TPS-65K+-14F195?style=for-the-badge&logo=solana" alt="TPS"/>
      <br />
      <sub><b>Performance Focused</b></sub>
    </td>
    <td align="center" width="33%">
      <img src="https://img.shields.io/badge/Latency-400ms-14F195?style=for-the-badge&logo=solana" alt="Latency"/>
      <br />
      <sub><b>Speed Optimized</b></sub>
    </td>
    <td align="center" width="33%">
      <img src="https://img.shields.io/badge/Cost-$0.00025-14F195?style=for-the-badge&logo=solana" alt="Cost"/>
      <br />
      <sub><b>Cost Efficient</b></sub>
    </td>
  </tr>
</table>

<details>
<summary>🔮 Future Roadmap</summary>

```mermaid
timeline
    title Solana Development Milestones
    2025 Q1 : Zero-Copy : Implementation : Performance Optimization
    2025 Q2 : Custom SPL : Token Standards : DeFi Integration
    2025 Q3 : Metaplex : NFT Infrastructure : Gaming Protocols
    2025 Q4 : Cross-Chain : Bridge Development : Ecosystem Expansion
```

</details>

<br/>

<table>
  <tr>
    <td>
      <img src="https://img.shields.io/badge/Rust-Proficiency-B7410E?style=flat-square&logo=rust" alt="Rust"/>
      <div style="width: 120px; background: #1A1B1E; border-radius: 3px; padding: 2px;">
        <div style="width: 95%; background: #B7410E; height: 8px; border-radius: 2px;"></div>
      </div>
    </td>
    <td>
      <img src="https://img.shields.io/badge/Solana-Expertise-14F195?style=flat-square&logo=solana" alt="Solana"/>
      <div style="width: 120px; background: #1A1B1E; border-radius: 3px; padding: 2px;">
        <div style="width: 90%; background: #14F195; height: 8px; border-radius: 2px;"></div>
      </div>
    </td>
    <td>
      <img src="https://img.shields.io/badge/Web3-Innovation-FF69B4?style=flat-square&logo=web3.js" alt="Web3"/>
      <div style="width: 120px; background: #1A1B1E; border-radius: 3px; padding: 2px;">
        <div style="width: 85%; background: #FF69B4; height: 8px; border-radius: 2px;"></div>
      </div>
    </td>
  </tr>
</table>

</div>

<div align="center">
  <sub>Built with ❤️ and 🦀 by Sagar Regmi</sub>
</div> 
