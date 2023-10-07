<base target="_blank">

# EVM-Create-Tokens
 Create tokens on any of the EVM blockchains
* Install MetaMask in your webbrowser if you haven't already
<!-- links -->
>> [MetaMask - Download](https://metamask.io/download)
<!-- links -->
>> [setup MetaMask](https://support.metamask.io/hc/en-us/articles/360015489531-Getting-Started-With-MetaMask)
* click MetaMask and make sure you have the Sepolia network selected
<!--Images-->
![MetaMask_Make-sure-Sepolia-network-is-selected](MetaMask_Make-sure-Sepolia-network-is-selected.jpg)
* goto Alchemy and sign up for a free account to be able to use their free Sepolia test network ETH
<!-- links -->
>> [Alchemy - Signup](https://auth.alchemy.com/signup)
<!--Images-->
![Alchemy_Signup](Alchemy_Signup.jpg)
* goto the Sepolia Faucet and faucet some free Sepolia ETH
<!-- links -->
>> [Sepolia Faucet](https://sepoliafaucet.com)
<!--Images-->
![Sepolia Faucet](Sepolia-Faucet.jpg)
* goto OpenZepplin's wizard page
<!-- links -->
>> [OpenZepplin - Wizard](https://wizard.openzeppelin.com)
* Fill in the following
    1. Name
    1. Symbol
    1. Premint
    1. Security Contact
* click 'Open in Remix'
<!--Images-->
![OpenZeppelin](OpenZeppelin.jpg)
* in Remix click Compile contract-blahblah (blahblah will be numbers and letters)
<!--Images-->
![Remix_click-Compile](Remix_click-Compile.jpg)
* click 'Deploy & run transactions' symbol on the left
<!--Images-->
![Remix_click-Deploy](Remix_click-Deploy.jpg)
* choose 'Injected Provider - MetaMask' in the ENVIRONMENT drop-down on the left
<!--Images-->
![Remix_Select-Injected-Provider](Remix_Select-Injected-Provider.jpg)
* make sure the correct wallet is selected (if you have more than 1 in MetaMask), then click Next
<!--Images-->
![MetaMask_Next](MetaMask_Next.jpg)
* click Connect
<!--Images-->
![MetaMask_Connect](MetaMask_Connect.jpg)
* click Deploy on the left
<!--Images-->
![Remix_click-Deploy-button](Remix_click-Deploy-button.jpg)
* click Confirm on MetaMask
<!--Images-->
![MetaMask_Confirm](MetaMask_Confirm.jpg)
* wait for Remix to show the green check mark on the bottom signifying that your contract has been deployed
* click view on ehterscan (just above the green check mark)
<!--Images-->
![Remix_view-on-etherscan](Remix_view-on-etherscan.jpg)
* you new token has been deploy, congratulations, now for importing it into your MetaMask
* click your Token name on the Etherscan page
<!--Images-->
![Etherscan](Etherscan.jpg)
* click the copy icon on your Tokens contract page
<!--Images-->
![Etherscan_Token-page](Etherscan_Token-page.jpg)
* back in MetaMask, click the 'Import tokens' link
<!--Images-->
![MetaMask_Import-tokens](MetaMask_Import-tokens.jpg)
* paste the contract that you copied to your clipboard and click the 'Add custom token' button
<!--Images-->
![MetaMask_click-Add-custom-token](MetaMask_click-Add-custom-token.jpg)
* click 'Import tokens' button
<!--Images-->
![MetaMask_click-Import-tokens](MetaMask_click-Import-tokens.jpg)
* you should now see your custom token in MetaMask
<!--Images-->
![MetaMask_click-Final-step](MetaMask_click-Final-step.jpg)
### Congratulations, on making your first custom token on the Sepolia ETH test network
#### Notes
* This demonstrates using the Sepolia ETH test network, but will work on any of the EVM test network or their main networks (BNB, ETH, POLYGON, etc.)
