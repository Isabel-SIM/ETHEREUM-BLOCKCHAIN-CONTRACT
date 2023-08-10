<h1> Joint Savings Contract </h1>


## Background
Our fintech initiative is leveraging a cross-border, Ethereum-compatible blockchain designed to integrate seamlessly with financial institutions. One of our pivotal solutions is the automation of joint savings accounts via smart contracts. The joint savings contract represents this endeavour, enabling two user addresses to manage a shared account.

## Contents
- The JointSavings Smart Contract: A structured Solidity contract to manage joint savings functionality.
- Execution_Results Folder: A directory containing evidence of successful transaction operations, demonstrating the contract's functionality.

## How to Use

1. Setting up the contract:
   - Open the joint_savings.sol file within the Remix IDE.
   - You'll encounter the JointSavings contract, which houses essential state variables and functions.
   - Account Holders: accountOne and accountTwo represent the primary account holders.
   - Activity Metrics: Track the last withdrawal operation and its associated amount.
   - Balance: contractBalance provides the current account balance.
     
2. Compilation and Deployment
   - Compile the contract in Remix IDE.
   - Navigate to “Deploy & Run Transactions” and select “JavaScript VM” as the environment.
   - Click on "Deploy" to initiate the contract on the blockchain.

3. Contract Interaction
   - Define the authorized users using the setAccounts function. For testing purposes:
   - account1: 0x0c0669Cd5e60a6F4b8ce437E4a4A007093D368Cb
   - account2: 0x7A1f3dFAa0a4a19844B606CD6e91d693083B12c0
   - Test the deposit function by adding amounts of 1 ether, 10 ether, and 5 ether sequentially.
   - To verify the contract's integrity, attempt withdrawals to each account.

Note: Ensure familiarity with ether and wei conversions. You can utilise tools like Ethereum Unit Converter if necessary.

## Contract Code

![MAIN PAGE](https://github.com/Isabel-SIM/WEEK-TWENTY-HOMEWORK/blob/main/Images/1.png) <br>
<br>
Contract Interaction: <br>
(https://github.com/Isabel-SIM/WEEK-TWENTY-HOMEWORK/blob/main/Images/2.png) <br>
(https://github.com/Isabel-SIM/WEEK-TWENTY-HOMEWORK/blob/main/Images/2.2.png) <br>
(https://github.com/Isabel-SIM/WEEK-TWENTY-HOMEWORK/blob/main/Images/3.png) <br>
(https://github.com/Isabel-SIM/WEEK-TWENTY-HOMEWORK/blob/main/Images/3.3.png) <br>
(https://github.com/Isabel-SIM/WEEK-TWENTY-HOMEWORK/blob/main/Images/4.png) <br>
(https://github.com/Isabel-SIM/WEEK-TWENTY-HOMEWORK/blob/main/Images/4.4.png) <br>

