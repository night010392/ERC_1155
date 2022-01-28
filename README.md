# NFT_ERC_1155
## 1. Goal ##
Support both ERC20 and ERC721 token transaction.  
ERC20 token represents the client's bonus point token issued by specific financial institution.   
ERC721 NFT token represents the NFT products of sellers.  
This contract supports the following goals.  

1-1. Account can exchange any ERC20 token to other ERC20 token to other accounts.  
1-2. Account can exchange any ERC20 token to any ERC721 NFT token to other accounts.  
1-3. Contract supports mutiple token transactions in one transaction.  
## 2. Function ##
Each account can call the following function to fulfill their goals.
  
**2-1. balanceOfBatch**: represent the list of token's balance with list of specific token ID.  
**2-2. MintBatch**: mint list of token with list of token ID and amount.  
**2-3. safeBatchTransferFrom**: transfer list of token to specific account.  
## 3. Setting & Environment ##
Language: Solidity 0.5.17.    
Simmulation Platform: Geth 1.10.15.    
OS: Ubuntu 20.04.03.  
