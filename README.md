# UI Components for EVLR Staking 
This includes three components required to build a staking UI for EVLR v1 staking contracts.  The three components handle connection to metamask, display statistics for the staking pool, and enable connected users to stake their tokens.  

# Dependencies
We use the following libraries to build components:
- React Metamask detection (http://www.github.com/YannyD/react-metamask-connection-tool)
- Material UI
- Styled Components

# Implementation
To implement:<br>
1.) Replace the deployment folder with one generated by hardhat-deploy for the EVLR staking contract.<br>
2.) Ensure the correct json replaced the MochEVLR1.json file or simply add the necessary ABI and Address information the constants file inside of utils<br>
3.) While individual components can be used without others, the useStaker.js file must be included in your repo.  
