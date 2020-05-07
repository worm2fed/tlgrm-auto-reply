This is small tool to auto reply when you are absent for a while

## Settings
To execute this script you have to install dependencies (to install run `pip3 install -r requirements`) and create a file `settings.py` whith following content:
```python
# sample API_ID from https://github.com/telegramdesktop/tdesktop/blob/f98fdeab3fb2ba6f55daf8481595f879729d1b84/Telegram/SourceFiles/config.h#L220
# or use your own
api_id = 99999
api_hash = 'aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa'

# fill in your own details here
phone = '+99999999999'
username = 'username'
password = 'password'  # if you have two-step verification enabled

# content of the automatic reply
reply_message = "reply_message"
```

and then run `python3 tlgrm-auto-reply.py` in your terminal window