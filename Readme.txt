1. Open your teminal and go to directory where is a executable file.
i,e: If you copy Tradebot directory to Document folder, then you can run "cd Document", "cd Tradebot"
2. In Tradebot directory, in order to set the parameters for trading, run this command: "nano .env" in MacOS and "vim .env" or "notepad .env" in Win.
3. In text editor, you can config the parameters such as currency, privatekey, invest amount, etc
After configuring, save and exit.
4. In order to run trading bot, run this in Tradebot directory "./tradebot"
If it needs the admin permission, you can run "sudo ./tradebot"

PS: There are two files in Tradebot directory. One is executable file named as "tradebot" and other file is not shown named as ".env"
When you copy, you need to copy directory. 
