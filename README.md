# CollectionManager
A Collection Manager in Bash, handles records with copies.

Purpose:
● Operating system commands
● flow control
● Operators
● Functions
● I/O to files
● Algorithmic thinking

General description: In this project I managed a record collection. Each record has a unique name, and there may be more than one copy.
To manage the collection, the following actions was performed:
1. Inserting record
2. Deleting a record
3. Searching by name or part of it
4. Updating record's name
5. Updating record's amount
6. Printing all records + their copies total
7. Printing the collection in a sorted manner
8. exiting the program

More details:
1. Insert. Parameters: record name, number of copies.
 This function will add a record or update an existing record.

2. Delete. Parameters: record name, number of copies.
 This function will remove a record or update an existing record.

3. Search. Parameters: search string. 
This function will search the file and show the user a list of records containing the search string.

4. Update Name. Parameters: old name, new name. 
This function will update a record name in an existing record.

5. Update Amount. Parameters: name, number of copies.
This function will update the amount of records in an existing record.

6. Print All. Parameters: None
This function will scan the file and summarize the total number of records in the database (total number of copies).

7. Print Sort. Parameters: none 
This function will print the file in lexicographic order (lexical order) according to the names of the records.

8. exit (no function just a command).

In addition we have:
9. Log. Parameters: the event that happened and whether it ended in success or failure and relevant values for printing.
This function will take care of writing the current event to a log file named recordFileName_log.

10. Some Validation functions for the input, and a temporary file (ecordFileName_tmp) used through the program (should be deleted automatically if exited by the program).
