# Assignment-Module-19

## Purpose

To build an application that allows employers to hire a web3 professional and pay them using ther over the Ethereum blockchain.

## Results

I chose to hire "Lane" for 5.00 hours. Her hourly rate is 0.2 ether and her Ethereum address is 0xaC8eB8B2ed5C4a0fC41a84Ee4950F417f67029F0.

The total wage payable in ether is 1.0.

In the following screenshot, ganache at block 0 is shown:

![](https://github.com/malrepos/Assignment-Module-19/blob/main/Images/ganache_block_0.JPG)

Upon sending the transaction in the strreamlit interface a validated transaction hash was displayed:

![](https://github.com/malrepos/Assignment-Module-19/blob/main/Images/streamlit_validated_transaction_hash.JPG)

Ganache at block 1 with the transaction sent and my account updated:

![](Images\ganache_block_1.JPG)

Here I display the expanded block 1 details:

![](Images\ganache_block_1_details.JPG)

Here I display the transaction details:

![](Images\ganache_transaction_details.JPG)

## Instructions

- Update your .env file by setting the MNEMONIC variable to the mnemonic from your ganache application.

- In the repo folder containing the krypto_jobs.py file, open a new bash terminal and type:

`streamlit run krypto_jobs.py`

- select a candidate.

- select the number of hours to hire the the candidate.

- Click "Send Transaction"

- In ganache, selct Transactions to view the transaction details

- Refresh the streamlit application to see the updated account balance in ether.
