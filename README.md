# DataHandler-and-sorting-Algos-Java
# the project has 4 classes:
 1. Datahandler
 2. Quicksort
 3. Bubblesort
 4. MyDate
 5. DataHandlerRun
 
 
 #  To run the project you have to run DataHandlerRun class
 
 #  In order to run the project you need the following:
 
 1. Replace prices variable with the path of your prices file
 
   ex: C:\\Users\\Simeon\\Dropbox\\APPLICATIONS\\SUMMER_HW\\prices.csv (on windows)
       /Users/Simeon/Dropbox/APPLICATIONS/SUMMER_HW/prices.csv (mac/linux)
       
 2. Replace corrections variable with the path of your corrections file  
 
 3. Replace fOutput variable with the path of where you would like to save results.txt file
 
 4. Choose a window size that is less than the size of the selected date range(e.g., window =10)
 
 5. This method takes sorting method specification of QuickSort or BubbleSort,
    and sort preference-ascending or descending, and price or date as parameters.
    e.g.: List<DataHandler> dh = dataHand.loadPriceData(prices, "QUICKSORT", "ASC", "DATE");
    
 6. You can change or select dates from part 4 in the DataHandlerRun class:
 	Example: ( fromDate, toDate)
	MyDate dateForPriceSelection = new MyDate("08/15/2004", "08/20/2004");# Load Price selection
	MyDate dateForAverage = new MyDate("08/15/2004", "09/15/2004");# Date selection range for computing average 
	MyDate dateForMaximuPrice = new MyDate("04/15/2004", "06/15/2004"); # Date selection range for computing maximum value
	MyDate dateForMovAv = new MyDate("08/15/2004", "09/15/2004");# Date selection range for computing simple moving average
		
7. "DONE" message is displayed on console once the program is finished running.	

8. Expected output written on the results.txt file for the above specified inputs:
    The Prices of SPY between 08/15/2004 and 08/20/2004 are: 
	94.42
	94.95
	95.92
	95.64
	96.32
	The Average Price of SPY between 08/15/2004 and 09/15/2004 is: 
	97.09409090909092
	The Maximum Price of SPY between 04/15/2004 and 06/15/2004 is: 
	99.77
	The Moving Average Price of SPY between 08/15/2004 and 09/15/2004 for WindowSize 10 is : 
	96.03999999999999
	96.23400000000001
	96.426
	96.53899999999999
	96.78999999999999
	96.93299999999999
	97.16499999999999
	97.35999999999999
	97.47999999999999
	97.651
	97.82399999999998
	98.09700000000001
	98.244
