# Sending Covid-19 Report THAILAND


### วิธีติดตั้ง

เปิด CMD / Terminal

```python
pip install CovidSonglinePawit
```

### Generate Line Notify TOKEN
https://notify-bot.line.me/th/

### วิธีเล่น

เปิด IDLE ขึ้นมาแล้วพิมพ์...

```python
from CovidSonglinePawit import report

token = 'YOUR LINE NOTIFY TOKEN'
re = report(token) #input token
re.sendline() #Send report to line

```

พัฒนาโดย: Pawit Kraisornnukhor
FB: https://www.facebook.com/jamecdtz.pawit


