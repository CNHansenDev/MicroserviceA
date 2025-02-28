# MicroserviceA

Communication Contract:

All communication will be done via email or discord.


Request:<br />
Data can be requested with an HTTP client using GET.<br />
Endpoint:<br />
GET /process_file<br />


Receive:<br />
Data will be in JSON format.<br />
[<br />
  { "command": "length", "word": "dog", "result": 3 },<br />
  { "command": "vowels", "word": "cat", "result": 1 },<br />
  { "command": "repeats", "word": "beachball", "result": 3 }<br />
]<br />


![image](https://github.com/user-attachments/assets/79a02bb3-f437-4400-b5ba-5e673eef27b6)



