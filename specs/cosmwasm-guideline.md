## I. Chapter 1: Write and upload a NFT contract (13 weeks to complete)
* Purpose: write a NFT contract and upload that contract to a local testnet with smart contract capability

1. __Group 1__: Setup a Smart Contract project with CosmWasm
* Lesson 1: Generating a CosmWasm project
* Lesson 2: Introduction to CosmWasm project file structure
* Lesson 3: Introduction to NFT's implementation idea and CW-721

2. __Group 2__: Entry point (lib.rs || contract.rs)
* Lesson 4: Introduction to contract entry_point and overall flow
* Lesson 5: instantiate, execute, query entry_point
* Lesson 6: Entry point variable (DepsMut, Deps, Env)
* Lesson 7: Entry point variable (MessageInfo, Msg)

2. __Group 3__: State (To save state of contract to database) (state.rs)
* Lesson 8: Introduction to data Structure of State
* Lesson 9: Introduction to cosmwasm_std::Storage
* Lesson 10: Introduction to cw_storage_plus storage format
* Lesson 11: Saving State to cosmwasm_std::Storage (cw_storage_plus::Item<'a, u64>)

3. __Group 4__: Msg
* Lesson 12: Introduction to Msg
* Lesson 13: Msg schema generation
* Lesson 14: Introduction to InstantiateMsg
* Lesson 15: Introduction to ExecuteMsg
* Lesson 16: Introduction to QueryMsg

4. __Group 5__: Execute
* Lesson 17: Writing implementation for "instantiate"
* Lesson 18: Writing implementation for "transfer" NFT
* Lesson 19: Writing implementation for "mint" NFT

5. __Group 6__: Query
* Lesson 20: Writing implementation for "owner_of"
* Lesson 21: Writing implementation for "nft_info"

6. __Group 7__: Contract error
* Lesson 22: Introduction to contract error

7. __Group 8__: Contract testing
* Lesson 23: Setup contract for testing
* Lesson 24: Test instantiation of contract
* Lesson 25: Test minting of contract

8. __Group 9__: Instantiating contract on local testnet of Juno
* Lesson 26: Store and instantiate contract on testnet

## II. Chapter 2: Interact with NFT contract (CLI and cosmJS)