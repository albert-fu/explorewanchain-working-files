# Wanchain Official Wallet Guide


1. [Cross Chain Transactions](#crosschain)   
  * [ETH to Wanchain](#ethtowan)
  * [WETH to Ethereum](#wethtoeth)
1. [Normal Wanchain Transactions](#wan)
1. [Normal Ethereum Transactions](#eth)   
1. [Private Transactions](#private)   



<div id="crosschain"></div>  

## Cross-Chain Transactions

Crosschain transactions are under this tab

![](media/Wanwalletcrosschain.png)

Before you make a crosschain transaction, please check WAN and ETH balance in your account in Wanwallet GUI or with links below.

Main network：

* ETH: https://etherscan.io/

* WAN: https://www.wanscan.org/


Test network：

* ETH: https://rinkeby.etherscan.io/

* WAN: http://13.58.108.244/

<div id="ethtowan"></div>  

### Send ETH to Wanchain

Click the "ETH >> WETH" tab below to send ETH to Wanchain

![](media/WanwalletETHtoWanchain.png)

Enter your password then press “OK” button to send the transaction.

![](media/WanwalletsendTransaction.png)


#### Confirm/Cancel the transaction

In the "Transaction history" tab, click on the “**Confirm**" button to finalize the cross-chain transaction process once it _**turns red**_.

![](media/Wanwalletconfirmcanceltransaction.png)

If you do not confirm before the HTLC countdown ends, it means you choose to cancel the transaction and refund the ETH from the locked account. 
The "Confirm" button changes to "**Cancel**" and you can click it to cancel the transaction once it _**turns red**_



#### Option A) Confirm transaction

Once the “Confirm” button turns **red**, click it to access “**Confirm Transaction**” page.

![](media/Wanwalletconfirmtransaction1.png)

Enter the password then click “OK” button to finalize transaction 

![](media/Wanwalletconfirmtransaction2.png)



#### Option B) Cancel transaction

Once the “Cancel” button turned **red** (after countdown ends), click it to access “**Cancel Transaction**” page.

![](media/Wanwalletcanceltransaction1.png)

Enter the password then click “OK” button to cancel the transaction 

![](media/Wanwalletcanceltransaction2.png)

<div id="wethtoeth"></div>  

### Send WETH to Ethereum

If you have ETH balance on Wanchain (WETH balance), you can send WETH back to Ethereum.

Click the "WETH >> ETH" tab below to perform this kind of cross-chain transaction.    

![](media/WanwalletWETHtoETH.png)

The process is similar to the ETH to Wanchain one, please refer to section 7 for details about how to confirm or cancel the transaction.


<div id="wan"></div>  

## Normal Wanchain transactions

To make a regular on chain Wanchain transaction, click the "Transfer" button from the home screen of the wallet. 

![](media/wanhome.jpg)

Fill in "To" and "From" accounts, "Amount", and "Fee", then click the "Send" button to complete your transaction.

![](media/wantrans.jpg)

<div id="eth"></div> 

## Normal Ethereum transactions

You can perform Ethereum to Ethereum transactions through the official Wanchain wallet.

Click the "Normal transaction" tab below, fill source and destination accounts, transaction amount, fee preference, then click "SEND"

![](media/WanwalletETHtoETH.png)

<div id="private"></div> 

## Private Transactions

>#### NOTE: Public & Private Addresses  
>Transactions made using public addresses are, as the name suggests, publicly visible. Transactions made using your private address (do not confuse with private key) on the other hand, are not be publicly visible.  
>**Public Address Example**  
>`0xefe000C1b9f9ca9bf063857aAF5fCb7B8A25eaA1`  
>**Private Address Example:**  
>`0x02bddd6c139a10c5c9e81d1d6438dd26bc4a26824a2c729819d21ee1fca8b2dbc203936c798596ac4adcbe89e96c88397894b6dfab14a95ea7e137c31f56b9c81255`  

### Sending Private Transactions

**Step 1**: Click the **Transfer** button on the right to start a private transaction


![](media/WanchainPrivate1.png)

**Step 2**: Click **Switch to Private** in the **From** field and enter a **Private address** in the **To** field. The Recipient will need to share their Private address beforehand. Enter the amount of WAN to send and click **SEND** to start the private transaction. 


![](media/WanchainPrivate2.png)

**Step 3**: Enter the **Password** for your account and click **SEND TRANSACTION** to send a private transaction. 

![](media/WanchainPrivate3.png)


**Step 4**: The latest transaction is displayed at the top of the **Transaction List**. 

![](media/WanchainPrivate4.png)

**Step 5**: On the **Wanchain Explorer**, the **Value**  and the **To** address are masked and hidden from the public.

![](media/WanchainPrivate5.png)


### Receiving Private Transactions

**Step 1**: Click **Details** to view detailed account settings

![](media/WanchainPrivate6.png)


**Step 2**: Click **Get OTA** to begin the process to receive a private transaction.

![](media/WanchainPrivate7.png)

**Step 3**: Enter the **Password** for your Account and Click **OK**. 

![](media/WanchainPrivate8.png)

**Step 4**: Wait a few minutes for the transaction to be processed and click **Redeem**. 

![](media/WanchainPrivate10.png)

**Step 5**: Click **Redeem** to accept the transaction.

![](media/WanchainPrivate11.png)

**Step 6**: The transaction details are show under **Redeem from OTAs**

![](media/WanchainPrivate12.png)