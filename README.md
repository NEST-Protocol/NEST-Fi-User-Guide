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

You can use NEST to buy ETH/USDT and BTC/USDT futures here, up to 20x leverage.

We offer you 1X, 2X, 5X, 10X, 15X 20X leverage. The following steps show you how to buy futures on NEST Fi.

#### Connect your wallet

You can connect your wallet through the "Connect Wallet" button on the page:
![image7](https://raw.githubusercontent.com/NEST-Protocol/NEST-Fi-User-Guide/main/Image/NFUG7.png)

#### Token

You need to have NEST tokens in your account to start trading.

It can be exchanged directly on swap: [https://finance.nestprotocol.org/#/swap](https://finance.nestprotocol.org/#/swap)

#### Open a position

Select the token you want to open a position, and check the current market price through NEST oracle, which is a completely decentralized oracle. The opening price will be slightly different from the price provided by the NEST oracle price based on risk compensation.

1. Choose "Long" or "Short", and the leverage you want to use.
2. Then, select the times of leverage
3. Input the amount of NEST as collateral for this future, minimum 50 NEST.

![image8](https://raw.githubusercontent.com/NEST-Protocol/NEST-Fi-User-Guide/main/Image/NFUG8.png)

4. The first time you need to approve it successfully before opening the position. NESTFi options use 0 slippage to open positions. And opening a position charges 0.2% of the position cost.

While there is no price impact on the transaction, price movements between the time the transaction is submitted and its confirmation on the blockchain can cause slippage.

#### Position management

After successfully opening a position, the details of your position will be displayed at the bottom of the page. You can close your future positions at any time.

![image12](https://raw.githubusercontent.com/NEST-Protocol/NEST-Fi-User-Guide/main/Image/NFUG12.png)

You can manage your liquidation price by clicking "Add" to add to the position. A service fee of 0.2% is charged based on the cost of your added position.

![image13](https://raw.githubusercontent.com/NEST-Protocol/NEST-Fi-User-Guide/main/Image/NFUG13.png)

#### Close a position

You can close all your positions by clicking “Close” button. Once you choose to close, we will charge a 0.2% service fee from you.

![image14](https://raw.githubusercontent.com/NEST-Protocol/NEST-Fi-User-Guide/main/Image/NFUG14.png)

#### Limit order

You can open the ‘limit order’ to set a specific opening price. This operation will charge a 0.2% service fee and a 15 NEST execution fee.

1. Click “Limit order”.
2. Then add your opening price to the corresponding “Limit Price”
3. Once you create this order, we will charge you the principal, service fee, and execution fee in advance.
4. You can manage your limit orders in the “Order” section.
5. Once ‘Open Price’ reached the price you set, the protocol will automatically open the position for you.

![image15](https://raw.githubusercontent.com/NEST-Protocol/NEST-Fi-User-Guide/main/Image/NFUG15.png)

Please note that the following situations may occur, which cause nonexecutable orders.

- The order doesn’t reach the price
- The specified price is reached but time is insufficient to execute the order
- There is no executor

Although there is no price impact on the transaction, price movements between the submission of the transaction and its confirmation on the blockchain may result in slippage. Execution at the trigger price is not guaranteed.

#### Limit Order Management

After you have completed your limit orders, you can manage your own limit orders in 'order'.

1. The list is displayed in the ‘order’ and you can change your limit order at any time via "edit"
2. You can change your opening price without being charged any fees for this process
3. You can close a limit order before it has been executed by "close", after which we will refund all the fees you have paid at the time of opening the order.

![image16](https://raw.githubusercontent.com/NEST-Protocol/NEST-Fi-User-Guide/main/Image/NFUG16.png)

#### Stop Loss and Take Profit orders

You can open and close a position at the set price by checking "Stop order" at the same time as placing a market order. A 0.2% service charge on the value of the position and a 15 NEST execution fee will be applied to the stop loss, which will be deducted directly from the margin when the position is closed at the execution price.

1. Turn on "stop order"
2. Add the price of the close position to the opened trigger
3. Open the order and we will charge an additional execution fee
4. You can manage your execution prices in the list of positions
5. Once the 'Close price' was greater than the price you set, the protocol will automatically close the position

![image17](https://raw.githubusercontent.com/NEST-Protocol/NEST-Fi-User-Guide/main/Image/NFUG17.png)

Please note that the following situations may occur, which cause nonexecutable orders.

- The order doesn’t reach the price
- The specified price is reached but time is insufficient to execute the order
- There is no executor

Although there is no price impact on the transaction, price movements between the submission of the transaction and its confirmation on the blockchain may result in slippage. Execution at the trigger price is not guaranteed.

#### Stop Loss and Take Profit order management

You can manage your limit orders in 'positions' after you have completed them. If you have a market order, you can also add a stop-trigger execution price.

Modifying execution prices

1. The list is displayed in positions and you can change your execution price at any time by using the "edit" button

![image18](https://raw.githubusercontent.com/NEST-Protocol/NEST-Fi-User-Guide/main/Image/NFUG18.png)

2. Modify the execution price of the close positions, we do not charge any additional fees for this process
3. The user can close a stop loss order

![image19](https://raw.githubusercontent.com/NEST-Protocol/NEST-Fi-User-Guide/main/Image/NFUG19.png)

4. When the stop profit and stop loss are not executed, the user actively closes the position, the service fee and execution fee for the stop profit and stop loss will not be refunded
5. When the stop profit and stop loss are automatically executed, the system will directly deduct the service fee and execution fee from your margin.

#### Create execution price

1. After the market order is opened, you can create your own execution price through the "trigger" at any time
2. We do not charge fees when creating an execution price. When the execution price is greater than the execution price, the service fee and execution fee will be deducted from your margin.

![image20](https://raw.githubusercontent.com/NEST-Protocol/NEST-Fi-User-Guide/main/Image/NFUG20.png)

#### Cost

- 0.2% of the position size for opening/closing
- When opening a position with a limit order, besides 0.2% position fee, additional 15 NEST will be charged for the limit order execution.
- When closing a position with a stop order, besides 0.2% position fee, additional 15 NEST will be charged for the stop loss/take profit order execution.


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
