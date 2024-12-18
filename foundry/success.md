fury@Furiosa:~/E/onchain-dao/foundry$ forge create --broadcast --rpc-url $QUICKNODE_RPC_URL --private-key $PRI
VATE_KEY --etherscan-api-key $ETHERSCAN_API_KEY --verify src/CryptoDevsNFT.sol:CryptoDevsNFT
[⠊] Compiling...
No files changed, compilation skipped
Deployer: 0xC63Ee3b2ceF4857ba3EA8256F41d073C88696F99
Deployed to: 0x9439caBc73e35b635d50f5837ee3D9A1aF70f487
Transaction hash: 0xfc6b4ec999eddb818cee3163138f1388dd39b94c099d5d3a9071917f2127f6ba
Starting contract verification...
Waiting for etherscan to detect contract deployment...
Start verifying contract `0x9439caBc73e35b635d50f5837ee3D9A1aF70f487` deployed on sepolia
Compiler version: 0.8.28

Submitting verification for [src/CryptoDevsNFT.sol:CryptoDevsNFT] 0x9439caBc73e35b635d50f5837ee3D9A1aF70f487.
Warning: Etherscan could not detect the deployment.; waiting 5 seconds before trying again (4 tries remaining)

Submitting verification for [src/CryptoDevsNFT.sol:CryptoDevsNFT] 0x9439caBc73e35b635d50f5837ee3D9A1aF70f487.
Submitted contract for verification:
Response: `OK`
GUID: `vedzbznw9wrymiwaalcxdajdtr879k22nfkvnklj5ju9genvlb`
URL: https://sepolia.etherscan.io/address/0x9439cabc73e35b635d50f5837ee3d9a1af70f487
Contract verification status:
Response: `NOTOK`
Details: `Pending in queue`
Warning: Verification is still pending...; waiting 15 seconds before trying again (7 tries remaining)
Contract verification status:
Response: `NOTOK`
Details: `Already Verified`
Contract source code already verified
fury@Furiosa:~/E/onchain-dao/foundry$

<!-- Marketplace -->

fury@Furiosa:~/E/onchain-dao/foundry$ forge create --broadcast --rpc-url $QUICKNODE_RPC_URL --private-key $PRIVATE_KEY --etherscan-api-key $ETHERSCAN_API_KEY --verify src/FakeNFTMarketplace.sol:FakeNFTMarketplace
[⠊] Compiling...
No files changed, compilation skipped
Deployer: 0xC63Ee3b2ceF4857ba3EA8256F41d073C88696F99
Deployed to: 0x913b288eb6A30B606B46bF17febAa53c8Ad19753
Transaction hash: 0x555cdf01d8312a41c6d846e6d808d5397f22e884c38297274538466a70ab7254
Starting contract verification...
Waiting for etherscan to detect contract deployment...
Start verifying contract `0x913b288eb6A30B606B46bF17febAa53c8Ad19753` deployed on sepolia
Compiler version: 0.8.28

Submitting verification for [src/FakeNFTMarketplace.sol:FakeNFTMarketplace] 0x913b288eb6A30B606B46bF17febAa53c8Ad19753.
Warning: Etherscan could not detect the deployment.; waiting 5 seconds before trying again (4 tries remaining)

Submitting verification for [src/FakeNFTMarketplace.sol:FakeNFTMarketplace] 0x913b288eb6A30B606B46bF17febAa53c8Ad19753.
Warning: Etherscan could not detect the deployment.; waiting 5 seconds before trying again (3 tries remaining)

Submitting verification for [src/FakeNFTMarketplace.sol:FakeNFTMarketplace] 0x913b288eb6A30B606B46bF17febAa53c8Ad19753.
Warning: Etherscan could not detect the deployment.; waiting 5 seconds before trying again (2 tries remaining)

Submitting verification for [src/FakeNFTMarketplace.sol:FakeNFTMarketplace] 0x913b288eb6A30B606B46bF17febAa53c8Ad19753.
Warning: Etherscan could not detect the deployment.; waiting 5 seconds before trying again (1 tries remaining)

Submitting verification for [src/FakeNFTMarketplace.sol:FakeNFTMarketplace] 0x913b288eb6A30B606B46bF17febAa53c8Ad19753.
Submitted contract for verification:
Response: `OK`
GUID: `xuvqvixjkvbenrusbg4vi188wysjknkfn5yaqmzpwyhrwbwgrm`
URL: https://sepolia.etherscan.io/address/0x913b288eb6a30b606b46bf17febaa53c8ad19753
Contract verification status:
Response: `NOTOK`
Details: `Pending in queue`
Warning: Verification is still pending...; waiting 15 seconds before trying again (7 tries remaining)
Contract verification status:
Response: `NOTOK`
Details: `Already Verified`
Contract source code already verified

<!-- DAO -->

fury@Furiosa:~/E/onchain-dao/foundry$ forge create --broadcast --rpc-url $QUICKNODE_RPC_URL --private-key $PRIVATE_KEY --etherscan-api-key $ETHERSCAN_API_KEY --verify --value 0.1ethe
r src/CryptoDevsDAO.sol:CryptoDevsDAO --constructor-args 0x913b288eb6A30B606B46bF17febAa53c
8Ad19753 0x9439caBc73e35b635d50f5837ee3D9A1aF70f487
[⠊] Compiling...
No files changed, compilation skipped
Deployer: 0xC63Ee3b2ceF4857ba3EA8256F41d073C88696F99
Deployed to: 0xAe05e1E11dB5153935a22E6894D1d1d267219AD6
Transaction hash: 0x6c4cb896ea9bddcac9632d1aef455ae56fe460b4cbe8c06256f9d36407d476e2
Starting contract verification...
Waiting for etherscan to detect contract deployment...
Start verifying contract `0xAe05e1E11dB5153935a22E6894D1d1d267219AD6` deployed on sepolia
Compiler version: 0.8.28
Constructor args: 000000000000000000000000913b288eb6a30b606b46bf17febaa53c8ad197530000000000000000000000009439cabc73e35b635d50f5837ee3d9a1af70f487

Submitting verification for [src/CryptoDevsDAO.sol:CryptoDevsDAO] 0xAe05e1E11dB5153935a22E6894D1d1d267219AD6.
Warning: Etherscan could not detect the deployment.; waiting 5 seconds before trying again (4 tries remaining)

Submitting verification for [src/CryptoDevsDAO.sol:CryptoDevsDAO] 0xAe05e1E11dB5153935a22E6894D1d1d267219AD6.
Warning: Etherscan could not detect the deployment.; waiting 5 seconds before trying again (3 tries remaining)

Submitting verification for [src/CryptoDevsDAO.sol:CryptoDevsDAO] 0xAe05e1E11dB5153935a22E6894D1d1d267219AD6.
Submitted contract for verification:
Response: `OK`
GUID: `37nstzxwbm6ui2pawftnhpxus6a8av3vbkwcej4b1fe4kkutvf`
URL: https://sepolia.etherscan.io/address/0xae05e1e11db5153935a22e6894d1d1d267219ad6
Contract verification status:
Response: `NOTOK`
Details: `Pending in queue`
Warning: Verification is still pending...; waiting 15 seconds before trying again (7 tries remaining)
Contract verification status:
Response: `OK`
Details: `Pass - Verified`
Contract successfully verified
