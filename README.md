# Circom Example - Rock Paper Scissors

This repository contains a simple circuit demonstrating how to start using Circom. The example showcases a Rock Paper Scissors game to illustrate how to write your own Zero-Knowledge Proofs (ZKPs) using Circom.

## Getting Started

To begin, review the `RPS.circom` file which contains the necessary logic for this circuit. This example also includes a Node.js project that imports the [CircomLib](https://github.com/iden3/circomlib), a collection of circuits you can use to build your own ZK circuits.

## Installing Circom

1. Install Rustup if you don't have it on your system:
    ```sh
    curl --proto '=https' --tlsv1.2 https://sh.rustup.rs -sSf | sh
    ```

2. Clone the Circom repository in your preferred directory:
    ```sh
    git clone https://github.com/iden3/circom.git
    ```

3. Navigate to the Circom directory and build the project:
    ```sh
    cd circom
    cargo build --release
    ```

4. Install the Circom binary:
    ```sh
    cargo install --path circom
    ```

5. Verify your installation:
    ```sh
    circom --help
    ```

## Installing SnarkJS

Zero-Knowledge Proofs can be divided into two main components: Constraint Generation and Proof Generation. SnarkJS is a crucial library for Proof Generation, capable of generating proofs using Groth16, Plonk, or FFLonk. Learn more about SnarkJS [here](https://github.com/iden3/snarkjs).

To install SnarkJS globally on your device, run:
```sh
npm install -g snarkjs
```

## Compiling the Circuit
To compile this circuit, go through a [Powers of Tau] ceremony and generate a Solidity file. Refer to the commands.txt file for detailed instructions to get you started.

## Resources
[Circom Documentation](https://docs.circom.io/getting-started/installation/) <br/>
[Understanding ZKPs 1](https://dev.to/tonyolendo/the-complete-full-stack-guide-to-getting-started-with-zero-knowledge-proofs-using-circom-and-zk-snarks-part-1-53gi) <br/>
[Understanding ZKPs 2](https://dev.to/tonyolendo/the-complete-full-stack-guide-to-getting-started-with-zero-knowledge-proofs-using-circom-and-zk-snarks-part-2-58o)
