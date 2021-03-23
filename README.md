# CollectionsandMapsBenchmark
Collections and Maps
Application
Create an application running various operations on Collections and Maps, calculate and display the average execution time of these operations (time in milliseconds).
Description
•	App should contain one Activity and two tabs (Fragments): "Collections" and "Maps". Use ViewPager for this.
•	App should have an input field for the size of each collection and button “Calculate”. Recommended input: 1’000’000 - 10’000’000.
Required functionality
3 Collections: ArrayList, LinkedList, CopyOnWriteArrayList.
•	Input: number of elements to compare. Recommended: 1’000’000 - 10’000’000.
•	Output: grid with [3 collections x 7 operations = 21 cells]. Operations to perform:
o	adding in the beginning;
o	adding in the middle;
o	adding in the end;
o	search by value;
o	removing in the beginning;
o	removing in the middle;
o	removing in the end.
2 Maps: TreeMap, HashMap.
•	Input: number of elements to compare. Recommended: 1’000’000 - 10’000’000.
•	Output: grid with 2 maps x 3 operations = 6 cells. Operations to perform:
o	adding new;
o	search by key;
o	removing.



•	Each cell of the table should have a text field to display the result and progress bar. While calculation is in progress, the progressBar must be shown in the table cell. 
•	After the operation is completed, the result(average time of execution) should be shown in the appropriate cell.
•	The entire table must be asynchronous, each operation must be performed on a separate thread.
•	In case of screen rotation/recreation of activity, the computation process should not be stopped.


Technology stack
•	Language - Java
