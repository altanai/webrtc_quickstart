# WebRTC Quick Start

```
npm install webrtcdevelopment
```

create certs 
```
openssl req -newkey rsa:2048 -new -nodes -x509 -days 3650 -keyout key.pem -out cert.pem
```

start server 
```
http-server -S
```

download the lib - webrtcdevelopment.js
```bash
wget https://raw.githubusercontent.com/altanai/webrtc/master/client/build/webrtcdevelopment.js
```

download the style - webrtcdevelopment.css
```bash
wget https://raw.githubusercontent.com/altanai/webrtc/master/client/build/webrtcdevelopment.css
```

Open chrome browser and goto 
```
https://localhost:8080/#59343317443672426
```
