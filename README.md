# NEST Fi User Guide

## Concept

### NEST Probability Virtual Machine

NEST Probability Virtual Machine (PVM) is a virtual machine-like structure based on the basic function library. Developers can develop various exciting applications based on the function library, similar to Ethereum virtual machine (EVM) programming.

NEST inherited the genes of Ethereum. The essence of EVM is that each program is a combination of some basic codes, which can be called as long as a certain gas fee is paid. The income of each product on the PVM can be regarded as a linear combination of some basic income functions, and this income can be obtained as long as a certain cost (that is, the discounted value of this income) is paid. The underlying logic of PVM is the same as that of EVM, which means that all EVM development can be implemented on PVM.

Check the PVM's [whitepaper](https://finance.nestprotocol.org/The_White_Paper_of_NEST_PVM.pdf) for more details.

## How to Play

### Connect Wallet

1. Open [NEST Fi official website](https://finance.nestprotocol.org/#/futures), choose the network you want to trade on, e.g. BSC (Binance Smart Contract Chain).
2. Then click the "Connect Wallet" button to connect to your wallet.
3. If your balance of NEST is lower than 1, you should use Swap function or buy NEST from exchange to add enough NEST for trading.

- If you have not added NEST token to your wallet, when your mouse hovered on "Balance", the "Add NEST to your wallet" will show, click it and the NEST token will be added to your wallet.

![image5](https://raw.githubusercontent.com/NEST-Protocol/NEST-Fi-User-Guide/main/Image/NFUG5.png)

### Swap

You can switch to "Swap" tab to exchange between USDT and NEST token. The exchange rate is based on AMM mechanism, thus it will slightly vary from the centralized exchanges.

![image6](https://raw.githubusercontent.com/NEST-Protocol/NEST-Fi-User-Guide/main/Image/NFUG6.png)

### Futures

You can use NEST to buy ETH/USDT and BTC/USDT futures here, up to 5x leverage.

The following steps show you how to buy futures on NEST Fi:

1. The market price of token pair is from [NEST Oracle](https://nestprotocol.org/#/docs/NEST-Oracle/Concept.md), a truly decentralized oracle. The opening price varies slightly from the price NEST oracle provides according to risk compensation.
2. Choose "Long" or "Short", and the leverage you want to use.
3. Then, input the amount of NEST as collateral for this future, minimum 50 NEST.
4. Approve and open the position.

![image7](https://raw.githubusercontent.com/NEST-Protocol/NEST-Fi-User-Guide/main/Image/NFUG7.png)

After you open the position successfully, the detail of your position will shows at the bottom of the page. You can close your future position at any time you want.

![image8](https://raw.githubusercontent.com/NEST-Protocol/NEST-Fi-User-Guide/main/Image/NFUG8.png)

### Options

NEST Fi's options are based on NEST Probability Virtual Machine (PVM), which provides options with infinite liquidity. NEST Fi support ETH/USDT and BTC/USDT options.

The following steps show you how to buy options on NEST Fi:

1. Similar to the future, option's market price of token pair is also from [NEST Oracle](https://www.nestprotocol.org/).
2. Choose "Call" or "Put" option you want to buy.
3. Choose the exercise time and strike price of the option. You should know, NEST Fi's options are [European Option](https://www.investopedia.com/terms/e/europeanoption.asp#:~:text=A%20European%20option%20is%20a,of%20or%20sell%20the%20shares.).

- Exercise Time: You cannot strike your option until this date, but you can sell this option to NEST Fi network before the exercise time.
- Strike Price: The final payoff depends on the strike price.

4. Then, input the amount of NEST as your payment and the option shares will show on the right.

![image9](https://raw.githubusercontent.com/NEST-Protocol/NEST-Fi-User-Guide/main/Image/NFUG9.png)

5. Approve and buy the option.

![image10](https://raw.githubusercontent.com/NEST-Protocol/NEST-Fi-User-Guide/main/Image/NFUG10.png)

After you buy the option successfully, the detail of your position will shows at the bottom of the page. You can sell your option before exercise time.

![image11](https://raw.githubusercontent.com/NEST-Protocol/NEST-Fi-User-Guide/main/Image/NFUG11.png)

### Video Guide

Open futures position on NEST Fi, here is the video guide.

<video src="./Image/UserGuide-Future.mov" controls="controls" width="600" height="400"></video>
