# Unit 20 - "Joint Savings Account"

![alt=“”](Images/20-5-challenge-image.png)


## Interact with the Deployed Smart Contract

1. Set accounts.

![set accounts](Execution_Results/set_accounts_1_2.png)

2. Test the deposit functionality of your smart contract by sending the following amounts of ether. After each transaction, use the `contractBalance` function to verify that the funds were added to your contract:

    * Transaction 1: Send 1 ether as wei.
![account 1 1 ether as wei](Execution_Results/account_1_1_ether_as_wei.png)
    * Transaction 2: Send 10 ether as wei.
![account 2 10 ether as wei](Execution_Results/account_2_10_ether_as_wei.png)
    * Transaction 3: Send 5 ether.
![account 1 5 ether](Execution_Results/account_1_5_ether.png)
 

3. Once you’ve successfully deposited funds into your contract, test the contract’s withdrawal functionality by withdrawing 5 ether into `accountOne` and 10 ether into `accountTwo`. After each transaction, use the `contractBalance` function to verify that the funds were withdrawn from your contract. Also, use the `lastToWithdraw` and `lastWithdrawAmount` functions to verify that the address and amount were correct.

    * Withdraw 5 ether into account 1.
    ![withdraw 5 ether account 1](Execution_Results/withdraw_5_ether_account_1.png)
    * Withdraw 10 ether into account 2.
    ![withdraw 10 ether account 2](Execution_Results/withdraw_10_ether_account_2.png)



