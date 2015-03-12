# LightBlue Bean nodes for node-red

Node-Red is a graphic flow-style programming environment based on node.js. The application runs as a server, and you manipulate functional "flows" from a web client. The server can be hosted on an inexpensive device like the Raspberry Pi. Flows can be manipulated from the browser of the server device, on a separate computer client on the same network, and/or remotely over the internet.

Node-Red allows for third party nodes to be made and distributed as npm modules. This project is set of node-red nodes that allow for easy interfacing to the LightBlue Bean.

![](https://punchthrough.com/images/products/bean/node-red/Screen%20Shot%202015-01-25%20at%203.12.22%20PM.png)

## Installation

1. Install Node.js (Note: 0.12.0 is not yet supported by Node-RED): http://nodejs.org/download/
1. Install Node-RED and Bean nodes: `sudo npm install -g node-red node-red-contrib-bean`

## Usage

1. `sudo node-red`
1. Open [http://localhost:1880](http://localhost:1880)

## Updating

1. Update both Node-RED and Bean nodes: `sudo npm update -g node-red node-red-contrib-bean`

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

- 0.2.0 : Better logging and reporting of errors, more accurate Bean connection timeout
- 0.1.0 : More robust connection routines, fixed some crashes during deployment, better how-to-use text
- 0.0.1 : Initial Release

## Authors

* Ray Kampmeier [@raykamp](https://github.com/raykamp)
* Simone Giertz [@simsalapim](https://github.com/simsalapim)

## Credits

Node-RED has been made possible by the hard work of Nick O'Leary @knolleary and Dave Conway-Jones @ceejay at IBM Emerging Technology. Much thanks to them and other supporters for advancing this platform. 

## License

This SDK is covered under The MIT License. See LICENSE.txt for more details.
