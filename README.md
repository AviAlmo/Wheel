# Wheel 

General 
The task is about a wheel game. The user can spin the wheel to win prizes.
The winnings are being saved to user's wallet and he can withdraw them in any time. 

First the user needs to select a player to start the game and if he has credit in the wallet he can deposit directly to his account. 
The game created using the next technologies  – MongoDB , Express, React ,   NodeJS .

The wheel created by npm package - React Custom Roulette.   

Link - https://www.npmjs.com/package/react-custom-roulette.   

Details
The main functions in the code: 

useEffect() – In the  createUser page, the useEffect function sending a request to the server to bring all the users that exist in the DB.   
newPrize() – This function have a responsibility for the wheel functionality.  
according to the function, the wheel contains prizes and it stops on a random prize and updates the player information.  
updateNewData() – This function updates the new information about the user such as spin history or wallet balance.  
WithdrawDeposit() – This function creates a deposit request and updates the new information in the DB by using the updateNewData().   
