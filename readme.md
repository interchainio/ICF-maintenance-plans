The Interchain Foundation [has recently shared its overall plans](https://medium.com/@interchain-io/unification-unifying-the-cosmos-hub-stack-and-ecosystem-f0ba49a3208f) and vision for Interchain Stack and Cosmos Hub development, as it consolidates its contributions to Cosmos under Interchain Inc. The ICF begun the hand-off of core component development from stewards to Interchain Inc, and redefined a focused set of components to be maintained. 

In this document, the ICF outlines its short-and-medium term maintenance priorities for libraries and components of the Interchain Stack, as well as the Cosmos Hub - detailing existing hand-off processes. This is the current breakdown as of December 2024, subject to updates:

---

#### Cosmos Hub

* **Development/Maintenance:** Interchain Inc. will begin working with Informal Systems to onboard into development, maintenance, security, and upgrade procedures immediately. Informal Systems will step down from its stewardship role and support the Interchain Inc team lightly as of Q1 2025\.  
* **Testnet/Operations:** Interchain Inc. will coordinate with Hypha as they seek to continue their mandate of testnet and mainnet maintenance operations in 2025\.  
* **Hydro:** Informal Systems is developing plans for Hydro, ICF has not funded this development.  
* **Hub-support:** Interchain Inc. built a core Hub product team that will bring product proposals and ensure the support of the Hub as of Q1-2025.

#### IBC:

* **IBC-GO**: Development will continue under Interchain Inc., integrating the ICF’s IBC team, and focusing on IBC-Eureka and EVM interoperability next.  
* **IBC-RS**: ICF won’t continue funding or maintenance. Informal Systems will manage the open-source repository and maintain it.  
* **Go Relayer:** Deprioritized in favor of Hermes. ICF won’t continue funding nor maintenance. The owner can maintain the open-source repository at their discretion.  
* **Interchain Test:** Deprioritized, ICF won’t continue funding. The repository is open-source, and contributors can manage it at their discretion. Interchain Inc. may contribute to the codebase.  
* **Hermes:** ICF will collaborate with Informal Systems until mid-2025 for security updates. Long-term plans to take ownership at Interchain Inc. will depend on IBC Eureka's relaying strategy, its maintenance for traditional IBC is expected.

#### CometBFT:

* **Core hand-off**: Hand-off from Informal Systems to Interchain Inc, Informal will perform security updates and basic maintenance until mid-2025. Interchain Inc. will assume full stewardship throughout that time, focusing on block time and node I/O reduction.

#### Cosmos SDK:

* **Core hand-off**: Hand-off from Binary Builders occurring until mid-2025 for security updates and finalizing the SDK V2 release. Interchain Inc. will continue thereafter.  
* **Ledger, and other developments:** ICF will work with Zondax to maintain Ledger integrations and explore support for other wallets.  
* **EVM:** ICF will begin to support and fund addition of EVM functionalities to Cosmos SDK applications.

#### CosmWasm, WasmVM, Wasmd:

* **Core hand-off**: Confio will continue security and upgrades through mid-2025 under ICF's contract. Confio will pursue funding beyond ICF to continue its development.  
* **Security & audits:** ICF will continue to support security audits for WasmVM  
* **Long-term support:** ICF is committed to ensuring CosmWasm’s long-term maintenance when it comes to existing stack relationships.

#### JS libraries: Telescope, Create-cosmos-app, cosmos-kit, starship, chain-registry NPM package, ts-codegen, CosmJS/InterchainJS, Interchain UI.

* **Core hand-off**: ICF will not continue funding or maintenance. Cosmology will retain ownership of the open source repositories, and will continue development. Interchain Inc. might continue to contribute code.  
* **Frontends & JS in Cosmos:** Interchain Inc. will re-evaluate the composition of the current frontend and JS stack, and explore tooling options.

Other secondary libraries and open-source toolings are being evaluated, and an updated set and proposal for maintenance will be posted in early 2025\. It’s important to note that stewards are open to seeking external funding to continue the development of libraries/components not supported by the ICF, and the ICF will support these efforts. While the ICF is selecting its areas of priority for the stack, and funding, the ecosystem remains open to contribute or develop any of these technologies.