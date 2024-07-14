# pixelverseBot
🖱️ clicker for [https://t.me/pixelversexyzbot](https://t.me/pixelversexyzbot?start=558455838)


## Functionality
| Functional                                                     | Supported |
|----------------------------------------------------------------|:---------:|
| Auto Claim Point                                               |     ✅     |
| Auto Claim Daily Reward                                        |     ✅     |
| Suppport Multi Account                                         |     ✅     |
| Input data manually (no login require)                         |     ✅     |
| Auto Upgrade Pets (Optional)                                   |     ✅     |
| Auto Claim Cipher/Daily Combo                                  |     ✅     |
| Auto Buy New Pet                                               |     ✅     |

## Settings data file
| Setting                      | Description                                                                                    |
|------------------------------|------------------------------------------------------------------------------------------------|
| query_id        | fill the `initdata.txt` file with your data, how to get data you can refer to [How to Get Data](#how-to-get-data)                      |


## Requirements
- Python 3.9 (you can install it [here](https://www.python.org/downloads/release/python-390/)) 
- How to Get Data (you can get them [here](#how-to-get-data))
  
## Auto Install/Run
- Click on Install.bat to automatically install the required dependencies 
- Then click on START.bat to run the project

## Menual Install/Run
1. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
   
## Usage
1. Run the bot:
   ```bash
   python bot.py
   ```

# How to Get Data
   
   1. Active web inspecting in telegram app
   2. Goto bot and open the apps
   3. Press `F12` on your keyboard to open devtool or right click on app and select `Inspect`
   4. Goto `console` menu and copy [javascript code](#javascript-command-to-get-telegram-data-for-desktop) then paste on `console` menu
   5. If you don't receive error message, it means you successfully copy telegram data then paste on `initdata.txt` (1 line for 1 telegram data)
   
   Example telegram data

   ```
   query_id=xxxxxxxxxx&user=xxxxxxfirst_namexxxxxlast_namexxxxxxxusernamexxxxxxxlanguage_codexxxxxxxallows_write_to_pmxxxxxxx&auth_date=xxxxxx&hash=xxxxxxxxxxxxxxxxxxxxx
   ```

   6. If you want to add more account. Just paste telegram second account data in line number 2.
   
   Maybe like this sample in below

   ```
   1.query_id=xxxxxxxxxx&user=xxxxxxfirst_namexxxxxlast_namexxxxxxxusernamexxxxxxxlanguage_codexxxxxxxallows_write_to_pmxxxxxxx&auth_date=xxxxxx&hash=xxxxxxxxxxxxxxxxxxxxx
   2.query_id=xxxxxxxxxx&user=xxxxxxfirst_namexxxxxlast_namexxxxxxxusernamexxxxxxxlanguage_codexxxxxxxallows_write_to_pmxxxxxxx&auth_date=xxxxxx&hash=xxxxxxxxxxxxxxxxxxxxx
   ```

# Javascript Command to Get Telegram Data for Desktop

```javascript
copy(Telegram.WebApp.initData)
```

# Discussion

If you have an question or something you can ask in here : [F.Davoodi](https://t.me/sizifart)

# Pet List
| ID                                 | Image URL                                                     |
| ---------------------------------- | ------------------------------------------------------------- |
| 0a6306e5-cc33-401a-9664-a872e3eb2b71 | <img src="https://storage.googleapis.com/pixelverse-dev.appspot.com/1717749670570_1.png" width="100" height="100"> |
| 571523ae-872d-49f0-aa71-53d4a41cd810 | <img src="https://storage.googleapis.com/pixelverse-dev.appspot.com/1717753602725_black_puma.png" width="100" height="100"> |
| 78e0146f-0dfb-4af8-a48d-4033d3efdd39 | <img src="https://storage.googleapis.com/pixelverse-dev.appspot.com/1717750211798_19.png" width="100" height="100"> |
| 7c3a95c6-75a3-4c62-a20e-896a21132060 | <img src="https://storage.googleapis.com/pixelverse-dev.appspot.com/1717750211795_16.png" width="100" height="100"> |
| 8074e9c5-f6c2-4012-bfa2-bcc98ceb5175 | <img src="https://storage.googleapis.com/pixelverse-dev.appspot.com/1717750072415_13.png" width="100" height="100"> |
| d364254e-f22f-4a43-9a1c-5a7c71ea9ecd | <img src="https://storage.googleapis.com/pixelverse-dev.appspot.com/1717750072416_15.png" width="100" height="100"> |
| dc5236dc-06be-456b-a311-cccedbd213ca | <img src="https://storage.googleapis.com/pixelverse-dev.appspot.com/1717749670581_5.png" width="100" height="100"> |
| e8c505ed-df93-47e0-bd2e-0e664d09ba86 | <img src="https://storage.googleapis.com/pixelverse-dev.appspot.com/1717749762365_8.png" width="100" height="100"> |
| ef0adeca-be18-4503-9e9a-d93c22bd7a6e | <img src="https://storage.googleapis.com/pixelverse-dev.appspot.com/1717749670580_4.png" width="100" height="100"> |
| f097634a-c8e8-4de9-b707-575d20c5fd88 | <img src="https://storage.googleapis.com/pixelverse-dev.appspot.com/1717750072415_14.png" width="100" height="100"> |
| 50e9e942-36d5-4f19-9bb7-c892cb956fff | <img src="https://storage.googleapis.com/pixelverse-dev.appspot.com/1717750072412_11.png" width="100" height="100"> |
| 7ee9ed52-c808-4187-a942-b53d972cd399 | <img src="https://storage.googleapis.com/pixelverse-dev.appspot.com/1717750072414_12.png" width="100" height="100"> |
| 36621a17-81f3-4d5d-b4e1-4b0cf51d4610 | <img src="https://storage.googleapis.com/pixelverse-dev.appspot.com/1717750211797_18.png" width="100" height="100"> |
| 90a07a32-431a-4299-be59-598180ee4a8c | <img src="https://storage.googleapis.com/pixelverse-dev.appspot.com/1717749762363_6.png" width="100" height="100"> |
| 45f2e16e-fb64-4e15-a3fa-2fb99c8d4a04 | <img src="https://storage.googleapis.com/pixelverse-dev.appspot.com/1717749762367_10.png" width="100" height="100"> |
| 3bfab57c-a57f-48d9-8819-c93c9f531478 | <img src="https://storage.googleapis.com/pixelverse-dev.appspot.com/1717750211796_17.png" width="100" height="100"> |
| 341195b4-f7d8-4b9c-a8f1-448318f32e8e | <img src="https://storage.googleapis.com/pixelverse-dev.appspot.com/1717749670578_2.png" width="100" height="100"> |
| bc3f938f-8f4c-467b-a57d-2b40cd500f4b | <img src="https://storage.googleapis.com/pixelverse-dev.appspot.com/1717749670579_3.png" width="100" height="100"> |
| f82a3b59-913d-4c57-8ffd-9ac954105e2d | <img src="https://storage.googleapis.com/pixelverse-dev.appspot.com/1717749762364_7.png" width="100" height="100"> |
| d59cd843-1b53-4131-9966-641d41aa634b | <img src="https://storage.googleapis.com/pixelverse-dev.appspot.com/1717749762366_9.png" width="100" height="100"> |
