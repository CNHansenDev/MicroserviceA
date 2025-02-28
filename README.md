# MicroserviceA

Communication Contract:

All communication will be done via email or discord.


Request:
Data can be requested with an HTTP client using GET.
Endpoint:
GET /process_file


Receive:
Data will be in JSON format.
[
  { "command": "length", "word": "dog", "result": 3 },
  { "command": "vowels", "word": "cat", "result": 1 },
  { "command": "repeats", "word": "beachball", "result": 3 }
]


![image](https://github.com/user-attachments/assets/79a02bb3-f437-4400-b5ba-5e673eef27b6)



