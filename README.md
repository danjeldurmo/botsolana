# botsolana

Solana Trading Bot for Raydium Liquidity Pool V4
We have developed a Python script that detects newly issued pairs in the Raydium Liquidity Pool V4 (Solana) and performs automated token trading based on user-defined conditions. Here's how it works:
 
Detection of new pairs as they are listed.
Data collection including token name, symbol, and holder percentages using Python libraries.
Market data retrieval such as price, market cap, liquidity, and more from free APIs like Jupiter and Dexscreener.
Tradeability check based on user-defined conditions (e.g., MCAP over $1B, top 1-40 holders owning < 0.50%, etc.).
Automated trading execution: If the token meets the "tradable" criteria, the bot will automatically buy and then sell after a user-specified time interval, using optimized slippage.
Telegram notifications are sent upon each BUY and SELL, providing all relevant transaction details
Data logging: All trades (both tradable and non-tradable tokens) are recorded in a MySQL database for monitoring.
Tech & Usage
The script works with free APIs from Jupiter, DexScreener, and Helius. To start the bot, once strategies, investment amount (SOL), and Phantom wallet private key are configured, simply run a systemctl command from the terminal.
 
Source Code & Support
The source code is sold "as-is" along with a guide. Customization and integration support are available as a paid service, depending on the effort required.
 
🔹 Note: The code is written in pure Python with no graphical interface, so we recommend it for users with basic technical knowledge—though modifying parameters and running it is very straightforward.
 
📩 For inquiries: info@datanext.app
