# Awesome Safe Modules

Safe Modules are smart contracts that enhance Safe contracts by adding functionality while keeping module logic separate from Safe's core contracts.

[Safe Modules Docs](https://docs.safe.global/safe-core/safe-modules)

## Community: Ask for help & meet other Safe builders

- @Safe{Builders} Telegram group

## Quickstart: Make your first Safe Module

## Official Modules

- [4337 Module](https://github.com/safe-global/safe-modules/tree/f0af05c5817fe69291a801c150b3bb8de4da5f7f/modules/4337) - Safe Module/Fallback handler for ERC-4337 support.
- [Allowance Module](https://github.com/safe-global/safe-modules/tree/f0af05c5817fe69291a801c150b3bb8de4da5f7f/modules/allowances) - Registry for managing ERC20 and Ether transfer allowances.
- [Passkey Module](https://github.com/safe-global/safe-modules/tree/f0af05c5817fe69291a801c150b3bb8de4da5f7f/modules/passkey) - Passkey signature verifier that can be used as Safe signer.
- [Recovery Module](https://github.com/safe-global/safe-modules/tree/f0af05c5817fe69291a801c150b3bb8de4da5f7f/modules/recovery) - Social recovery module for Safe accounts.

## Third Party Repos

### Useful Tools & Libraries

- [dSafe Registry](https://twitter.com/daoism_systems) - A decentralized registry for Safe smart contracts, enabling alternative interaction methods.
- [Reference SDK for ERC-4337 with Safe{Core}](https://www.candide.dev/) - Open-source SDK for developing Safe-based smart accounts by Candide.
- [Fluidkey](https://fluidkey.com) - Privacy solution using stealth addresses for scalable privacy across EVM-compatible chains.
- [Cannon](https://usecannon.com) - A DevOps tool for protocol deployments and upgrades on EVM-compatible chains.

### Plugins & Extensions

- [BrahmaFi Console](https://www.brahma.fi/) - Unifies on-chain custody with efficient execution and policy-driven delegation.
- [Eternal Safe](https://github.com/eternalsafe/wallet) - A decentralized Safe{Wallet} and web app hosted on IPFS.
- [Extensible Fallback Handler + Signature Verifier Mixer](https://github.com/rndlabs/safe-contracts) - Framework for building function handlers or signature verifiers.
- [Safe Anonymization Module](https://oxor.io/) - Privacy module using ZKProof technology for anonymous Safe account management.
- [SafeRecover](https://github.com/porco-rosso-j/safe-recovery-noir) - Plugin for Safe account recovery using zk-powered mechanisms.

### Research & Governance

- [How to responsibly incentivize multisig signers?](https://github.com/bartosjiri/multisig-signer-incentives) - Community research project on incentivizing multisignature wallet signers.
- [Liveness Module](https://github.com/defi-wonderland/safe-liveness) - Enhances cross-chain user experience by syncing smart wallet configurations.
- [Safe Explorer](https://safescanner.xyz) - User-friendly block explorer for Safe ecosystem.
- [Safe Governance Analytics Dashboard](https://safedao.curiahub.xyz/) - Provides insights into governance activities within SafeDAO.
- [StableLab](https://www.stablelab.xyz/) - Enhances governance participation in SafeDAO through targeted solutions.

### Gnosis Guild & Zodiac

[Gnosis Guild](https://www.gnosisguild.org/) is an independent company spun out of Gnosis, offering a suite of tools for access controls and more. They are known for developing the Zodiac standard, a collection of tools for DAOs that enable flexible, module-based control of programmable accounts.

- [Zodiac Wiki](https://www.zodiac.wiki/) - A living resource for DAOs with documentation and a library.
- [Enclave](https://www.enclave.gg/) - A protocol for Encrypted Execution Environments (E3).
- [Zodiac Modules](https://www.zodiac.wiki/documentation#modules) - Includes modules like Reality, Exit, and Bridge, enhancing on-chain execution and cross-chain interactions.
  - [Bridge Module](https://www.zodiac.wiki/documentation/bridge-module) - Controls an avatar on another chain using an Arbitrary Message Bridge (AMB).
  - [Connext Module](https://github.com/gnosis/zodiac-module-connext/) - Enables cross-domain governance using Connext protocol.
  - [Exit Module](https://www.zodiac.wiki/documentation/exit-pattern) - Redeem tokens for a share of an avatar's assets, similar to Moloch DAO's rageQuit().
  - [Governor Module](https://www.zodiac.wiki/documentation/governor-module) - Integrates OpenZeppelin Governor for on-chain voting.
  - [oSnap Module](https://docs.umaproject.org/developers/osnap/osnap-quick-start) - Puts off-chain Snapshot votes on-chain using UMA's oracle.
  - [Kleros Snapshot Module](https://docs.kleros.io/integrations/types-of-integrations/1.-dispute-resolution-integration-plan/channel-partners/kleros-reality-module) - Executes based on Reality.eth oracle outcomes, using Kleros as arbitrator.
  - [Reality Module](https://www.zodiac.wiki/documentation/reality-module) - Executes transactions based on Reality.eth oracle outcomes.
  - [Safe Minion Module](https://daohaus.substack.com/p/6991f40b-3931-47ff-bea3-fa6f9c365135?s=r) - Manages Safe assets based on Moloch DAO proposals.
  - [Siphon Module](https://github.com/gnosisguild/zodiac-module-siphon) - Withdraws from liquidity positions to manage debt.
  - [Tellor Module](https://github.com/tellor-io/snapshot-zodiac-module) - Executes transactions using the Tellor oracle.
  - [Usul Module](https://github.com/SekerDAO/Usul) - Operates with trustless tokenized DeGov for flexible voting.

Anyone can contribute to the Zodiac ecosystem. You can submit a pull request on [this repository](https://github.com/gnosisguild/zodiac) or create a new module. Learn more about contributing to the Zodiac standard [here](https://github.com/gnosisguild/zodiac/blob/master/CONTRIBUTING.md).

## Building on Safe

- [Account Recovery with a regulated Swiss Bank](https://www.sygnum.com/) - Sygnum offers a secure recovery solution for Safe accounts, leveraging traditional finance frameworks.
- [Acme](https://www.acme.am) - Building an intent-based network for on-chain conversion with minimal development effort.
- [Lore](https://lore.xyz) - Protocol for communities to leverage Safe for value distribution and coordination.
- [Nest Wallet](https://nestwallet.xyz/) - Browser extension and mobile app for Safe Wallets, enabling biometric signing.
- [StationX](http://app.stationx.network) - Tools for communities to coordinate capital leveraging Safe.
- [ZenGuarden](https://zenguard.xyz) - Plugin marketplace for smart accounts to streamline development and risk assessment.
- [Alloc8](https://www.alloc8.xyz) - Delegates assets to managers while maintaining custody in smart wallets.
- [Palmera](https://www.palmeradao.xyz/) - Manages organizations on-chain with Safe integrations and DAO tools.
- [Epoch Protocol](https://www.epochprotocol.xyz/) - Automates transactions using Account Abstraction.
- [Onit](https://www.onit.fun/) - Manages Safe in an XMTP chat for multiplayer crypto experiences.
- [Aarc](https://aarc.xyz/) - Simplifies user accounts and enhances smart contract account adoption.

## Video Explanation

- [Create your own Safe Module](https://www.youtube.com/watch?v=5qZ8z2JWQ5o) - Gnosis Safe 🛠 Safe modding 101: Create your own Safe module

## Tutorials

- [Build a Custom Zodiac Module](https://www.zodiac.wiki/documentation/custom-module) - Learn the fundamental concepts of Zodiac modules while you build a super-simple example of a Custom Module.
