I created this repo to test out things related to the size of github repositories. 

Interesting. When I committed the first time and made a request to https://api.github.com/repos/mjrecent-on-Telegram/yesy-repo-size, I got a json with a value 0 next to the key "size", i.e. according to the API this repo had a size of 0 bytes. Yes, this file wasn't too large, but it was sized 84 bytes, not 0 bytes. And yes, I made a request a couple of times (like 5) and every time I saw ""size": 0," there (the last one was made just now)

Before I committed this, this repo waited 2kb according to the github's API.
