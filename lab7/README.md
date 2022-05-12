# Lab 7 — ThingSpeak and Google Sheets
## Part 1
I ran thingspeak_cpu_loop.py and thingspeak_feed.py in a demo folder to collect and upload data about my cpu performance.
```console
pi@ctmpi: ~/demo $ python3 thingspeak_feed.py
An API key savefile was not found. Enter Write API Key >>> ****************
Should we save this key for future use? [y/N] >>> y
574.7578125
Wed, 11 May 2022 15:59:07
200 OK
15.0
577.23828125
Wed, 11 May 2022 16:00:07
200 OK
15.2
577.4765625
Wed, 11 May 2022 16:01:07
200 OK
14.6
577.03515625
Wed, 11 May 2022 16:02:07
200 OK
14.9
577.46484375
```

## Part 2
I installed gspread and oauth2client, and created a new Google Cloud Platform service account with a JSON key file, in order to use Google SHeets API calls. By prepping a new sheet and running cpu_spreadsheet.py, I was able to upload the data collected in Part 1 to Google Drive.
```console
pi@ctmpi: ~/demo $ python3 rpi_spreadsheet.py
Free RAM: 16 (866)
Number of processes: 178
Up time:  4:33
Number of connections: 2
Temperature in C: 63.3
IP-address: 192.168.1.215
CPU speed in MHz: arm_freq=1500

Logging sensor measurements to rpidata every 10 seconds.
Press Ctrl-C to quit.
2022-05-11 16:40:49.034073
CPU Usage:   21.2 %
Temperature: 63.7 C
Wrote a row to rpidata
2022-05-11 16:40:59.234427
CPU Usage:   15.2 %
Temperature: 62.8 C
Wrote a row to rpidata
2022-05-11 16:41:09.402127
CPU Usage:   14.1 %
Temperature: 63.3 C
Wrote a row to rpidata
2022-05-11 16:41:19.572112
CPU Usage:   15.3 %
Temperature: 62.3 C
Wrote a row to rpidata
2022-05-11 16:41:29.762102
CPU Usage:   15.3 %
Temperature: 62.8 C
Wrote a row to rpidata
2022-05-11 16:41:39.973860
CPU Usage:   15.1 %
Temperature: 63.7 C
Wrote a row to rpidata
```
