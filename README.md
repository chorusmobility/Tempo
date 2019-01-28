# Tempo
Tempo is a Rust crate that automates the download and startup of a private Tezos network.
The Rust script downloads the *mainnet* Tezos docker image

This project is part of Chorus Mobility's suite of Tezos projects for autonomous vehicle solutions. 

## Requirements
To run Tezos through Docker the machine has to have Docker and Docker Compose installed and available.
Those should be installed using the OS package manager. 

## Building / Running
This crate can be used as a binary or as a library. The intended use case is initializing a private Tezos
network to evaluate smart contracts processed through an off-chain network.

You can either connect to the Tezos node directly (port `17700`) or use the Rust Tezos RPC bindings
that are under development by Chorus Mobility.
