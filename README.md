<div align="center"><h1>ppauth-cli</h1></div>
A simple CLI to make authentication quick and painless for developers, system administrators, and DevOps teams.  
<br><br>

<h5>* Note: These packages are automatically installed when you run <code>pip install ppauth</code></h5>

- get token  
```sh
# Quickly retrieve an authentication token for use in your commands.
ppauth-cli get token --host 127.0.0.1 --port 8080 --username admin --password admin123 --no-tls-verify
```


- registry otp
```sh
# Generates a QR code for two-factor authentication.
# Use it to complete login and receive your access token.
ppauth-cli registry otp --host 127.0.0.1 --port 8080 --username admin --password admin123 --no-tls-verify
```
