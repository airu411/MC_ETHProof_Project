# MyToken

The project is MyToken.sol and contains a very simple creation of a token.

## Description

This is the code I did for my Solidity project in fulfillment of the ETH Proof Beginner course in Metacrafters. 
There are two main functions: `mint` and `burn`. 
The `mint` function is used to increment the total supply and the sender's balance, while the `burn` function is used 
to decrement the total supply and the sender's balance if the sender's balance satisfies a requirement. 
This was made with the use of the Remix environment. 

## Getting Started

### Setting Up 

1. To start, go to the Remix website at https://remix.ethereum.org/

2. Then, copy the code from the MyToken.sol file in this project and paste it onto a new file. To create a new file, 
simply right click the left-side pane where you can see the files and folders and click on `New File`. After which, assign 
a name to your new file. 

3. Then, find `Solidity Compiler` on the leftmost side and click it. Then, click on `Compile {filename}` where {filename} 
refers to the name of your recently created file containing the code. In my case, it was `MyToken.sol`.

4. After compiling, find `Deploy & Run Transactions` on the leftmost side, which should be right under the `Solidity Compiler` icon. 
When you have found it, click on `Deploy`.

### How to Use

After deploying, you can add values and addresses to `mint` and `burn`
(as shown in the screenshots below) to test if the project is working properly. 

![image](https://github.com/airu411/MC_ETHProof_Project/assets/159874160/f0a70861-207e-43f9-a509-19d037b2bee3)

![image](https://github.com/airu411/MC_ETHProof_Project/assets/159874160/1b13eb28-0982-4e52-a622-83b66f32526a)

## Help

If you encounter any problems or issues, you may check the official documentation at:

`Solidity v0.8.18 - https://docs.soliditylang.org/en/v0.8.18/`

The code uses this version (0.8.18) of Solidity and may not work as intended with other versions. It would be best to also use 
this version by specifying it through using `pragma` at the beginning of your file. 

## Author

@airu411
