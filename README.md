# ABAP-Send-Message-to-Telegram
SAP ABAP Send Message to Telegram

Step by step :
1. Create Bot
2. Get Token
3. Start Conversations in your new Bot (type more messages) 
4. Get chat_id (https://api.telegram.org/bot<token>/getUpdates)
   e.g. https://api.telegram.org/bot446024890:AAElkDxGgwifbtC1eVSc7Sy6ERi9eSm2-Rw/getUpdates
5. Get info your Bot (https://api.telegram.org/bot<token>/getMe)
   e.g. https://api.telegram.org/bot446024890:AAElkDxGgwifbtC1eVSc7Sy6ERi9eSm2-Rw/getMe
6. Create ABAP Program
7. Run ABAP Program
   filled parameter : chat_id & Message
8. Enjoy


References:
1. Cara Membuat Bot Telegram - Blajar Bot Telegram #1 
https://youtu.be/pgDabVwUwLc

2. Cara Menggunakan Telegram Bot API - Blajar Bot Telegram #2
https://youtu.be/3IQKb_orBlo

3. Telegram Bot API
https://core.telegram.org/bots/api 
