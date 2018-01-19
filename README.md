# NiceHashBalanceIFTTTWebhook
A simple comand line app to send pending wallet balance to a IFTTT webhook.

- Setup a webhook in IFTTT and get the key and event name that you want.
- Setup a scheduled task on your computer to run whenever you want with the arguments <WalletAddress> <EventName> <Key>
- Value 1 is your Wallet Address, Value 2 is going to be your pending balance.
