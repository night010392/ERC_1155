# ERC_1155
## 1. Goal ##
Support both ERC20 and ERC721 token transaction.  
ERC20 token represents the client's bonus point token issued by specific finicial institution.   
ERC721 NFT token represents the NFT products of seller.  
This contract support the following goals.  

1-1. Account can exchange one of ERC20 token to other ERC20 token to other accounts.  
1-2. Account can exchange any ERC20 token to any ERC721 NFT token to other accounts.  
1-3. Contract supports mutiple token transaction in one transaction.  
## 2. Function ##
Each account can call the following function to fulfill their goals.
  
**2-1. balanceOfBatch**: represent the balance of token with list of specific token ID.  
**2-2. MintBatch**: mint list of token with list of token ID and amount.  
**2-3. safeBatchTransferFrom**: transfer list of token to specific account.  
