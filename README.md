# Pancake swap Contracts for reference

    -Smartchef(pool factory) : https://bscscan.com/address/0x927158be21fe3d4da7e96931bb27fd5059a8cbc2#writeContract

    -SmartChefInitializable (single pool): https://bscscan.com/address/0x6ac2213F09A404c86AFf506Aa51B6a5BF1F6e24E#code

    -CakeVault : https://bscscan.com/address/0xa80240eb5d7e05d3f250cf000eec0891d00b51cc#code

    -Cake Token : https://bscscan.com/address/0x0e09fabb73bd3ade0a17ecc321fd13a19e81ce82#code
    -Masterchef : https://bscscan.com/address/0x73feaa1ee314f8c655e354234017be2193c9e24e#code

Steps To deploy :

-   deploy factory from core folder
-   deploy weth or using existing weth of any testnet
-   deploy router contract
-   call addLiquidity function where you need to pass token adderess(you can use existing erc20 tokens need to approve router contract)

factory contract : 0x4f7eaF42277DacE388618679fC57EdfCF402cd25
smartcheaf : 0x57AF1203FCd93bBC443436F573a614f8BCab1372
deposite tx : https://rinkeby.etherscan.io/tx/0xb627fbf5f548362975cf07d3c3bb93bb671a884547384142814c1708e8c08838
