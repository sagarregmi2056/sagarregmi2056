<div align="center" style="background: linear-gradient(135deg, rgba(8, 43, 96, 0.9), rgba(8, 43, 96, 0.4)); backdrop-filter: blur(10px); color: white; padding: 40px; min-height: 100vh; width: 100%; border: 1px solid rgba(255, 255, 255, 0.1); border-radius: 16px;">

# <div align="center" style="background: rgba(255, 255, 255, 0.1); padding: 20px; border-radius: 16px; backdrop-filter: blur(10px); border: 1px solid rgba(255, 255, 255, 0.1);">
  <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="35" alt="wave"/> 
  Hi, I'm Sagar Regmi
</div>

<div align="center" style="margin: 30px 0;">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=100&section=header&text=Full%20Stack%20Developer&fontSize=40&fontAlignY=35&animation=twinkling&fontColor=FFFFFF" width="100%" style="border-radius: 10px;" />
</div>

<div align="center" style="background: rgba(255, 255, 255, 0.05); padding: 20px; border-radius: 16px; backdrop-filter: blur(10px); border: 1px solid rgba(255, 255, 255, 0.1); margin: 20px 0;">
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
  <img src="https://i.imgur.com/dBaSKWF.gif" height="20" width="100%" style="margin: 20px 0;"/>
</div>

<div align="right" style="background: rgba(20, 241, 149, 0.1); padding: 20px; border-radius: 16px; backdrop-filter: blur(10px); border: 1px solid rgba(20, 241, 149, 0.2); margin: 20px 0;">
  <img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=600&size=22&duration=2000&pause=1000&color=14F195&center=true&vCenter=true&multiline=true&repeat=true&width=435&height=100&lines=Building+Smart+Contracts;Crafting+Web3+Solutions;Innovating+with+Blockchain" alt="Coding Animation"/>
</div>

## <svg width="24" height="24" viewBox="0 0 24 24" fill="none" style="vertical-align: middle; margin-right: 8px;">
  <path d="M13 7h-2v2h2V7zm0 4h-2v6h2v-6zm-1-9C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm0 18c-4.41 0-8-3.59-8-8s3.59-8 8-8 8 3.59 8 8-3.59 8-8 8z" fill="#14F195"/>
</svg> About Me

<div style="background: rgba(255, 255, 255, 0.05); padding: 20px; border-radius: 16px; backdrop-filter: blur(10px); border: 1px solid rgba(255, 255, 255, 0.1);">

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

</div>


<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 20px; padding: 20px;">
  
</div>

<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=18&duration=2000&pause=1000&color=14F195&center=true&vCenter=true&multiline=true&width=800&height=384&lines=%23[program];pub+mod+token_vault+%7B;++++use+anchor_lang::prelude::*%3B;++++%23[derive(Accounts)];++++pub+struct+Initialize%3C'info%3E+%7B;++++++++%23[account(init%2C+payer+%3D+authority)];++++++++pub+vault%3A+Account%3C'info%2C+TokenVault%3E%2C;++++++++pub+authority%3A+Signer%3C'info%3E%2C;++++++++pub+system_program%3A+Program%3C'info%2C+System%3E;++++%7D;++++pub+fn+initialize(ctx%3A+Context%3CInitialize%3E)+-%3E+Result%3C()%3E+%7B;++++++++msg!(%22%F0%9F%9A%80+Initializing+token+vault...%22)%3B;++++++++Ok(()));++++%7D;%7D" alt="Typing SVG" />
</div>

<!-- Static Code Display -->
```rust
#[program]
pub mod token_vault {
    use anchor_lang::prelude::*;

    #[derive(Accounts)]
    pub struct Initialize<'info> {
        #[account(init, payer = authority)]
        pub vault: Account<'info, TokenVault>,
        pub authority: Signer<'info>,
        pub system_program: Program<'info, System>
    }

    pub fn initialize(ctx: Context<Initialize>) -> Result<()> {
        msg!("🚀 Initializing token vault...");
        Ok(())
    }
}

#[account]
pub struct TokenVault {
    pub authority: Pubkey,    // 32
    pub token_mint: Pubkey,   // 32
    pub token_account: Pubkey // 32
}
```

## <svg width="24" height="24" viewBox="0 0 24 24" fill="none" style="vertical-align: middle; margin-right: 8px;">
  <path d="M22 9V7h-2V5c0-1.1-.9-2-2-2H4c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2v-2h2v-2h-2v-2h2v-2h-2V9h2zm-4 10H4V5h14v14zM6 13h5v4H6zm6-6h4v3h-4zM6 7h5v5H6zm6 4h4v6h-4z" fill="#14F195"/>
</svg> Tech Stack

<div align="center" style="background: rgba(255, 255, 255, 0.05); padding: 20px; border-radius: 16px; backdrop-filter: blur(10px); border: 1px solid rgba(255, 255, 255, 0.1); margin: 20px 0;">
  <!-- Blockchain & Web3 -->
  <a href="https://solana.com" target="_blank">
    <img src="https://img.shields.io/badge/-Solana-000000?style=for-the-badge&logo=solana&logoColor=14F195" alt="Solana"/>
  </a>
  <a href="https://ethereum.org" target="_blank">
    <img src="https://img.shields.io/badge/-Ethereum-000000?style=for-the-badge&logo=ethereum&logoColor=3C3C3D" alt="Ethereum"/>
  </a>
  <a href="https://www.rust-lang.org/" target="_blank">
    <img src="https://img.shields.io/badge/-Rust-000000?style=for-the-badge&logo=rust&logoColor=B7410E" alt="Rust"/>
  </a>
  <a href="https://web3js.readthedocs.io/" target="_blank">
    <img src="https://img.shields.io/badge/-Web3.js-000000?style=for-the-badge&logo=web3.js&logoColor=F16822" alt="Web3.js"/>
  </a>
  
  <!-- Full Stack -->
  <a href="https://nodejs.org" target="_blank">
    <img src="https://img.shields.io/badge/-Node.js-000000?style=for-the-badge&logo=node.js&logoColor=339933" alt="Node.js"/>
  </a>
  <a href="https://reactjs.org/" target="_blank">
    <img src="https://img.shields.io/badge/-React-000000?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React"/>
  </a>
  <a href="https://www.typescriptlang.org/" target="_blank">
    <img src="https://img.shields.io/badge/-TypeScript-000000?style=for-the-badge&logo=typescript&logoColor=3178C6" alt="TypeScript"/>
  </a>
  <a href="https://www.mongodb.com/" target="_blank">
    <img src="https://img.shields.io/badge/-MongoDB-000000?style=for-the-badge&logo=mongodb&logoColor=47A248" alt="MongoDB"/>
  </a>
  
  <!-- DevOps & Cloud -->
  <a href="https://www.docker.com/" target="_blank">
    <img src="https://img.shields.io/badge/-Docker-000000?style=for-the-badge&logo=docker&logoColor=2496ED" alt="Docker"/>
  </a>
  <a href="https://aws.amazon.com/" target="_blank">
    <img src="https://img.shields.io/badge/-AWS-000000?style=for-the-badge&logo=amazon-aws&logoColor=FF9900" alt="AWS"/>
  </a>
</div>

<!-- Tech Stack Icons in Compact Format -->
<div align="center" style="background: rgba(255, 255, 255, 0.05); padding: 20px; border-radius: 16px; backdrop-filter: blur(10px); border: 1px solid rgba(255, 255, 255, 0.1); margin: 20px 0;">
  <p>
    <img src="https://skillicons.dev/icons?i=solana,rust,nodejs,react,typescript,mongodb,docker,aws" />
  </p>
</div>

<div align="center" style="background: rgba(255, 255, 255, 0.05); padding: 20px; border-radius: 16px; backdrop-filter: blur(10px); border: 1px solid rgba(255, 255, 255, 0.1); margin: 20px 0;">
  <img src="https://komarev.com/ghpvc/?username=sagarregmi2057&label=Profile%20views&color=61DAFB&style=flat" alt="Profile views"/>
</div>

<div align="center" style="margin-top: 40px;">
  <sub>Built with ❤️ and 🦀 Rust | Powered by ⚡ Solana and 🌐 Web3 | Crafted by Sagar Regmi</sub>
</div>

## <svg width="24" height="24" viewBox="0 0 24 24" fill="none" style="vertical-align: middle; margin-right: 8px;">
  <path d="M12 2C6.48 2 2 6.48 2 12c0 5.52 4.48 10 10 10s10-4.48 10-10c0-5.52-4.48-10-10-10zm0 18c-4.41 0-8-3.59-8-8s3.59-8 8-8 8 3.59 8 8-3.59 8-8 8zm4.59-12.42L10 14.17l-2.59-2.58L6 13l4 4 8-8z" fill="#14F195"/>
</svg> Featured Projects

<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 20px; padding: 20px;">

 


 

## <svg width="24" height="24" viewBox="0 0 24 24" fill="none" style="vertical-align: middle; margin-right: 8px;">
  <path d="M20 4H4c-1.1 0-1.99.9-1.99 2L2 18c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2zm0 14H4V8l8 5 8-5v10zm-8-7L4 6h16l-8 5z" fill="#14F195"/>
</svg> Let's Connect

<div style="background: rgba(255, 255, 255, 0.05); padding: 30px; border-radius: 16px; backdrop-filter: blur(10px); border: 1px solid rgba(255, 255, 255, 0.1); margin: 20px 0; text-align: center;">
  <h3 style="color: #14F195; margin-bottom: 20px;">Get in Touch</h3>
  <p style="color: #fff; margin-bottom: 20px;">Interested in collaborating or have a project in mind? Let's connect and discuss!</p>
  <div style="display: flex; justify-content: center; gap: 20px;">
    <a href="https://github.com/sagarregmi2057" target="_blank" style="color: #fff; text-decoration: none; background: rgba(15, 8, 8, 0.74); padding: 10px 20px; border-radius: 8px; transition: all 0.3s;">GitHub</a>
    <a href="https://www.linkedin.com/in/sagar-regmi-60b377216/" target="_blank" style="color: #fff; text-decoration: none; background: rgba(255, 255, 255, 0.1); padding: 10px 20px; border-radius: 8px; transition: all 0.3s;">LinkedIn</a>
    <a href="mailto:sagarregmi2056@gmail..com" target="_blank" style="color: #fff; text-decoration: none; background: rgba(255, 255, 255, 0.1); padding: 10px 20px; border-radius: 8px; transition: all 0.3s;">Email</a>
  </div>
</div>

</div>



