---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/Mingzhe_CV.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      # Apply a gradient background
      css_class: hbx-bg-gradient
      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        My research interests span the broad domain of blockchain systems and Web 3.0, with a particular focus on blockchain interoperability, sharding, security, and intelligent blockchain systems. I am especially interested in designing scalable and efficient blockchain protocols, leveraging AI-driven techniques to enhance security and performance, and exploring decentralized finance (DeFi) and network economics. My work aims to address fundamental challenges in blockchain scalability, security, and usability by developing innovative and practically deployable solutions that push the boundaries of blockchain technology for real-world applications.
    design:
      columns: '1'
  - block: markdown
    id: hiring
    content:
      title: 🎓 Open Positions
      subtitle: ''
      text: |-        
        I am recruiting **PhD students, Master’s students, Postdoctoral Researchers,** and **Research Assistants** (full-time or part-time). **Start dates are flexible**; applications are reviewed on a rolling basis.
        
        **Research Focus (including but not limited to)**
        - **Blockchain systems & protocols:** sharding, cross-chain interoperability, consensus, verifiable computation/zk, L2 & rollups  
        - **DeFi security & economics:** MEV mitigation, transaction routing and cost optimization, attack detection/traceability  
        - **AI for Blockchain Systems:** on-chain & node telemetry, anomaly detection, time-series forecasting, retrieval-augmented analytics
        
        **What We’re Looking For**
        - Background in **systems/networks/cryptography/data/ML** (one or more)  
        - Strong implementation skills in **Rust / Go / C/C++ / Python** (one or more)  
        - Curiosity and drive for **both research and real-world impact** (papers/open-source/prototypes)  
        - Bonus (not required): publications, competition results, open-source contributions, or solid engineering experience
        
        **What We Offer**
        - Close mentorship and collaborative projects that bridge academia and industry  
        - Opportunities to build **real systems/prototypes** (idea → experiments → paper/open-source/prototype)  
        - Scholarships/salaries in line with university and project policies (to be discussed)
        
        **How to Apply (Rolling Review)**
        Please email **[mlibn@connect.ust.hk](mailto:mlibn@connect.ust.hk)** with subject  
        `Application – Position – Your Name – Research Area`, and include:
        1. **CV** (with links to projects/papers/open-source)  
        2. **Transcript(s)** (if available)  
        3. **One representative paper or code repo** (if available)  
        4. **1-page research statement** (if available)
        
        > Strong candidates are welcome to start as **RA** (onsite or remote) before formal enrollment.  
        > Candidates proposing their own topics or **co-advised projects** are also welcome.

    design:
      columns: '1'
  - block: markdown
    id: news
    content:
      title: Recent News
      subtitle: ''
      text: |-
        ...
    design:
      columns: '1'
  - block: markdown
    id: papers
    content:
      title: 📑 Publications
      subtitle: ''
      text: |-
        ### Published
        
        - **Chaoyue Yin*†**, **Mingzhe Li\***, Jin Zhang, You Lin†, Qingsong Wei, and Siow Mong Rick Goh. “Atomic Smart Contract Interoperability with High Efficiency via Cross-Chain Integrated Execution.” *IEEE Transactions on Parallel and Distributed Systems (TPDS)*, 2025.
        
        - **You Lin*†**, **Mingzhe Li\***, and Jin Zhang. “SpiralShard: Highly Concurrent and Secure Blockchain Sharding via Linked Cross-shard Endorsement.” *IEEE/ACM Transactions on Networking (TON)*, 2025.
        
        - **Mingzhe Li**, You Lin, Jin Zhang, and Wei Wang. “SP-Chain: Boosting Intra-Shard and Cross-Shard Security and Performance in Blockchain Sharding.” *IEEE Internet of Things Journal (IoTJ)*, 2025.
        
        - **Mingzhe Li**, Jin Zhang, and Wei Wang. “Towards Efficient and Deposit-Free Blockchain-Based Spatial Crowdsourcing.” *ACM Transactions on Sensor Networks (TOSN)*, 2024.
        
        - **Mingzhe Li**, Jin Zhang, and Wei Wang. “LB-Chain: Load-Balanced and Low-Latency Blockchain Sharding via Account Migration.” *IEEE Transactions on Parallel and Distributed Systems (TPDS)*, 2023.
        
        - **Mingzhe Li**, You Lin, Jin Zhang, and Wei Wang. “CoChain: High Concurrency Blockchain Sharding via Consensus on Consensus.” *IEEE INFOCOM*, 2023 (acceptance rate 19.2%).
        
        - **Mingzhe Li**, You Lin, Jin Zhang, and Wei Wang. “Jenga: Orchestrating Smart Contracts in Sharding-Based Blockchain for Efficient Processing.” *IEEE ICDCS*, 2022 (acceptance rate 19.9%).
        
        - **Mingzhe Li**, Jin Zhang, Wei Wang, and Qian Zhang. “Incentivizing WiFi-based Multilateration Location Verification.” *IEEE Internet of Things Journal (IoTJ)*, 2021.
        
        - **Mingzhe Li**, Jingrou Wu, Jin Zhang, and Wei Wang. “Towards Privacy-Preserving Task Assignment for Fully Distributed Spatial Crowdsourcing.” *IEEE Internet of Things Journal (IoTJ)*, 2021.
        
        - **Mingzhe Li**, Jin Zhang, and Wei Wang. “Task Selection and Scheduling for Food Delivery: A Game-Theoretic Approach.” *IEEE GLOBECOM*, 2018.
        
        ### Preprint
        
        - **Mingzhe Li**, Bo Gao, Kentaroh Toyoda, Yechao Yang, Juniarto Samsudin, Haibin Zhang, Sifei Lu, Tai Hou Tng, Kerching Choo, Andy Ting, Siow Mong Rick Goh, and Qingsong Wei. “MStableChain: Towards Multi-Native Stablecoins in EVM-Compatible Blockchain for Stable Fee and Mass Adoption.” *arXiv:2410.22100*, 2024.
        
        - **Hulin Yang*†**, **Mingzhe Li\***, Jin Zhang, Alia Asheralieva, Qingsong Wei, and Siow Mong Rick Goh. “BriDe Arbitrager: Enhancing Arbitrage in Ethereum 2.0 via Bribery-enabled Delayed Block Production.” *arXiv:2407.08537*, 2024.
        
        - **You Lin*†**, **Mingzhe Li\***, Qingsong Wei, Yong Liu, Siow Mong Rick Goh, and Jin Zhang. “DL-Chain: Scalable and Stable Blockchain Sharding with High Concurrency via Dual-Layer Consensus.” *arXiv:2407.06882*, 2024.
        
        ---
        
        **Legend:** **†** = (co-)supervised student; **\*** = equal contribution.
    design:
      columns: '1'
  - block: cta-card
    demo: true # Only display this section in the Hugo Blox Builder demo site
    content:
      title: 👉 Build your own academic website like this
      text: |-
        This site is generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.

        <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/hugo-blox-builder on GitHub">Star</a>

        Easily build anything with blocks - no-code required!

        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
      button:
        text: Get Started
        url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: 'bg-primary-300 dark:bg-primary-700'
        css_style: ''
---
