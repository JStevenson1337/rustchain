To build smart contracts in Rust on the Cardano blockchain, you'll be working with Plutus, which is a smart contract development platform for Cardano. Plutus supports both Haskell and Rust for writing smart contracts. Below are the steps to get started with building smart contracts in Rust on the Cardano chain:

1. Set up the development environment:
   - Install Rust: If you don't already have Rust installed, you can get it from the official Rust website (https://www.rust-lang.org/tools/install).

2. Install Plutus development tools:
   - Install the Plutus development environment. Plutus Playground is a web-based tool for testing and developing Plutus smart contracts. You can find Plutus Playground on GitHub (https://github.com/input-output-hk/plutus).

3. Create a Rust project:
   - Create a new Rust project for your smart contract using the `cargo` tool. You can use `cargo new <project-name>` to create a new project.

4. Add Plutus dependencies:
   - To interact with the Cardano blockchain, you'll need to use the Plutus smart contract development libraries for Rust. Add these dependencies to your `Cargo.toml` file.

   ```toml
   [dependencies]
   cardano = "X.X.X"
   cardano-wallet = "X.X.X"
   ```

   Replace "X.X.X" with the version numbers that are compatible with your Plutus development environment.

5. Write your smart contract:
   - Write your smart contract logic in Rust. Ensure it adheres to the Plutus smart contract development guidelines and integrates with the Plutus libraries.

6. Test your smart contract:
   - Use Plutus Playground to test and simulate the behavior of your smart contract. You can write and run scripts in the Plutus Playground environment to verify your contract's functionality.

7. Compile and build your smart contract:
   - Use the Rust build tools, such as `cargo`, to compile your smart contract code into a format that can be deployed on the Cardano blockchain.

8. Deploy your smart contract:
   - Deploy your smart contract on the Cardano blockchain by using the Cardano CLI or wallet software. Follow the Cardano documentation and guides for deploying contracts.

9. Interact with your smart contract:
   - You can interact with your deployed smart contract using Cardano's transaction submission and query APIs. Implement a frontend or a command-line interface to interact with your contract.

10. Test thoroughly and deploy on the mainnet:
    - After rigorous testing on testnets and making sure your smart contract works as expected, you can deploy it on the Cardano mainnet.

Keep in mind that smart contract development can be complex, and it's important to thoroughly test your contracts on testnets and understand the security implications. You should also refer to the official Cardano and Plutus documentation and community resources for up-to-date information and best practices, as the development environment and tooling may change over time.