# Platform Remote WS Client

This is the client side code of the websocket platform integration for Texts. 

Built with https://github.com/batuhan/texts-platform-remote-client

Server side code at https://github.com/batuhan/texts-platform-remote-server-ws

## Prerequisites

Before you begin. ensure you have the following installed.

- [Texts](https://texts.com)
- [Yarn](https://yarnpkg.com/)
- [Node.js](https://nodejs.org/en)

## How to install

- Clone this repository and navigate into the project directory:
```bash
git clone https://github.com/batuhan/texts-platform-remote-ws.git && cd texts-platform-remote-ws
```
- Install dependencies and build the project:
```bash
yarn install
yarn build
```
- Open Texts and access the command bar (`CMD+J` on macOS) to select **Install platform integrations**
- Choose **Load platform from directory**, navigate inside of the `dist` directory generated by `yarn build`
- Restart Texts to apply changes.
- Make sure you have platform remote ws server running and set up correctly.
- Log in to this remote integration by entering the Base URL for your remote server and a websocket URL to connect to. 

## Credits
This integration was built at [Pickled Works](https://pickled.works/) by [@alperdegre](https://github.com/alperdegre/) and it isn't an official integration by Texts.
