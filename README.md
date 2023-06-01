# Ken_Likit_agnos_frontend_internship_2023

# Requirements  
1. Install react. 
2. Install NPM.

# To deploy on local computer
1. Download code and open folder location in command line.
2. Use the command `npm start` This will start the server on local host port 3000.
3. Click on parts of the picture to have it highlighted and have an action occur. 
4. To switch between problems a `Change Question` button can be found in top left corner to switch questions.
5. Each picture can only be clicked on once before the page needs to be refreshed or switch problem. 
 
# Outstanding problem 
Due to the image map implementation, when clicking on an area inside the image it would cause the page to reload and reset the state. As a result the selelected area would be reset and the overlay image(s) would dissapear. To solve this I used `e.preventDefault` to stop the page reload and the side effect is that it would not respond to further clicks.

