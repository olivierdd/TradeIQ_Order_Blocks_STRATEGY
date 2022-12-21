# TradeIQ_Order_Blocks_STRATEGY
 
This pinescript replicates the trading strategy from TradeIQ published on YouTube here : https://www.youtube.com/watch?v=8LocxM2_YWk

At this stage the script is under development :
- [done]	Objective 1 : replicate the order block computation, write code to identify when price touches an OB (without disabling it) and generate buy / sell signal
- [ongoing]	Objective 2 : extend code to generate buy / sell signal only of price comes back to the OB for the n-th time (n being configurable)
- [ ]		Objective 3 : integrate Boom Hunter Pro algorithm in code and generate buy / sell signal
- [ ]		Objective 4 : combine both signals