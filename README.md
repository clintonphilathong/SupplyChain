# Hackathon Setup

Example code to connect an:
1) `api` session object with a CENNZnet node
2) Load a keypair
3) Send a transaction to say hi!

## Install
1) clone the repo
2) `yarn`

## Run it
Supply your message, path to keypair.json and the password
```bash
node src/index.js "hello CENNZnet!" ./myKeyPair.json  password
```

output 
```
My CENNZnet address is: 5FWEHQqYMN8YCg8yJxKHnon7Dtx4Psp2xnjvKfQqGC6kUwgv
Connecting to CENNZnet...
Saying hello...

Said hello 🚀: 'hello world'
Tx hash: 0x0390f6ea97a38ef762db8c44b4e69c5d7ebf9fed9dd726ce6007162f2d3acef7
```

Got to UNcover and view the transaction!