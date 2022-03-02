# MedAR

Running instructions:

1. Install `npm`

2. Generate self-signed certificates `openssl req -newkey rsa:2048 -new -nodes -x509 -days 3650 -keyout key.pem -out cert.pem`

3. Initialize project `npm init -y && npm install node-static`

4. Start the server `npm start`

5. Make sure your smartphone is connected to the same network as your PC, open Chrome and navigate to [https://your_local_ip:3000/webxr-threejs.html](https://your_local_ip:3000/webxr-threejs.html)
