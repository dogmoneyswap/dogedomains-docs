# LNS Deployments

If you are working with an [LNS library](dapp-developer-guide/lns-libraries.md), your library will automatically find the LNS deployment you need. If for whatever reason, you need to interact with LNS directly, details for the currently supported deployments are detailed here.

The LNS registry is deployed at 0x00000000000C2E074eC69A0dFb2997BA6C7d2e1e. This same address is used across Mainnet, Ropsten, Rinkeby and Goerli.

On mainnet, the following registrars are deployed:

* .bch, using the .bch Permanent registrar.

To find out the contract address of each tld, check the "controller" address of the tld \(eg: [https://app.bch.domains/name/xyz](https://app.bch.domains/name/xyz) for `.xyz`

![](.gitbook/assets/screenshot-2021-05-19-at-17.54.17.png)

Ropsten test network has the .test registrar deployed. This registrar permits anyone to instantly register a domain for testing purposes; these domains persist for 28 days.

In addition, the test networks also have a deployment of the .eth registrar for testing purposes.

For other contract addresses such as root, multisig, controller, public resolver, and so on, you can see their address under [https://app.bch.domains/name/ens.eth/subdomains](https://app.bch.domains/name/ens.eth/subdomains)

Back in February 2020, the ENS registry was migrated to the new contract address to patch security vulnerabilities \(Read more detail [here](ens-migration-february-2020/technical-description.md)\). The prior registry addresses were:

* Mainnet, at [0x314159265dd8dbb310642f98f50c066173c1259b](https://etherscan.io/address/0x314159265dd8dbb310642f98f50c066173c1259b#code).
* Ropsten, at [0x112234455c3a32fd11230c42e7bccd4a84e02010](https://ropsten.etherscan.io/address/0x112234455c3a32fd11230c42e7bccd4a84e02010).
* Rinkeby, at [0xe7410170f87102df0055eb195163a03b7f2bff4a](https://rinkeby.etherscan.io/address/0xe7410170f87102df0055eb195163a03b7f2bff4a).
* Goerli, at [0x112234455c3a32fd11230c42e7bccd4a84e02010](https://goerli.etherscan.io/address/0x112234455c3a32fd11230c42e7bccd4a84e02010).
