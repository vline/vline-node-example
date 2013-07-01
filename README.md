Sample node.js app that demonstrates vLine API integration.

In order for the application to run you need to install node.js. You
can install node.js with an [installer](http://nodejs.org/download/) or [package
manager](https://github.com/joyent/node/wiki/Installing-Node.js-via-package-manager.).

## Getting Started

1. Sign up for a [vLine developer account](https://vline.com/developer/) and
   create your vLine service.
1. Make note of your `API Secret` on the `Service Settings` tab in the [vLine
   Developer Console](https://vline.com/developer/app/).
1. Clone this repository.
1. Add your `Service ID` and `API Secret` to the
   `routes/routehandler.js` file.
1. Install dependencies using the Node Package Manager (`npm`): `npm install`
1. Start the server: `npm start`
1. Open [http://localhost:3000](http://localhost:3000) in one regular browser
   window and one incognito window.
1. Log in as different users in the two windows. The users (and passwords) are
   defined in the `users.json` file in the root directory of this example.
1. Click on a username to call that user.
