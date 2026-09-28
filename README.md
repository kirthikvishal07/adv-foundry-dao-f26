# Foundry DAO Governance

This repository is a learning project for building an on-chain DAO governance system with Solidity and Foundry. I am following the DAO and Governance lesson from the [Cyfrin Updraft Solidity course](https://www.youtube.com/watch?v=wUjYK5gwNZs&t=21945s), taught by Patrick Collins.

The course reference implementation is included in [`foundry-dao-cu/`](foundry-dao-cu/README.md). The top-level `src/`, `script/`, and `test/` directories currently contain Foundry's Counter starter example; DAO implementation work in this repository is in progress.

## Learning goals

- Understand token-based voting and governance proposals.
- Explore how a governance token, governor contract, and timelock work together.
- Practice writing and testing Solidity contracts with Foundry.

> Token-weighted voting is one governance model, but it has tradeoffs. Consider the risks of wealth-based voting when designing real governance systems.

## Requirements

- [Git](https://git-scm.com/)
- [Foundry](https://getfoundry.sh/)

Check that Foundry is installed:

```shell
forge --version
```

## Getting started

Clone this repository and enter its directory:

```shell
git clone <your-repository-url>
cd <your-repository-name>
```

Build and run the current test suite:

```shell
forge build
forge test
```

## Useful commands

Format Solidity files:

```shell
forge fmt
```

Create a gas snapshot:

```shell
forge snapshot
```

Start a local Ethereum node:

```shell
anvil
```

## Project layout

```text
src/          Solidity contracts for the root project
script/       Foundry deployment scripts
test/         Solidity tests
foundry-dao-cu/ Course reference implementation
```

## Course reference

- [Cyfrin Updraft: Lesson 14 — DAOs & Governance](https://www.youtube.com/watch?v=wUjYK5gwNZs&t=21945s)
- [Reference repository: Cyfrin/foundry-dao-cu](https://github.com/Cyfrin/foundry-dao-cu)
- [Foundry Book](https://book.getfoundry.sh/)
# adv-foundry-dao-f26
# adv-foundry-dao-f26
