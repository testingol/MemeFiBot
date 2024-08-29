> [<img src="https://img.shields.io/badge/Telegram-%40Me-orange">](https://t.me/roddyfred)

![img1](./.github/image/hero-image.png)

# Use Python 3.11 or less

## Functionality

| Functional                                                     | Supported |
| -------------------------------------------------------------- | :-------: |
| Purchasing TapBot                                              |    ✅     |
| Starting TapBot                                                |    ✅     |
| Claiming TapBot reward every 3 hours                           |    ✅     |
| Claiming Daily Combo                                           |    ✅     |
| Spinning game                                                  |    ✅     |
| User Agent for each session                                    |    ✅     |
| Multithreading                                                 |    ✅     |
| Binding a proxy to a session                                   |    ✅     |
| Auto-purchase of items if you have coins (tap, energy, charge) |    ✅     |
| Random sleep time between clicks                               |    ✅     |
| Random number of clicks per request                            |    ✅     |
| Support tdata / pyrogram .session / telethon .session          |    ✅     |
| Referral bonus claiming after first time registering           |    ✅     |



| Settings                                      | Description                                                                            |
| --------------------------------------------- | -------------------------------------------------------------------------------------- |
| **API_ID / API_HASH**                         | Platform data from which to launch a Telegram session (stock - Android)                |
| **MIN_AVAILABLE_ENERGY**                      | Minimum amount of available energy, upon reaching which there will be a delay (eg 100) |
| **SLEEP_BY_MIN_ENERGY**                       | Delay when reaching minimum energy in seconds (eg 200)                                 |
| **ADD_TAPS_ON_TURBO**                         | How many taps will be added when turbo is activated (eg 2500)                          |
| **AUTO_UPGRADE_TAP**                          | Should I improve the tap (True / False)                                                |
| **MAX_TAP_LEVEL**                             | Maximum level of tap pumping (eg 5)                                                    |
| **AUTO_UPGRADE_ENERGY**                       | Should I improve the tap (True / False)                                                |
| **MAX_ENERGY_LEVEL**                          | Maximum level of tap pumping (eg 5)                                                    |
| **AUTO_UPGRADE_CHARGE**                       | Should I improve the tap (True / False)                                                |
| **MAX_CHARGE_LEVEL**                          | Maximum level of tap pumping (eg 5)                                                    |
| **APPLY_DAILY_ENERGY**                        | Whether to use the daily free energy boost (True / False)                              |
| **APPLY_DAILY_TURBO**                         | Whether to use the daily free turbo boost (True / False)                               |
| **RANDOM_TAPS_COUNT**                       | Random number of taps (eg 50,200)                                                      |
| **SLEEP_BETWEEN_TAP**                         | Random delay between taps in seconds (eg 10,25)                                        |
| **USE_PROXY_FROM_FILE**                       | Whether to use proxy from the `bot/config/proxies.txt` file (True / False)             |
| **SLEEP_BETWEEN_TAP**                         | Random delay between taps in seconds (eg 10,26)                                        |
| **AUTO_BUY_TAPBOT**                           | Whether to purchase tapbot automatically (True / False)                                |
| **AUTO_SPIN**                                 | Whether to spin automatically (True / False)                                           |
| **AUTO_GENERATE_USER_AGENT_FOR_EACH_SESSION** | Whether you want to generate user agent for each session (True / False)                |

## Installation


```shell
~ >>> git clone https://github.com/try-to-learn-now/MemeFiBot
~ >>> cd MemeFiBot

~/MemeFiBot >>> python3 -m venv venv
~/MemeFiBot >>> source venv/bin/activate
~/MemeFiBot >>> pip3 install -r requirements.txt
~/MemeFiBot >>> python3 main.py

#Windows
1. Double click on INSTALL.bat in MemeFiBot directory to install the dependencies
2. Double click on START.bat in MemeFiBot directory to start the bot

OR

~/MemeFiBot >>> python -m venv venv
~/MemeFiBot >>> venv\Scripts\activate
~/MemeFiBot >>> pip install -r requirements.txt
~/MemeFiBot >>> python main.py
```

Also for quick launch you can use arguments, for example:

```shell
~/MemeFiBot >>> python3 main.py --action (1/2)
# Or
~/MemeFiBot >>> python3 main.py -a (1/2)

#1 - Create session
#2 - Run clicker
```
