<div align="center">
    <picture>
        <source media="(prefers-color-scheme: dark)" srcset=".github/1inch_logo_white.svg">
        <img src=".github/1inch_logo_black.svg" alt="1inch" width="300">
    </picture>
</div>

# 1inch Smart Contract Audit Reports

This repository is the official archive of security audit reports for smart contracts developed by 1inch Network. The reports were produced by independent security firms and researchers, and are grouped by protocol — each section below corresponds to a folder in this repository. Most links point directly to the PDF report; a few link to reports published on the auditor's website.

## Contents

- [Aqua and SwapVM v1](#aqua-and-swapvm-v1)
- [Aggregation Protocol v6 and Limit Order Protocol v4](#aggregation-protocol-v6-and-limit-order-protocol-v4)
- [Aggregation Protocol v5 and Limit Order Protocol v3](#aggregation-protocol-v5-and-limit-order-protocol-v3)
- [Aggregation Protocol v4](#aggregation-protocol-v4)
- [Aggregation Protocol v3](#aggregation-protocol-v3)
- [Aggregation Protocol v2](#aggregation-protocol-v2)
- [Limit Order Protocol v2](#limit-order-protocol-v2)
- [Limit Order Protocol v1](#limit-order-protocol-v1)
- [Fusion Mode and Token Plugins](#fusion-mode-and-token-plugins)
- [Fusion Settlement v2](#fusion-settlement-v2)
- [Fees for Limit Orders and Fusion v1](#fees-for-limit-orders-and-fusion-v1)
- [Cross-chain Protocol (Fusion+)](#cross-chain-protocol-fusion)
- [Crosschain Fees v1.1](#crosschain-fees-v11)
- [Solana Fusion v1](#solana-fusion-v1)
- [Solana Cross-chain v1](#solana-cross-chain-v1)
- [Multi-Farming Contracts v3](#multi-farming-contracts-v3)
- [Liquidity Protocol](#liquidity-protocol)
- [Fixed Rate Swap v1](#fixed-rate-swap-v1)
- [Vesting Contract](#vesting-contract)

## Aqua and SwapVM v1

Aqua — a shared liquidity layer where makers' funds stay in their own wallets while being available to multiple trading strategies — together with SwapVM, a programmable virtual machine that executes swaps defined as bytecode programs.

- [Bailsec](https://github.com/1inch/1inch-audits/raw/master/Aqua%20and%20SwapVM%20v1/Aqua_SwapVM_v1_Bailsec.pdf)
- [Decurity](https://github.com/1inch/1inch-audits/raw/master/Aqua%20and%20SwapVM%20v1/Aqua_SwapVM_v1_Decurity.pdf)
- [Hashlock](https://github.com/1inch/1inch-audits/raw/master/Aqua%20and%20SwapVM%20v1/Aqua_SwapVM_v1_Hashlock.pdf)
- [Hexens](https://github.com/1inch/1inch-audits/raw/master/Aqua%20and%20SwapVM%20v1/Aqua_SwapVM_v1_Hexens.pdf)
- [MixBytes](https://github.com/1inch/1inch-audits/raw/master/Aqua%20and%20SwapVM%20v1/Aqua_SwapVM_v1_Mixbytes.pdf)
- [Nethermind](https://github.com/1inch/1inch-audits/raw/master/Aqua%20and%20SwapVM%20v1/Aqua_SwapVM_v1_Nethermind.pdf)
- [OpenZeppelin](https://github.com/1inch/1inch-audits/raw/master/Aqua%20and%20SwapVM%20v1/Aqua_SwapVM_v1_OpenZeppelin.pdf)
- [Theori](https://github.com/1inch/1inch-audits/raw/master/Aqua%20and%20SwapVM%20v1/Aqua_SwapVM_v1_Theori.pdf)

## Aggregation Protocol v6 and Limit Order Protocol v4

The sixth version of the Aggregation Router combined with the fourth version of the Limit Order Protocol in a single deployment, including the v6.1 and v6.2 updates.

- Aggregation Router v6
  - [Consensys](https://github.com/1inch/1inch-audits/raw/master/Aggregation%20Pr.%20V6%20and%20Limit%20Order%20Pr.V4/1inch%20Aggregation%20Router%20V6_Consensys.pdf)
  - [Decurity](https://github.com/1inch/1inch-audits/raw/master/Aggregation%20Pr.%20V6%20and%20Limit%20Order%20Pr.V4/1inch%20Aggregation%20Router%20V6_Decurity.pdf)
  - [Hexens](https://github.com/1inch/1inch-audits/raw/master/Aggregation%20Pr.%20V6%20and%20Limit%20Order%20Pr.V4/1inch%20Aggregation%20Router%20V6_Hexens.pdf)
  - [OpenZeppelin](https://github.com/1inch/1inch-audits/raw/master/Aggregation%20Pr.%20V6%20and%20Limit%20Order%20Pr.V4/1inch%20Aggregation%20Router%20V6_OpenZeppelin.pdf)
  - [PeckShield](https://github.com/1inch/1inch-audits/raw/master/Aggregation%20Pr.%20V6%20and%20Limit%20Order%20Pr.V4/1inch%20Aggregation%20Router%20V6_PeckShield.pdf)
  - [Pessimistic](https://github.com/1inch/1inch-audits/raw/master/Aggregation%20Pr.%20V6%20and%20Limit%20Order%20Pr.V4/1inch%20Aggregation%20Router%20V6_Pessimistic.pdf)
- Aggregation Router v6.1
  - [Decurity](https://github.com/1inch/1inch-audits/raw/master/Aggregation%20Pr.%20V6%20and%20Limit%20Order%20Pr.V4/1inch%20Aggregation%20Router%20V6.1_Decurity.pdf)
  - [Hexens](https://github.com/1inch/1inch-audits/raw/master/Aggregation%20Pr.%20V6%20and%20Limit%20Order%20Pr.V4/1inch%20Aggregation%20Router%20V6.1_Hexens.pdf)
  - [OpenZeppelin](https://github.com/1inch/1inch-audits/raw/master/Aggregation%20Pr.%20V6%20and%20Limit%20Order%20Pr.V4/1inch%20Aggregation%20Router%20V6.1_OpenZeppelin.pdf)
  - [PeckShield](https://github.com/1inch/1inch-audits/raw/master/Aggregation%20Pr.%20V6%20and%20Limit%20Order%20Pr.V4/1inch%20Aggregation%20Router%20V6.1_PeckShield.pdf)
- Aggregation Router v6.2
  - [Decurity](https://github.com/1inch/1inch-audits/raw/master/Aggregation%20Pr.%20V6%20and%20Limit%20Order%20Pr.V4/1inch%20Aggregation%20Router%20V6.2_Decurity.pdf)
  - [Hexens](https://github.com/1inch/1inch-audits/raw/master/Aggregation%20Pr.%20V6%20and%20Limit%20Order%20Pr.V4/1inch%20Aggregation%20Router%20V6.2_Hexens.pdf)
  - [Pessimistic](https://github.com/1inch/1inch-audits/raw/master/Aggregation%20Pr.%20V6%20and%20Limit%20Order%20Pr.V4/1inch%20Aggregation%20Router%20V6.2_Pessimistic.pdf)
- Limit Order Protocol v4
  - [OpenZeppelin](https://github.com/1inch/1inch-audits/raw/master/Aggregation%20Pr.%20V6%20and%20Limit%20Order%20Pr.V4/1inch%20Limit%20Order%20Protocol%20v4_OpenZeppelin.pdf)
- Limit Order Protocol v4.1
  - [OpenZeppelin](https://github.com/1inch/1inch-audits/raw/master/Aggregation%20Pr.%20V6%20and%20Limit%20Order%20Pr.V4/1inch%20Limit%20Order%20Protocol%20v4.1_OpenZeppelin.pdf)

## Aggregation Protocol v5 and Limit Order Protocol v3

Aggregation Router v5 — the swap aggregation router combined with the third version of the Limit Order Protocol in a single deployment.

- [ABDK](https://github.com/1inch/1inch-audits/raw/master/Aggregation%20Pr.%20V5%20and%20Limit%20Order%20Pr.V3/1inch%20Aggregation%20Router%20V5_ABDK%20Consulting.pdf)
- [CoinFabrik](https://github.com/1inch/1inch-audits/raw/master/Aggregation%20Pr.%20V5%20and%20Limit%20Order%20Pr.V3/1inch%20Aggregation%20Router%20V5_CoinFabrik.pdf)
- [Consensys](https://github.com/1inch/1inch-audits/raw/master/Aggregation%20Pr.%20V5%20and%20Limit%20Order%20Pr.V3/1inch%20Aggregation%20Router%20V5_Consensys.pdf)
- [Igor Gulamov](https://github.com/1inch/1inch-audits/raw/master/Aggregation%20Pr.%20V5%20and%20Limit%20Order%20Pr.V3/1inch%20Aggregation%20Router%20V5_IgorGulamov.pdf)
- [MixBytes](https://github.com/1inch/1inch-audits/raw/master/Aggregation%20Pr.%20V5%20and%20Limit%20Order%20Pr.V3/1inch%20Aggregation%20Router%20V5_MixBytes.pdf)
- [OpenZeppelin](https://github.com/1inch/1inch-audits/raw/master/Aggregation%20Pr.%20V5%20and%20Limit%20Order%20Pr.V3/1inch%20Aggregation%20Router%20V5_OpenZepplin.pdf)
- [PeckShield](https://github.com/1inch/1inch-audits/raw/master/Aggregation%20Pr.%20V5%20and%20Limit%20Order%20Pr.V3/1inch%20Aggregation%20Router%20V5_PeckShield.pdf)
- [Pessimistic](https://github.com/1inch/1inch-audits/raw/master/Aggregation%20Pr.%20V5%20and%20Limit%20Order%20Pr.V3/1inch%20Aggregation%20Router%20V5_Pessimistic.pdf)
- [Statemind](https://github.com/1inch/1inch-audits/raw/master/Aggregation%20Pr.%20V5%20and%20Limit%20Order%20Pr.V3/1inch%20Aggregation%20Router%20V5_Statemind.pdf)
- [Zokyo](https://github.com/1inch/1inch-audits/raw/master/Aggregation%20Pr.%20V5%20and%20Limit%20Order%20Pr.V3/1inch%20Aggregation%20Router%20V5_Zokyo.pdf)

## Aggregation Protocol v4

The fourth version of the Aggregation Router.

- [ABDK](https://github.com/1inch/1inch-audits/raw/master/Aggregation%20Protocol%20V4/1inch%20Aggregation%20Router%20v4%20Audit_ABDK.pdf)
- [Chainsulting](https://github.com/1inch/1inch-audits/raw/master/Aggregation%20Protocol%20V4/1inch%20Aggregation%20Router%20v4%20Audit_Chainsulting.pdf)
- [CoinFabrik](https://github.com/1inch/1inch-audits/raw/master/Aggregation%20Protocol%20V4/1inch%20Aggregation%20Router%20v4%20Audit_Coinfabrik.pdf)
- [Consensys](https://github.com/1inch/1inch-audits/raw/master/Aggregation%20Protocol%20V4/1inch%20Aggregation%20Router%20v4%20Audit_Consensys.pdf)
- [Igor Gulamov](https://github.com/1inch/1inch-audits/raw/master/Aggregation%20Protocol%20V4/1inch%20Aggregation%20Router%20v4%20Audit_Igor%20Gulamov.pdf)
- [MixBytes](https://github.com/1inch/1inch-audits/raw/master/Aggregation%20Protocol%20V4/1Inch%20Aggregation%20Router%20v4%20Audit_MixBites.pdf)
- [Pessimistic](https://github.com/1inch/1inch-audits/raw/master/Aggregation%20Protocol%20V4/1inch%20Aggregation%20Router%20v4%20Audit_Pessimistic.pdf)

## Aggregation Protocol v3

The third version of the Aggregation Router.

- [Certik](https://github.com/1inch/1inch-audits/raw/master/Aggregation%20Protocol%20V3/Certik%20-%201inch%20v3%20Audit%20Report.pdf)
- [Igor Gulamov](https://github.com/1inch/1inch-audits/raw/master/Aggregation%20Protocol%20V3/Gulamov%20-%201inch%20v3%20Audit%20Report.pdf)
- [MixBytes](https://github.com/1inch/1inch-audits/raw/master/Aggregation%20Protocol%20V3/MixBytes%20-%201inch%20v3%20Audit%20Report.pdf)

## Aggregation Protocol v2

The second version of the aggregation contracts (1inch v2).

- [Certik](https://github.com/1inch/1inch-audits/raw/master/Aggregation%20Protocol%20V2/Certik%20-%201inch%20v2%20Audit%20Report.pdf)
- [Chainsulting](https://github.com/1inch/1inch-audits/raw/master/Aggregation%20Protocol%20V2/Chainsulting%20-%201inch%20v2%20Audit%20Report.pdf)
- [CoinFabrik](https://github.com/1inch/1inch-audits/raw/master/Aggregation%20Protocol%20V2/Coinfabrik%20-%201inch%20v2%20Audit%20Report.pdf)
- [Hacken](https://github.com/1inch/1inch-audits/raw/master/Aggregation%20Protocol%20V2/Hacken%20-%201inch%20v2%20Audit%20Report.pdf)
- [Haechi](https://github.com/1inch/1inch-audits/raw/master/Aggregation%20Protocol%20V2/Haechi%20-%201inch%20v2%20Audit%20Report.pdf)
- [MixBytes](https://github.com/1inch/1inch-audits/raw/master/Aggregation%20Protocol%20V2/MixBytes%20-%201inch%20v2%20Audit%20Report.pdf)
- [OpenZeppelin](https://blog.openzeppelin.com/1inch-exchange-audit/)
- [Scott Bigelow](https://github.com/1inch/1inch-audits/raw/master/Aggregation%20Protocol%20V2/Scott%20Bigelow%20-%201inch%20v2%20Audit%20Report.pdf)
- [SlowMist](https://github.com/1inch/1inch-audits/raw/master/Aggregation%20Protocol%20V2/Slowmist%20-%201inch%20v2%20Audit%20Report.pdf)

## Limit Order Protocol v2

The second version of the protocol for signed off-chain limit orders.

- [ABDK](https://github.com/1inch/1inch-audits/raw/master/Limit%20Order%20Protocol%20V2/1Inch%20Limit%20Order%20Protocol_ABDK.pdf)
- [Certik](https://github.com/1inch/1inch-audits/raw/master/Limit%20Order%20Protocol%20V2/1inch%20Limit%20Order%20Portocol_Certik.pdf)
- [Chainsulting](https://github.com/1inch/1inch-audits/raw/master/Limit%20Order%20Protocol%20V2/1Inch%20Limit%20Order%20Protocol_Chainsulting.pdf)
- [CoinFabrik](https://github.com/1inch/1inch-audits/raw/master/Limit%20Order%20Protocol%20V2/1Inch%20Limit%20Order%20Protocol_CoinFabrik.pdf)
- [Igor Gulamov](https://github.com/1inch/1inch-audits/raw/master/Limit%20Order%20Protocol%20V2/1Inch%20Limit%20Order%20Protocol_IgorGulamov.pdf)
- [MixBytes](https://github.com/1inch/1inch-audits/raw/master/Limit%20Order%20Protocol%20V2/1Inch%20Limit%20Order%20Protocol_MixBytes.pdf)
- [Pessimistic](https://github.com/1inch/1inch-audits/raw/master/Limit%20Order%20Protocol%20V2/1Inch%20Limit%20Order%20Protocol_Pessimistic.pdf)

## Limit Order Protocol v1

The first version of the Limit Order Protocol.

- [ABDK](https://github.com/1inch/1inch-audits/raw/master/Limit%20Order%20Protocol/ABDK%20-%201inch%20Limit%20Order%20Protocol%20audit.pdf)
- [Chainsulting](https://github.com/1inch/1inch-audits/raw/master/Limit%20Order%20Protocol/Chainsulting%20-%201inch%20Limit%20Order%20Protocol%20audit.pdf)
- [CoinFabrik](https://github.com/1inch/1inch-audits/raw/master/Limit%20Order%20Protocol/Coinfabrik%20-%201inch%20Limit%20Order%20Protocol%20audit.pdf)
- [Coinspect](https://github.com/1inch/1inch-audits/raw/master/Limit%20Order%20Protocol/Coinspect%20-%201inch%20Limit%20Order%20Protocol%20audit.pdf)
- [Igor Gulamov](https://github.com/1inch/1inch-audits/raw/master/Limit%20Order%20Protocol/LimitSwap%20audit.pdf)
- [iosiro](https://iosiro.com/audits/1inch-network-limit-order-protocol-smart-contract-audit)
- [Pessimistic](https://github.com/1inch/1inch-audits/raw/master/Limit%20Order%20Protocol/Pessimistic%20-%201inch%20Limit%20Order%20Protocol%20audit.pdf)

## Fusion Mode and Token Plugins

Fusion mode — intent-based swaps settled by resolvers — together with the token plugins standard.

- [ABDK](https://github.com/1inch/1inch-audits/raw/master/Fusion%20mode%20and%20Token-plugins/1inch_FusionMode_ABDK.pdf)
- [ChainSecurity 1](https://github.com/1inch/1inch-audits/raw/master/Fusion%20mode%20and%20Token-plugins/1inch_FusionMode_ChainSecurity1.pdf)
- [ChainSecurity 2](https://github.com/1inch/1inch-audits/raw/master/Fusion%20mode%20and%20Token-plugins/1inch_FusionMode_ChainSecurity2.pdf)
- [ChainSecurity 3](https://github.com/1inch/1inch-audits/raw/master/Fusion%20mode%20and%20Token-plugins/1inch_FusionMode_ChainSecurity3.pdf)
- [Decurity 1](https://github.com/1inch/1inch-audits/raw/master/Fusion%20mode%20and%20Token-plugins/1inch_FusionMode_Decurity.1.pdf)
- [Decurity 2](https://github.com/1inch/1inch-audits/raw/master/Fusion%20mode%20and%20Token-plugins/1inch_FusionMode_Decurity.2.pdf)
- [Hexens 1](https://github.com/1inch/1inch-audits/raw/master/Fusion%20mode%20and%20Token-plugins/1inch_FusionMode_Hexens.1.pdf)
- [Hexens 2](https://github.com/1inch/1inch-audits/raw/master/Fusion%20mode%20and%20Token-plugins/1inch_FusionMode_Hexens.2.pdf)
- [iosiro](https://github.com/1inch/1inch-audits/raw/master/Fusion%20mode%20and%20Token-plugins/1inch_FusionMode_iosiro.pdf)
- [OpenZeppelin 1](https://github.com/1inch/1inch-audits/raw/master/Fusion%20mode%20and%20Token-plugins/1inch_FusionMode_OpenZepplin.1.pdf)
- [OpenZeppelin 2](https://github.com/1inch/1inch-audits/raw/master/Fusion%20mode%20and%20Token-plugins/1inch_FusionMode_OpenZepplin.2.pdf)
- [Oxorio](https://github.com/1inch/1inch-audits/raw/master/Fusion%20mode%20and%20Token-plugins/1inch_FusionMode_Oxorio.pdf)
- [Pashov (Token Plugins)](https://github.com/1inch/1inch-audits/raw/master/Fusion%20mode%20and%20Token-plugins/1inch_TokenPlugins-Pashov.pdf)
- [PeckShield](https://github.com/1inch/1inch-audits/raw/master/Fusion%20mode%20and%20Token-plugins/1inch_FusionMode_Peckshield.pdf)
- [Pessimistic](https://github.com/1inch/1inch-audits/raw/master/Fusion%20mode%20and%20Token-plugins/1inch_FusionMode_Pessimistic.pdf)

## Fusion Settlement v2

The second version of the Fusion settlement contracts, which fill signed orders through resolvers, including the v2.1 update.

- Settlement v2
  - [Decurity](https://github.com/1inch/1inch-audits/raw/master/Fusion%20Settlement%20V2/1inch%20Settlement%20v2_Decurity.pdf)
  - [Hexens](https://github.com/1inch/1inch-audits/raw/master/Fusion%20Settlement%20V2/1inch%20Settlement%20v2_Hexens.pdf)
  - [OpenZeppelin](https://github.com/1inch/1inch-audits/raw/master/Fusion%20Settlement%20V2/1inch%20Settlement%20v2_Open%20Zeppelin.pdf)
  - [PeckShield](https://github.com/1inch/1inch-audits/raw/master/Fusion%20Settlement%20V2/1inch%20Settlement%20v2_Peckshield.pdf)
  - [Pessimistic](https://github.com/1inch/1inch-audits/raw/master/Fusion%20Settlement%20V2/1inch%20Settlement%20v2_Pessimistic.pdf)
- Settlement v2.1
  - [AstraSec](https://github.com/1inch/1inch-audits/raw/master/Fusion%20Settlement%20V2/1inch%20Settlement%20v2.1_AstraSec.pdf)
  - [Decurity](https://github.com/1inch/1inch-audits/raw/master/Fusion%20Settlement%20V2/1inch%20Settlement%20v2.1_Decurity.pdf)
  - [Hexens](https://github.com/1inch/1inch-audits/raw/master/Fusion%20Settlement%20V2/1inch%20Settlement%20v2.1_Hexens.pdf)
  - [OpenZeppelin](https://github.com/1inch/1inch-audits/raw/master/Fusion%20Settlement%20V2/1inch%20Settlement%20v2.1_Open%20Zepplin.pdf)
  - [Pashov](https://github.com/1inch/1inch-audits/raw/master/Fusion%20Settlement%20V2/1inch%20Settlement%20v2.1_Pashov.pdf)
  - [Pessimistic](https://github.com/1inch/1inch-audits/raw/master/Fusion%20Settlement%20V2/1inch%20Settlement%20v2.1_Pessemistic.pdf)

## Fees for Limit Orders and Fusion v1

Fee flow contracts that introduce protocol fees for the Limit Order Protocol and Fusion.

- [AstraSec](https://github.com/1inch/1inch-audits/raw/master/Fees%20for%20LO%20and%20Fusion%20V1/Fee%20flow%20v1-AstraSec.pdf)
- [Bailsec](https://github.com/1inch/1inch-audits/raw/master/Fees%20for%20LO%20and%20Fusion%20V1/Fee%20flow%20v1-Bailsec.pdf)
- [ChainLight](https://github.com/1inch/1inch-audits/raw/master/Fees%20for%20LO%20and%20Fusion%20V1/Fee%20flow%20v1-ChainLight.pdf)
- [Decurity](https://github.com/1inch/1inch-audits/raw/master/Fees%20for%20LO%20and%20Fusion%20V1/Fee%20flow%20v1-Decurity.pdf)
- [OpenZeppelin](https://github.com/1inch/1inch-audits/raw/master/Fees%20for%20LO%20and%20Fusion%20V1/Fee%20flow%20v1-Open%20Zepplin.pdf)
- [Sherlock](https://github.com/1inch/1inch-audits/raw/master/Fees%20for%20LO%20and%20Fusion%20V1/Fee%20flow%20v1-Sherlock.pdf)

## Cross-chain Protocol (Fusion+)

1inch Fusion+ — cross-chain atomic swaps built on escrow contracts, versions 1 and 2.

- Cross-chain Swap v1
  - [AstraSec](https://github.com/1inch/1inch-audits/raw/master/Cross-chain%20Protocol/1inch-cross-chain-swap-v1-AstraSec.pdf)
  - [Consensys](https://github.com/1inch/1inch-audits/raw/master/Cross-chain%20Protocol/1inch-cross-chain-swap-v1-Consensys.pdf)
  - [Decurity](https://github.com/1inch/1inch-audits/raw/master/Cross-chain%20Protocol/1inch-cross-chain-swap-v1-Decurity.pdf)
  - [Igor Gulamov](https://github.com/1inch/1inch-audits/raw/master/Cross-chain%20Protocol/1inch-cross-chain-swap-v1-Igor%20Gulamov.pdf)
  - [OpenZeppelin](https://github.com/1inch/1inch-audits/raw/master/Cross-chain%20Protocol/1inch-cross-chain-swap-v1-Open%20Zeppelin.pdf)
  - [Pessimistic](https://github.com/1inch/1inch-audits/raw/master/Cross-chain%20Protocol/1inch-cross-chain-swap-v1-Pessimistic.pdf)
- Cross-chain Swap v2
  - [AstraSec](https://github.com/1inch/1inch-audits/raw/master/Cross-chain%20Protocol/1inch-cross-chain-v2-Astrasec.pdf)
  - [Consensys](https://github.com/1inch/1inch-audits/raw/master/Cross-chain%20Protocol/1inch-cross-chain-v2-Consensys.pdf)
  - [Decurity](https://github.com/1inch/1inch-audits/raw/master/Cross-chain%20Protocol/1inch-cross-chain-v2-Decurity.pdf)
  - [Igor Gulamov](https://github.com/1inch/1inch-audits/raw/master/Cross-chain%20Protocol/1inch-cross-chain-v2-Igor%20Gulamov.pdf)
  - [OpenZeppelin](https://github.com/1inch/1inch-audits/raw/master/Cross-chain%20Protocol/1inch-cross-chain-v2-Open%20Zeppelin.pdf)
  - [Pessimistic](https://github.com/1inch/1inch-audits/raw/master/Cross-chain%20Protocol/1inch-cross-chain-v2-Pessimistic.pdf)

## Crosschain Fees v1.1

Protocol fee support for the cross-chain (Fusion+) swaps.

- [Certora](https://github.com/1inch/1inch-audits/raw/master/Crosschain%20fees%20v1.1/1inch%20Crosschain%20Fee%20v1.1_Certora.pdf)
- [Decurity](https://github.com/1inch/1inch-audits/raw/master/Crosschain%20fees%20v1.1/1inch%20Crosschain%20Fee%20v1.1_Decurity.pdf)
- [Hexens](https://github.com/1inch/1inch-audits/raw/master/Crosschain%20fees%20v1.1/1inch%20Crosschain%20Fee%20v1.1_Hexens.pdf)
- [OpenZeppelin](https://github.com/1inch/1inch-audits/raw/master/Crosschain%20fees%20v1.1/1inch%20Crosschain%20Fee%20v1.1_Open%20Zeppelin.pdf)
- [Sherlock](https://github.com/1inch/1inch-audits/raw/master/Crosschain%20fees%20v1.1/1inch%20Crosschain%20Fee%20v1.1_Sherlock.pdf)

## Solana Fusion v1

The first version of the Fusion swap protocol on Solana.

- [Decurity](https://github.com/1inch/1inch-audits/raw/master/Solana%20Fusion%20v1/Solana%20Fusion%20-%20Decurity%20v1.pdf)
- [Hexens](https://github.com/1inch/1inch-audits/raw/master/Solana%20Fusion%20v1/Solana%20Fusion%20-%20Hexens%20v1.pdf)
- [Kudelski](https://github.com/1inch/1inch-audits/raw/master/Solana%20Fusion%20v1/Solana%20Fusion%20v1_Kudelski.pdf)
- [Offside Labs](https://github.com/1inch/1inch-audits/raw/master/Solana%20Fusion%20v1/Solana%20Fusion%20v1_OffsideLabs.pdf)
- [OpenZeppelin](https://github.com/1inch/1inch-audits/raw/master/Solana%20Fusion%20v1/Solana%20Fusion%20-%20Open%20Zepplin%20v1.pdf)
- [OtterSec](https://github.com/1inch/1inch-audits/raw/master/Solana%20Fusion%20v1/Solana%20Fusion%20-%20Ottersec%20v1.pdf)
- [Quantstamp](https://github.com/1inch/1inch-audits/raw/master/Solana%20Fusion%20v1/Solana%20Fusion%20-%20Quantstamp%20v1.pdf)
- [Zenith](https://github.com/1inch/1inch-audits/raw/master/Solana%20Fusion%20v1/Solana%20Fusion%20-%20Zenith%20v1.01.pdf)

## Solana Cross-chain v1

The Solana implementation of the cross-chain (Fusion+) protocol, versions 1.0 and 1.1.

- Solana Cross-chain v1.0
  - [Decurity](https://github.com/1inch/1inch-audits/raw/master/Solana%20cross-chain%20v1/Solana%20cross-chain%20v1.0_Decurity.pdf)
  - [Hexens](https://github.com/1inch/1inch-audits/raw/master/Solana%20cross-chain%20v1/Solana%20cross-chain%20v1.0-Hexens.pdf)
  - [Offside Labs](https://github.com/1inch/1inch-audits/raw/master/Solana%20cross-chain%20v1/Solana%20cross-chain%20v1.0_OffsideLabs.pdf)
  - [Sherlock](https://github.com/1inch/1inch-audits/raw/master/Solana%20cross-chain%20v1/Solana%20cross-chain%20v1.0_Sherlock.pdf)
  - [Zenith](https://github.com/1inch/1inch-audits/raw/master/Solana%20cross-chain%20v1/Solana%20cross-chain%20v1.0-Zenith.pdf)
- Solana Cross-chain v1.1
  - [Decurity](https://github.com/1inch/1inch-audits/raw/master/Solana%20cross-chain%20v1/Solana%20cross-chain%20v1.1_Decurity.pdf)
  - [Hexens](https://github.com/1inch/1inch-audits/raw/master/Solana%20cross-chain%20v1/Solana%20cross-chain%20v1.1_Hexens.pdf)
  - [Offside Labs](https://github.com/1inch/1inch-audits/raw/master/Solana%20cross-chain%20v1/Solana%20cross-chain%20v1.1_OffsideLabs.pdf)
  - [Sherlock](https://github.com/1inch/1inch-audits/raw/master/Solana%20cross-chain%20v1/Solana%20cross-chain%20v1.1_Sherlock.pdf)
  - [Zenith](https://github.com/1inch/1inch-audits/raw/master/Solana%20cross-chain%20v1/Solana%20cross-chain%20v1.1_Zenith.pdf)

## Multi-Farming Contracts v3

The third version of the farming contracts, which allows running multiple reward farms for a single staked token.

- [ChainSafe](https://github.com/1inch/1inch-audits/raw/master/Multi-Farming%20Contracts%20V3/1inch%20Multi-Farming%20Contracts%20V3_Chainsafe.pdf)
- [CoinFabrik](https://github.com/1inch/1inch-audits/raw/master/Multi-Farming%20Contracts%20V3/1inch%20Multi-Farming%20Contracts%20V3_CoinFabrik.pdf)
- [Decurity](https://github.com/1inch/1inch-audits/raw/master/Multi-Farming%20Contracts%20V3/1inch%20Multi-Farming%20Contracts%20V3_Decurity.pdf)
- [Igor Gulamov](https://github.com/1inch/1inch-audits/raw/master/Multi-Farming%20Contracts%20V3/1inch%20Multi-Farming%20Contracts%20V3_Gulamov.pdf)
- [PeckShield](https://github.com/1inch/1inch-audits/raw/master/Multi-Farming%20Contracts%20V3/1inch%20Multi-Farming%20Contracts%20V3_Peckshield.pdf)
- [Pessimistic](https://github.com/1inch/1inch-audits/raw/master/Multi-Farming%20Contracts%20V3/1inch%20Multi-Farming%20Contracts%20V3_Pessimistic.pdf)
- [SmartState](https://github.com/1inch/1inch-audits/raw/master/Multi-Farming%20Contracts%20V3/1inch%20Multi-Farming%20Contracts%20V3_Smartstate.pdf)

## Liquidity Protocol

The 1inch Liquidity Protocol — an automated market maker with virtual balances that protects liquidity providers from front-running.

- [Certik](https://github.com/1inch/1inch-audits/raw/master/Liquidity%20Protocol/Certik%20-%201inch%20Liquidity%20Protocol%20audit.pdf)
- [Chainsulting](https://github.com/1inch/1inch-audits/raw/master/Liquidity%20Protocol/Chainsulting%20-%201inch%20Liquidity%20Protocol%20Audit.pdf)
- [CoinFabrik](https://github.com/1inch/1inch-audits/raw/master/Liquidity%20Protocol/Coinfabrik%20-%201inch%20Liquidity%20Protocol%20Audit.pdf)
- [Consensys Diligence](https://diligence.security/audits/2020/12/1inch-liquidity-protocol/)
- [Cure53](https://github.com/1inch/1inch-audits/raw/master/Liquidity%20Protocol/Cure53%20-%201inch%20Liquidity%20Protocol%20audit.pdf)
- [Igor Gulamov](https://github.com/1inch/1inch-audits/raw/master/Liquidity%20Protocol/Gulamov%20-%201inch%20Liquidity%20Protocol%20audit.pdf)
- [MixBytes](https://github.com/1inch/1inch-audits/raw/master/Liquidity%20Protocol/MixBytes%20-%201inch%20Liquidity%20Protocol%20Report.pdf)
- [OpenZeppelin](https://www.openzeppelin.com/news/1inch-liquidity-protocol-audit)

### Farming

Liquidity mining contracts for the Liquidity Protocol pools.

- [Igor Gulamov](https://github.com/1inch/1inch-audits/raw/master/Liquidity%20Protocol/Farming/Gulamov%20-%201inch%20Farming%20audit.pdf)
- [iosiro](https://iosiro.com/audits/1inch-exchange-staking-rewards-smart-contract-audit)

## Fixed Rate Swap v1

A contract for swapping between stablecoins at a nearly fixed rate.

- [Ackee Blockchain](https://github.com/1inch/1inch-audits/raw/master/Fixed%20Rate%20Swap%20V1/1inch%20FixedRateSwap_Ackee%20Blockchain.pdf)
- [Chainsulting](https://github.com/1inch/1inch-audits/raw/master/Fixed%20Rate%20Swap%20V1/1inch%20FixedRateSwap_Chainsulting.pdf)
- [CoinFabrik](https://github.com/1inch/1inch-audits/raw/master/Fixed%20Rate%20Swap%20V1/1inch%20FixedRateSwap_CoinFabrik.pdf)
- [iosiro](https://iosiro.com/audits/1inch-network-fixed-rate-swap-smart-contract-audit)
- [MixBytes](https://github.com/1inch/1inch-audits/raw/master/Fixed%20Rate%20Swap%20V1/1inch%20FixedRateSwap_MixedBytes.pdf)
- [Pessimistic](https://github.com/1inch/1inch-audits/raw/master/Fixed%20Rate%20Swap%20V1/1inch%20FixedRateSwap_Pessimistic.pdf)

## Vesting Contract

Step vesting contracts used for gradual token distribution.

- [Chainsulting](https://github.com/1inch/1inch-audits/raw/master/Vesting%20Contract/Chainsulting%20-%201inch%20Vesting%20Contract%20audit.pdf)
- [CoinFabrik](https://github.com/1inch/1inch-audits/raw/master/Vesting%20Contract/Coinfabrik%20-%201inch%20Vesting%20Contract%20audit.pdf)
- [Igor Gulamov](https://github.com/1inch/1inch-audits/raw/master/Vesting%20Contract/Gulamov%20-%201inch%20Vesting%20Contract%20audit.pdf)
- [iosiro](https://iosiro.com/audits/1inch-network-step-vesting-smart-contract-audit)
- [Pessimistic](https://github.com/1inch/1inch-audits/raw/master/Vesting%20Contract/Pessimistic%20-%201inch%20Vesting%20Contract%20audit.pdf)
