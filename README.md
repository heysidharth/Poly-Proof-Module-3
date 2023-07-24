# Poly-Proof-Module-3

# ZK SNARK Designer
Polygon is asking you to design a new zkSNARK circuit that implements some logical operations. You need to implement the circuit and deploy a verifier on-chain to verify proofs generated from this circuit
For this project, you will create a circuit using the circom programming language that implements the logical gate

# Logical Gate Circom Circuit with ZK-SNARK Proof

This project implements a logical gate circuit using the circom programming language. The circuit implements the following truth table:
```
A B X Y Q
0 0 0 1 1
0 1 0 0 0
1 0 0 1 1
1 1 1 0 1
```

The goal of the project is to prove that you know the inputs A=0 and B=1 that yield a output as true value thorugh logic gate concept.

# Installing

To get started with the project, follow these steps:

1. clone the circom repository :
   `https://github.com/iden3/circomlib.git`
   
2. Install the required dependencies :
   `npx hardhat circom`
   
3. Then deploy the scripts
   `npx hardhat run scripts/deploy.ts`
   
5. Testing the network deploy
   `npx hardhat run scripts/deploy.ts --network Mumbai`

## Output
If you followed all the steps correctly you will get a contract address where it is deployed and verifier result: true.


## Author 

Sidharth Samantaray

## Walkthrough Video
https://www.loom.com/share/02791825c7b3418b8074bf7e886034bd
