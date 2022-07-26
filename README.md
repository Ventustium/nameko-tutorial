Clone Repo
```
git clone https://github.com/
```

Install Nameko with Nameko Reloader
```
pip3 install -f requirements.txt
```

- Using Service-1
```
nameko_reloader run service-1 --reload
```
use ctrl+c for stop service

open another terminal and use curl for get response
```
curl "http://localhost:8000/multiply/3/4?thrid=3"
```
or open your browser using this url
```
http://localhost:8000/multiply/3/4?thrid=3
```

-using service-2
```
nameko_reloader run service-2 --reload
```