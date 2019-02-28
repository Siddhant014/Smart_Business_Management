
************SMART BUSINESS MANAGER***************

Project created by:

Shivam Mishra      9915103195
Shubham Sharma     9915103196
Tarun Khare        9915103200
Yagyesh Bajpai     9915103206


-----CONTENTS-----


1. Project abstract.
2. Libraries used.
3. Major functions used.
4. Instructions to run code.
5. Results

------------------

1. Project abstract:-

Suppose you work in a goods transportation company, so you will have to deal with many problems in your day to day job. Some of them are:

a) Returning change to purchasers.

b) Loading and unloading goods.

c) Minimising distance while delivering goods.

So our goal is to tackle these problems by implementing a smart business assistance program which would help the business managers to calculate the
amount to be returned to the customers with the denominations of the returned money,  calculate the minimum distance between the godowns to 
minimize the petrol fare and also assist in the loading of the goods for the transportation.

-------------------

2. Libraries used:-

We have used the following C++ libraries in our project:
- iostream
- windows.h
- time.h
- string.h
- conio.h

-------------------
 
3. Major functions used:-

# void delivery():
This function is used to find the shortest delivery path and then ultimately using it for calculating petrol cost to transfer in drivers account.
In this function, we will be inputting distances between different cities, and then using minimum cost path algorithm to calculate the minimum 
distance, and then using this distance to find petrol cost.

# int bin_pack(int wt[],int num,int cap):
this function takes no. of items, weight of each item, max capacity of bin as input and returns no. of bins required to pack all goods.

# void cashing():
This function prints the change to be given to the customer, which it finds using another function called coin_change().

# void coin_change(int amount):
This function takes amount to be changed as input and prints the change to be given to the customer. It uses the coinage algorithm to do so.

--------------------

4. Instructions to run code:

Compile the code in codeblocks and run it. Use 'admin' as username and 'j128f6' as password to access the main program. Now enter the choice in the menu displayed to 
run that functionality of program.

--------------------

5. Results:

This code runs successfully. Though it might give graphic related problems on some systems but algorithmic part works fine.


--------------------THANK YOU!!!---------------------------
