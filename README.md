# Contact form PHP - Telegram Bot
![](https://i.imgur.com/b1kWUB7.gif)

PHP Form contact to Telegram Bot based on the official [Telegram Bot API](https://core.telegram.org/bots/api "Telegram Bot API")

## Instructions
1. Message [@BotFather](https://telegram.me/BotFather "@BotFather") with the following text: `/newbot`

	![](https://i.imgur.com/mLRQFoP.gif)

	[@BotFather](https://telegram.me/BotFather "@BotFather") replie:
	> Alright, a new bot. How are we going to call it? Please choose a name for your bot.

	Continue with the next steps *(look at the image above)*:
	- Assign a name
	- Continue with the username finished in _bot that is available. example: `juantest_bot `

2. Once the previous steps have been carried out, [@BotFather](https://telegram.me/BotFather "@BotFather") responds with its respective **HTTP TOKEN API.**

3. Save your respective **HTTP TOKEN API **

4. Insert your TOKEN

	```php
	<?php
	date_default_timezone_set('America/Bogota');

	# Enter your **token** here:
	define('BOT_TOKEN', '**API-KEY**');
	define('API_URL', 'https://api.telegram.org/bot'.BOT_TOKEN.'/'); #Do not modify
	```

5. Next we have to know our telegram ID, there are different ways to do it. I recommend knowing, through this bot. It is much faster. [GET ID - TELEGRAM](https://telegram.me/get_id_bot "GET ID - TELEGRAM")

6. Already obtained our ID. We go to the code and put our ID 
	```php
	# Enter your Telegram ID here:
	define('TLG_ID', 'YOUR-ID');
	```
