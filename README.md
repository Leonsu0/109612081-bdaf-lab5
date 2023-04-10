# 109612081-bdaf-lab5
### This is my ERC20 token contract
### token contract address: 0x9b3c0d4dec4f092290ba39d4a4e4a56827e5d33b
#### you can deploy it on chain with Remix IDE, and publish & verify on etherscan, and than you can interact with your ERC20 token contract. 

1. Develop an ERC20 token: 
2. Deploy your ERC20 token. Mint 1000 tokens (i.e. 1000 * 10^18 units) to yourself. (Record the address of your own token)
   EggToken:
	 * tx:`0xd2498ce3136143653f3b1c567d3bdc5b0969491b29661851a38a7f656c17d0f7`
	 *  add:`0x9b3c0d4dec4f092290ba39d4a4e4a56827e5d33b`
3. Go to Aave, lend ETH and borrow DAI out (Record your Borrow transaction)
4. Go to Etherscan and get the address of the DAI (Record the address of the DAI token)
   Aave:
	 * lend tx: `0x828953778e1ffe57aba7ac0319f3ec5dff931a609ba127bc3e86320999d5be89`
	 * borrow tx:`0xb9d36dcc499f8bdaba1b7a762233375a9f20e5283f161b249f3ce3eee34242b3`
	 * DAI add:`0xBa8DCeD3512925e52FE67b1b5329187589072A55`
5. Go to UniswapV2 to create a new liquidity pair
   Uni:
	  * pool tx:`0xafda7d2029a6d29d8f1eba12db2c77777843bcac935b069358832125ce69bcd2`
	 *  pool token add:`0x4C4CB2bBbB0fafFe49D768a3bb71e48Ce8B84e19`
	 *  swap egg to dai tx: `0x4eb4c5c1bd5d7695608bfe74237d875b2bd8c95e48734150aca2e9f09513e7ed`
	  * swap dai to egg tx:`0x9954ec922bdef9b0d516b299bb9f2be86c8b2e428458ae3625135f8341bde6aa`
6. Create a Safe (Gnosis’s multiSig solution) on Goerli (Record the address of your Safe multiSig address)
   safe:
	  * create tx:`0xe5901037a205c6fee2cdf3abb4b67ceacaa09437a0f3f2a44cc9bed297c529c7`
	  * add:gor:`0xbd3614BF6445681470e1b02B027d32aCefFfb710`
7. Transfer Ownership of your token to your Safe multiSig address. (Record the transaction)
    * Transfer egg token owner tx:`0x2f4ef7ded3af519e9cc75d119328ae89a1bfffd3d7468725dd48bfb9e5398022`
8. Mint 10000 of your tokens by using your Safe multiSig address to your own address (Record the transaction)
   Mint 10000 egg with multisig safe 
	     * tx:`0x59f0d011a5be7c565f0dc428e4549079b67900c163c0d016709eee8d746cccb1`
	    s * afeTxHash:0x4390f39dd2bb33fea4fc9b77810c802ea090444acc1e8d24ef5c108f6789e0a9`
9. Sell all of the 10000 tokens into the Uniswap pool you created. (Record the transaction)
   Sell 10000 egg to pool:
	  * tx:`0x6dfcede7462d1ab3ac991765a8293f27706eb9103194929a3c2cef1bc7fb5ede`

   
