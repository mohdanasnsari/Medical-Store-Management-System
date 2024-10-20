# Medical-Store-Management-System
GUI (Graphical User Interface) Based Medical Store Management System with Python
RUN IN PYTHON SHELL OR TERMINAL (cmd)

Files
-> medStoreGui.py contains source code.
-> Medical_Store_Management_System.pdf contains description, source code & images of application.
-> bill.csv file automatically created in program for data & records.
-> Needed.txt automatically created in program for data & records.


Overview,
This Program or GUI Based Tkinter Application is build to manage Medical Store.
Program uses mysql database to manage tables & queries, and csv & text files to print bills & save records of medicine sold & left in inventory.
Program also contain feature of minimum selling cost where seller will surely get minimum 10% profit on each product, that is program will inform about minimum price to get atleast 10% profit on product.

Contains,
-> 'Main Window' to calculate total amount and bill for customers while saving bill for seller, calculating profit and automatically substracting number of medicine sold from main inventory to keep record of medicine. New Entries to add new stock (name & amount) for billing while informing about minimum price of product to get atleast 10% profit.

-> 'New Table Window' is used to create new table in database.

-> 'Insert Button' opens up Insert Window to add new stocks in inventory.

-> 'Query Window' used for searching or changing names & cost of products.

-> 'Needed Window' will automatically inform about products which are left less than 5 in inventory (table name required in query). Seller can add those product names in text file (.txt) with this window feautres for records.


