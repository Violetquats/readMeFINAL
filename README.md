# readMeFINAL
1. Software instructions
	Add items to your list by typing "1", and then hitting "enter".
	Read the options.
	Choose what you would like to do with your list.
	Type in numbers based on what you want to do.
	Press enter once you have selceted your number.
	Once you have narrowed down your options, pick the specific act that you would like to perform.
	Type in the corresponding number and hit enter.
	Make sure to kill the program when you're finished!
2. Descriptions of how our binary search functions work
	Both binary search functions are fairly similar in how they work. Fundamentally, the program starts
	by determining the midpoint of the list. If the value of the item that it is looking for is higher
	than the value of the midpoint, everything in the first half of the list is discarded and no longer
	searched through. The process is the same if the value is below mid, only the upper half of the
	list is discarded.

	The process repeats, changing the value of high or low based on where the item is. Because the 
	program discards half of the list every time, it is able to find the value very quickly.

	There are two binary search functions in our code: the iterative binary search function and the 
	recursive binary search function. The iterative binary search function uses a while loop to iterate
	through the process until the desired value is found at a specific index position. The recursive
	binary search, however, uses itself to repeat the process. After a half has been discarded, if the
	item has not been found, then it will call the recursive binary function again. This time though, it
	will have a different value for high, low, and mid. It will continue calling itself until it finds
	the number that it is looking for.
3. Description of changes I made
	I made two big changes to my list. The first of which was moving the print statement out of the 
	while loop so that it only greeted the user one time. The second change that I made was actually 
	large and impacted the way the code runs. I didn't like choosing from a billion options, so I 
	narrowed it down into four categories--editing, searching, printing, and leaving. The user then 
	chooses one of the options from the four categories. Each category then had different things. If the
	user picked option one, they could add one number, add multiple numbers, clear the list--another 
	feature I added--or go back to the main program. The second option then had several search functions
P.S. sorry, i'm sure that there are a lot of errors, I didn't read through it at all
	as well as the sort function. The third option only gives you the option to chose which lists to 
	print, and the fourth option kills the program.
