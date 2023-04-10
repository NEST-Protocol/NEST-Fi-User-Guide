# NEST Fi User Guide

## Concept

### What is NEST Protocol?

The NEST Protocol is a decentralized trading infrastructure known as the martingale network. NEST uses smart contracts to eliminate market markers and LPs while providing traders with nearly infinite liquidity through risk sharing.

NEST Protocol includes three modules: NEST Oracle, NEST Assets, and NESTcraft. NEST Oracle provides decentralized on-chain prices. NEST Assets are generated and burned by NEST smart contract, and provide currency units for martingale transactions on NEST. NESTcraft converts various on-chain random sources into a super martingale function library and provides a variety of customizable martingale trading options.

The NEST protocol can be used for a variety of purposes, including decentralized contract exchanges, financial derivatives supermarkets, on-chain and off-chain risk hedging, the economic framework of Metaverse and GameFi, lottery, prop synthesis, and a few others.

## How to Play

### Connect Wallet

1. Open [NEST Fi official website](https://finance.nestprotocol.org/#/futures), choose the network you want to trade on, e.g. BSC (Binance Smart Contract Chain).
2. Then click the "Connect Wallet" button to connect to your wallet.
3. If your balance of NEST is lower than 1, you should use Swap function or buy NEST from exchange to add enough NEST for trading.
4. If you have not added NEST token to your wallet, when your mouse hovered on "Balance", the "Add NEST to your wallet" will show, click it and the NEST token will be added to your wallet.

![image5](https://raw.githubusercontent.com/NEST-Protocol/NEST-Fi-User-Guide/main/Image/NFUG5.png)

### Swap

You can switch to "Swap" tab to exchange between USDT and NEST token. The exchange rate is based on AMM mechanism, thus it will slightly vary from the centralized exchanges.

![image6](https://raw.githubusercontent.com/NEST-Protocol/NEST-Fi-User-Guide/main/Image/NFUG6.png)

### Futures

You can use $NEST to buy ETH/USDT and BTC/USDT futures here, with up to 50X leverage. We offer you 1-50 times leverage. The following steps show you how to buy futures on NEST Fi.

#### Connect your wallet

Connect your wallet through the "Connect Wallet" button on the page:
![image7](https://raw.githubusercontent.com/NEST-Protocol/NEST-Fi-User-Guide/main/Image/NFUG7.png)

#### Token

You need to have NEST tokens in your account to start trading. Orders can also be opened USDT and we will automatically convert to NEST for you during the process.

You can exchange directly through Swap: [https://finance.nestprotocol.org/#/swap](https://finance.nestprotocol.org/#/swap)

#### Open a position

Select the token pair you want to open a position and check the current market price through NEST Oracle, an utterly decentralized oracle. The opening price will be slightly different from the price provided by NEST Oracle based on risk compensation. Steps are as follows:

1. Choose "Long" or "Short" according to your expectation on which side you want to build your position.
2. Then, select the times of leverage.
3. Enter the amount to buy futures, and the minimum purchase is 50 $NEST or the equivalent in USDT.

![image8](https://raw.githubusercontent.com/NEST-Protocol/NEST-Fi-User-Guide/main/Image/NFUG8.png)

4. You need to approve it successfully before opening the position for the first time.
5. Service fee for opening positions: 0.05% of the position.

Entry Price: this is not the opening price, because the characteristics of the blockchain will eventually have some deviations from the open price.

Liq Price: Due to the market volatility, the actual liquidation price may be different from the theoretical liquidation price . Here is the theoretical liquidation price, for reference only.

#### Position management

After successfully opening a position, the information of your position will be displayed at the bottom. You can close your future positions at any time.

![image12](https://raw.githubusercontent.com/NEST-Protocol/NEST-Fi-User-Guide/main/Image/NFUG12.png)

You can manage your liquidation price by clicking "Add" to add margin. There is no service fee for margin calls.

![image13](https://raw.githubusercontent.com/NEST-Protocol/NEST-Fi-User-Guide/main/Image/NFUG13.png)

Base interest rate 
- 0.03%  per day
- 0.0000003472% per second

#### Close a position

1. You can close all your positions by clicking the “Close” button.
2. Service fee for closing: 0.05% of the position.

![image14](https://raw.githubusercontent.com/NEST-Protocol/NEST-Fi-User-Guide/main/Image/NFUG14.png)

#### Limit order

You can click the ‘Limit order’ to set a specific opening price. Service fee for Limit order: 0.05% of the position+15 NEST(execution fee).

1. Click “Limit order”.
2. In the expanded menu, Limit Price, adds the price for opening a position.
3. Once you create this order, we will charge you the principal, service fee, and execution fee in advance.
4. You can manage your limit orders in the “Order” section.
5. Once reaches the price you set, the protocol will automatically open the position for you.

![image15](https://raw.githubusercontent.com/NEST-Protocol/NEST-Fi-User-Guide/main/Image/NFUG15.png)

Please note that the following situations may occur, and the order will not be executed:

- The order doesn’t reach the price.
- The specified price is reached, but time is insufficient to execute the order.
- There is no executor.

#### Limit Order Management

After you have completed your limit orders, you can manage your own limit orders in 'Order'.

1. Click “Order” to check your limit order information.
2. Click "Edit" to change the opening price and no service fee for this process.
3. You can close a limit order before it has been executed by "Close", after which we will refund all the fees you have paid at the time of opening the position.

![image16](https://raw.githubusercontent.com/NEST-Protocol/NEST-Fi-User-Guide/main/Image/NFUG16.png)

Limit Order Execution Conditions
- Long:  triggered when market price <= limit price 
- Short: triggered when market price >= limit price 

#### Stop Loss and Take Profit orders

You can select "Stop order" at the same time when placing an order in the market order, after successful opening a position, it will be automatically closed according to the price you set.

Service fee for Stop Loss and Take Profit orders: 15 NEST(execution fee).

This fee will be deducted directly from the margin when the order is closed.

1. Click "Stop order".
2. In the expanded menu, “Take Profit” and “Stop Loss” adds the price for closing a position.

Long:

- Market price ≥ Take Profit will trigger Take profit
- Market price ≤ Stop Loss will trigger Stop profit

Short:

- Market price ≤ Take Profit will trigger Take profit
- Market price ≥ Stop Loss will trigger Stop profit

3. When your order is executed, we will charge an additional execution fee of 15NEST.

![image17](https://raw.githubusercontent.com/NEST-Protocol/NEST-Fi-User-Guide/main/Image/NFUG21.png)

4. You can manage your orders in the Positions list.
5. You also click the “Trigger” in the Positions list to open Stop loss and Take profit.

![image17](https://raw.githubusercontent.com/NEST-Protocol/NEST-Fi-User-Guide/main/Image/NFUG17.png)

Please note that the following situations may occur and the order will not be executed:

- The order doesn’t reach the price.
- The specified price is reached, but time is insufficient to execute the order.
- There is no executor.

#### Stop Loss and Take Profit order management

You can manage your Stop loss and Take profit orders in 'Positions' after you have completed the orders.

1. Click “Positions” to check your Stop Loss and Take Profit orders information.
2. Click "Edit" to change Stop Loss and Take Profit price, and no service fee for this process.
3. Click "Close" to close the Stop Loss and Take Profit order.

![image18](https://raw.githubusercontent.com/NEST-Protocol/NEST-Fi-User-Guide/main/Image/NFUG18.png)

4. When the Stop Loss and Take Profit order is not automatically executed, if the user actively closes the order, the execution fee will not be deducted.
5. When the Stop Loss and Take Profit order is automatically executed, the system will directly deduct the service fee and execution fee from your deposit.

#### Create execution price

Create Stop Loss and Take Profit order after opening a position： If you have a market order, you can click “Edit” to add the price.

1. After the market order is opened, you can create the Stop Loss and Take Profit order by clicking the "Trigger".
2. No fee will be charged when editing the market order to Stop Loss and Take Profit order. When the Stop Loss and Take Profit orders are automatically executed, the service fee and execution fee will be deducted from your margin.

![image20](https://raw.githubusercontent.com/NEST-Protocol/NEST-Fi-User-Guide/main/Image/NFUG20.png)

#### Futures service fee

- 0.05% of the position size for opening/closing.
- limit order 15 NEST execution fee.
- Stop Loss and Take Profit order + 15 NEST execution fee.

<!-- ### Video Guide

Open futures position on NEST Fi, here is the video guide.

<video src="./Image/UserGuide-Future.mov" controls="controls" width="600" height="400"></video> -->
