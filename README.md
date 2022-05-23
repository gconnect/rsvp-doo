# RSVP TICKETING DAPP BUILT WITH REACH DEPLOYED ON ALGORAND
RSVP Dapp built with Reach
RSVP DApp that allows you to purchase a ticket by staking Algos, and allowing you to withdraw them after you attend, and have been verified by the admin.


# Live Demo
Here is a [demo link](https://rsvp-dapp.vercel.app/) to the deployed Application on vercel. Figma design [link](https://www.figma.com/file/PlznxkNi3S58s1HUGRzrbj/rsvp-ticketing?node-id=10%3A419)

# Run Frontend Code
To test the code
- Fork the repository
- Do `npm install` this will install all required dependencies. (If you encounter any issue after doing this you can delete the node module folder and do npm install again)
- run `npm start` to start the local server at localhost:3000

# Setup Requirements
- Install [make](https://en.wikipedia.org/wiki/Make_(software)), [Docker](https://www.docker.com/get-started/) and [Docker Compose](https://docs.docker.com/compose/install/)
- [Vs Code](https://code.visualstudio.com/) or any IDE of your choice
- [Node Package Manager](https://nodejs.org/download/)
- [Create React App](https://github.com/facebook/create-react-app) . This creates a react boilerplate app.
- [Aphrodite](https://github.com/Khan/aphrodite) for css styling
- Install Reach and Reach Standard Library
- More detailed Reach specific setup instruction can be found [here](https://docs.reach.sh/tut/rps/#tut-1)

# Test Smart Contract Code
- Ensure you have docker installed and running
- Navigate to th contract folder. `/src/contract`
- run `./reach run`

# Blog and Video Demo
For more details you can checkout the blog post [here](https://medium.com/@agatevureglory/my-experience-developing-decentralised-app-with-reach-b96cd59b0f0f) . And here is the link to the youtube [demo](https://youtu.be/tAfJ3clA2kU)

# Login with Unstoppable
Integration with login with unstoppable can be found here `src/api/login.js`. To get your clientID follow this [guide](https://docs.unstoppabledomains.com/login-with-unstoppable/login-integration-guides/login-client-configuration/#rules-for-redirect-uris). Submission detail [here](https://github.com/gconnect/rsvp-dapp/blob/master/unstoppable-integration.md)

# LICENSE 
Distributed under the MIT License. See for more information LICENSE

#Disclaimer
This project is not audited and should not be used in a production environment.

