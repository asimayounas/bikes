BIKES
-----

Introduction
------------

A single webpage application showing bikes in a list/grid format.  


USER STORY
------------

- A list/grid of bikes from a JSON object which can be found from https://raw.githubusercontent.com/jujhars13/jujhars13/master/bikes.json
- The data presented for each bike  is as follows: name, an image, a description, and the class for each bike. 
- The list/grid is sorted based on the custom order based on class
- When the page is refreshed the sort is saved and therefore the sort is not refreshed. 


ASSUMPTIONS
------------

- Project must work in the latest version of Google Chrome- other browsers can be ignored
- JS libraries/frameworks of choice can be used
- HTML/CSS frameworks of choice can be used
- The ability to view a list/grid of bikes which can be sorted by the class of the object
- Each bike will be show on the list/grid without difficulty 


USER INTERFACE OF LIST/GRID
---------------------------

Please refer to attachment - If i had more time i would style the table as shown in the picture 


STYLING  
-------

For the purpose of this task the chosen styling was CSS the styling is kept within the index.html in style tags. 
Examples of this are as follows: 

	<style>
	.bikeTable {
		width: 100%;
  		text-align: left;
  		background-color: lemonchiffon;
  		border-collapse: collapse; 
  	} 
	</style>

If you are requred to add/chang the exisiting styling to the table by adding .bikeTable followed by the appropriate tag for the table. 

SORT COLUMN  
-----------

If there was more time given to spend I would give the abiltiy to sort the column in class. This would be achieved by adding a JQuery plugin called tablesorter. This would allow the table to be sort without effecting page refreshes. 

To achieve this i would  do the following steps:

	- Add the JQuery plugin at the top of the page
	- add javascript which will tell tablesorter to sort '#bikeData' and then passing options which will sort the specific column in our case it would be class in ascending order.   




Read Author: Asima Younas
