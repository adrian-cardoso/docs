---
title: Whitepapers
---

import YouTube from '@components/YouTube';
import PageRef from '@components/PageRef'
import Tabs from '@theme/Tabs';
import TabItem from '@theme/TabItem';

# Whitepapers

---

### **1. Chainweb, Kadena’s (layer 1) public blockchain protocol** <a href="#1-chainweb-kadenas-public-blockchain-protocol" id="1-chainweb-kadenas-public-blockchain-protocol"></a>

Chainweb is a braided, parallelized proof-of-work consensus mechanism that improves throughput and scalability while maintaining the security and integrity found in Bitcoin.

<YouTube videoId="hYvXxFbsN6I"/>

In 2020, Kadena's public blockchain performed a live network expansion from 10 chains to 20 chains. This doubled throughput, proving the network's ability to scale in production to meet ever-higher demand.

**Informational Resources**

- Article: [Kadena’s Public Blockchain 101](https://medium.com/kadena-io/all-about-chainweb-101-and-faqs-6bd88c325b45)
- Whitepapers: [Chainweb layer 1](./chainweb-layer-1.md)
- Article: [How to scale a Proof of Work Blockchain](https://medium.com/kadena-io/how-to-scale-a-proof-of-work-blockchain-9233e5b4b62)&#x20;

:::note

Resources for interacting with Kadena’s public blockchain are available [here](../../build/resources/pact-resources).

:::

### _2_**. Pact, Kadena’s smart contract language** <a href="#3-pact-kadenas-smart-contract-language" id="3-pact-kadenas-smart-contract-language"></a>

Pact is a human readable and Turing Incomplete smart contract language purpose-built for blockchains with powerful security features including full Formal Verification of user code, error messages, contract upgradability, support for interoperability, and strong permission and access control.

#### **Informational Resources**

- Article: [Safer, Smarter Contracts with Pact](https://medium.com/kadena-io/safer-smarter-contracts-with-pact-e86b9ccaca9f)
- Whitepaper: [Pact Smart Contract Language](./pact-smart-contract-language.md)
- Documentation: [Pact GitHub](https://github.com/kadena-io/pact)
- Documentation: [Pact Language Reference](https://pact-language.readthedocs.io/en/latest/pact-reference.html)

:::note

Resources for using Pact are available at the [Public chain interaction](https://kadena-io.github.io/kadena-docs/Public-Chain-Docs.html) page.

:::

### **3. Kuro, Kadena’s layer 2 blockchain** <a href="#2-kuro-kadenas-private-blockchain" id="2-kuro-kadenas-private-blockchain"></a>

Kuro has been proven to support up to 8,000 transactions per second across 500 nodes, and is available for evaluation on [AWS](https://aws.amazon.com/marketplace/pp/Kadena-LLC-Kadena-Blockchain-for-Enterprise-Commun/B07MKMKP4F) and [Azure](https://azuremarketplace.microsoft.com/en-ca/marketplace/apps/kadenallc.scalablebft?tab=Overview).

**Informational Resources**

- Article: [Kadena's layer 2 blockchain 101](https://medium.com/kadena-io/scalablebft-kadenas-private-blockchain-101-c99895c0fd50)
- Whitepaper: [Kuro layer 2](./kuro-layer-2.md)

:::note

Resources for deploying Kuro are available at the [Private chain deployment](https://kadena-io.github.io/kadena-docs/Private-Chain-Docs.html) page.

:::

### **4. Kadena's layer 1 + 2** <a href="#2-kuro-kadenas-private-blockchain" id="2-kuro-kadenas-private-blockchain"></a>

With 20 chains, the Kadena blockchain platform achieves an industry-leading 480,000 transactions per second.

<!-- ![Chainweb nodes have their own “local cluster” of two independent Kuro chains. They synchronize with the Chainweb node using a cross-chain bridge. Kuro chains in the cluster can accept transactions at 8k per second directly from clients and between each other. Thus a single cluster can do 16k TPS. Using the power of both layer 1 and layer 2 networks, Kadena’s blockchain can achieve around 480,000 TPS.](<../.gitbook/assets/Screenshot 2021-10-19 at 08.43.48.png>) -->

**Informational Resources**

- Article: [Kadena completes blockchain scaling to 480,000 TPS on 20 Chains](https://medium.com/kadena-io/kadena-completes-hybrid-blockchain-scaling-to-480-000-transactions-per-second-on-20-chains-5a652295533c)
- Article: [Kadena's layer 2 blockchain 101](https://medium.com/kadena-io/scalablebft-kadenas-private-blockchain-101-c99895c0fd50)
- Whitepaper: [Kuro layer 2](./kuro-layer-2.md)

:::note

Resources for deploying Kuro are available at the [Kuro layer 2 deployment](../../build/kuro-layer-2.md) page.

:::
