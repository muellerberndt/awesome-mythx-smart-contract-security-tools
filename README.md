# Awesome MythX Smart Contract Security Tools

<p align="center">
	<img src="mythx_powered.png" height="200px"/>
</p>

[![Discord](https://img.shields.io/discord/481002907366588416.svg)](https://discord.gg/E3YrVtG)

[MythX](https://mythx.io) is a smart contract security analysis API that supports Ethereum, Quorum, Vechain, Roostock, Tron and other EVM-compatible blockchains. It uses static analysis, symbolic execution and input fuzzing to detect security bugs and verify the correctness of smart contract code. This is a curated list of developer tools and resources related to MythX.

## IDEs with MythX support

- [Remix IDE](https://remix.ethereum.org/) - Activate the "MythX Security Verification" module in plugin manager ([Howto](https://docs.mythx.io/en/latest/tools/remix/index.html))
- [MythX Plugin for Truffle](https://github.com/ConsenSys/truffle-security) - Security verification plugin for the [Truffle Framework](https://truffleframework.com)
- [MythX for VS Code](https://marketplace.visualstudio.com/items?itemName=MythX.mythxvsc) - MythX Extension for Visual Studio Code
- [Brownie](https://github.com/iamdefinitelyahuman/brownie) - Python framework for Ethereum smart contract deployment ([native integration](https://eth-brownie.readthedocs.io/en/latest/tests-security-analysis.html))
- [MythX Plugin for Embark](https://github.com/flex-dapps/embark-mythx) -  Security verification plugin for [Status Embark](https://embark.status.im) by [Flex Dapps](https://flexdapps.com)
- [Truffle Sca2t](https://github.com/tagomaru/truffle-sca2t) - Smart contract audit assistant (generates Mocha test files for CI)

## Command-line tools

- [MythX CLI](https://github.com/dmuhs/mythx-cli) -  Official command-line tool maintained by MythX the MythX team
- [Solfuzz](https://github.com/b-mueller/solfuzz) - Assertion checker for smart contracts written in Solidity
- [Sabre](https://github.com/b-mueller/sabre) - JavaScript CLI for the MythX API
- [Mythos](https://github.com/cleanunicorn/mythos) - Anoher MythX JavaScript client

## Continuous integration howtos

- [Setting up MythX in CircleCI](https://blog.mythx.io/howto/mythx-and-continuous-integration-part-1-circleci/)
- [Setting up MythX in Travis CI](https://blog.mythx.io/howto/mythx-and-continuous-integration-part-1-circleci/)
- [MythX in CI DIY Guide](https://blog.mythx.io/howto/part-3-mythx-heart-continuous-integration-diy/)

## Support and documentation

- [MythX CLI Docs](https://mythx-cli.readthedocs.io/en/latest/)
- [MythX Developer and User Guide](https://docs.mythx.io/en/latest/)
- [MythX Community Discord](https://discord.gg/kktn8Wt)

## Language bindings

- [MythXJS](https://github.com/ConsenSys/mythxjs)  - MythX JavaScript library
- [PythX](https://github.com/dmuhs/PythX) - A Python library for the MythX platform

## Articles, papers and videos

### Awesome videos

- [The Ether Wars (DEFCON 27 Conference Talk)](https://www.youtube.com/watch?v=Qd9ubry-c_M)
- [Advances in Smart Contract Vulnerability Detection (EthBerlin 2019 Conference Talk)](https://www.youtube.com/watch?v=6mtO9GfS91Q)
- [Detecting DeFi Composability Bugs (EthCC 2020 Conference Talk)](https://www.youtube.com/watch?v=WtE_goJ2n7Y&feature=youtu.be&t=155)
- [Using MythX in Smart Contract Development (Webinar)](https://www.youtube.com/watch?v=j43w42r7_wk)

### MythX bug detection and property checking

- [Detecting Generic Smart Contract Vulnerabilities with MythX (Medium)](https://medium.com/consensys-diligence/detecting-the-top-4-critical-smart-contract-vulnerabilities-with-mythx-9c568d7db7a6)
- [Checking Custom Security Properties with the MythX Plugin for Remix (Medium)](https://medium.com/coinmonks/advanced-smart-contract-security-verification-in-remix-9630b43695e5)
- [Checking Custom Correctness Properties of Smart Contracts Using the AssertionFailed Event (Medium)](https://medium.com/consensys-diligence/checking-custom-correctness-properties-of-smart-contracts-using-mythx-25cbac5d7852)
- [The Tech Behind MythX (MythX blog)](https://blog.mythx.io/features/mythx-tech-behind-the-scenes-of-smart-contract-analysis/)

### Symbolic execution / Mythril

- [Intro to Symbolic Execution in Mythril (Medium)](https://medium.com/@joran.honig/introduction-to-mythril-classic-and-symbolic-execution-ef59339f259b)
- [Smashing Smart Contracts (HITB GSEC 2018 / PDF)](https://conference.hitb.org/hitbsecconf2018ams/materials/D1T2%20-%20Bernhard%20Mueller%20-%20Smashing%20Ethereum%20Smart%20Contracts%20for%20Fun%20and%20ACTUAL%20Profit.pdf)
- [Advances in Smart Contract Vulnerability Detection (DEFCON 27 / PDF)](https://github.com/b-mueller/smashing-smart-contracts/blob/master/DEFCON27-EVM-Smart-Contracts-Mueller-Luca.pdf)
- [Multi-contract bug detection with Mythril (Medium)](https://blog.mythx.io/misc/easy-multi-contract-security-analysis-using-mythril/)

### Grey-box fuzzing / Harvey

- [Harvey Greybox Fuzzing Article Series (Medium)](https://medium.com/consensys-diligence/finding-vulnerabilities-in-smart-contracts-175c56affe2)
- [Fuzzing Smart Contracts Using Input Prediction (Medium)](https://medium.com/consensys-diligence/fuzzing-smart-contracts-using-input-prediction-29b30ba8055c)
- [Fuzzing Smart Contracts Using Multiple Transactions (Medium)](https://medium.com/consensys-diligence/fuzzing-smart-contracts-using-multiple-transactions-51471e4b3c69)
- [Detecting Reentrancy Issues in Smart Contracts Using Fuzzing (Medium)](https://medium.com/consensys-diligence/detecting-reentrancy-issues-in-smart-contracts-using-fuzzing-e81474ba3a2e)
- [Targeted fuzzing using static lookahead analysis: how to guide fuzzers using online static analysis (MythX blog)](https://blog.mythx.io/misc/targeted-fuzzing-using-static-lookahead-analysis-how-to-guide-fuzzers-using-online-static-analysis/)
- [Learning Inputs in Greybox Fuzzing (arXiv)](https://arxiv.org/pdf/1807.07875.pdf)
- [Harvey: A Greybox Fuzzer for Smart Contracts (arXiv)](https://arxiv.org/pdf/1905.06944.pdf)
- [Targeted Greybox Fuzzing with Static Lookahead Analysis (ICSE 2020)](https://mariachris.github.io/Pubs/ICSE-2020.pdf)

### Other
 
- [Practical Mutation Testing in Smart Contracts (Springer)](https://link.springer.com/chapter/10.1007%2F978-3-030-31500-9_19)
