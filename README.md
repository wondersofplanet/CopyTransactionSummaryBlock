This macro copies transaction summary data from the active worksheet to a separate worksheet named "txsummary". 
It searches for the cell containing the text "Transaction Name" in the active worksheet, then copies all rows below that cell until the first empty row is encountered.
Before copying, it trims any whitespace characters from each cell's content to ensure accuracy. If the "txsummary" sheet does not exist, it creates one.
