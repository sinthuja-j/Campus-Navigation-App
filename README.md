README
******

# Campus-Navigation-App
This application is a map that allows the user to navigate through Middlesex College, Health Science Building, and Alumni Hall. 
Points of interest are highlighted in the application, but the user has the ability to create their own if desired. The weather currently on campus is also displayed in the application.


REQUIRED LIBRARIES AND THIRD PARTY TOOLS
****************************************

This application requires Java SE 19 to run without any complications.
Visit Oracle's webpage to download Java:
	https://www.oracle.com/java/technologies/javase/jdk19-archive-downloads.html

BUILDING THE CODE
*****************

To begin, open the repository of the program. Proceed by following the following folders: 
	src/main/java
Open the main file to begin building the application:
	App.java
Once loaded, clean and build the project in your chosen IDE to assemble the application.

RUNNING THE CODE
****************

When the project is built, open the repository folder of the application. Follow these folders to access the executable file:
	target
Run the jar file to run the application:
	2212Project-1.0-SNAPSHOT-jar-with-dependancies.jar
	(Note: the src folder must be in the same directory as the .jar)

USING THE APPLICATION
*********************

	CHANGING MAPS
	*************
		Three buildings are available as maps to navigate: Middlesex College, Health Science Building, and Alumni Hall.
		To change the map and/or floor, click "Change Map" in the top right of the app. Then, selected your desired building and floor.

	NAVIGATING MAPS
	***************
		To navigate the map, use the available scroll bars to horizontally and vertically move the map.

	DISPLAYING LAYERS
	*****************
		This program has the ability to toggle layers on or off. 
		Layers are defined as a collection of common POIs for the current map that fall under the same category.
		Click on the "Favourites and Layers" tab to view the Layers menu.
		Click on a non-empty layer and click "Toggle Layer" to toggle the layer's visibility.
		Please note that Accessibility and Washrooms are unable to be turned off.
	
	SEARCHING MAPS
	**************
		To search for POIs in all three maps, click the "Search POIs" tab. 
		From there, use the search bar to look for a POI if it exists.
		Click on a POI to view more information in the "Selected POI Info" pane below.
		
	POI DISCOVERY
	*************
		To search for all POIs on the map's current floor, click the "Floor POIs" tab.
		Click on a POI to view more information in the "Selected POI Info" pane below.
		
	FAVOURITES
	**********
		To mark a POI as a favourite, click a POI and press "Toggle Favourite".
		To view all of your favourites, click on the "Favourites and Layers" tab.
		
	CREATING A POI
	**************
		In order to create a POI, start by selecting the "Create" button.
		On the right, you are able to give the POI a name, description, location, and a favourites option.
		To set the name and description, fill in the name and description boxes.
		To set a location, click anywhere on the map and press "Select Location".
		Check the favourites box if you wish for this POI to be a favourite.
		Select the "Confirm" button once you are ready or "Cancel" to exit.
		
	DELETING A POI
	**************
		To delete a POI, start by selecting a POI.
		Then, press the "Delete" button.
		To proceed, press "Delete" again or click "Cancel" to abort.
		
	CLOSING THE APPLICATION
	***********************
		To exit the program safely, click "File" in the top right of the app and select Exit.
		CTRL + Z is another option to exit the program.
		
	DEVELOPER MODE
	**************
		There are two modes for this map application: user and developer. User mode is automatically loaded on startup. 
		To enter developer mode, click "File" on the top right of the app, and select "Enter Developer Mode". The password is:
			cs2212
		Once in developer mode, you are able to create or delete any built-in POIs.
		- To create a built in POI, proceed as you would create a normal POI. 
		  However, note that you are able to select the layer of your new POI.
		  Finish by proceeding as you would create a user POI.
		- To delete a POI, proceed as you would delete a regular POI.
		
		To exit developer mode, click "Exit Dev Mode".
