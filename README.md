## Requirements:

The program uses NodeJS version 16+ to run the three applications
`https://nodejs.org/en/download/`

# Start the three applications:
## Entry node:

First start the entry node by going into the `entry/` directory and use command:
```
node index.js
```

## Relay node:

Start a relay node by going into the `relay/` directory and use command:
```
node index.js
```

For more relay nodes read the README inside the directory.

## Peer node:
Start a peer node by going into the `peer/` directory and use command:
```
node index.js
```

For more information about starting multiple peers read the README inside the directory.

## Access the UI
The default port for peer node is `3000`, so go into a browser (Google Chrome is preferred) and go to url: `http://localhost:3000`

The password can not be too short (GUN constrain) so a suggestion is to simply use:
`11223344`
as password when creating a user.
