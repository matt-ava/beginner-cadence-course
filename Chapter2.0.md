# Chapter 2

## Day 1

**1) Deploy a contract to account 0x03 called "JacobTucker". Inside that contract, declare a constant variable named is, and make it have type String. Initialize it to "the best" when your contract gets deployed.**
<br/><br/>
![Screenshot](images/chap2-day1-q1.PNG)
<br/><br/>
**2) Check that your variable is actually equals "the best" by executing a script to read that variable. Include a screenshot of the output.**
<br/><br/>
![Screenshot](images/chap2-day1-q2.PNG)
<br/><br/>

## Day 2

**1) Explain why we wouldn't call changeGreeting in a script.**     
Because a script cannot alter data stored on the Blockchain.

**2) What does the AuthAccount mean in the prepare phase of the transaction?**      
AuthAccount is used to access data in the user account.

**3) What is the difference between the prepare phase and the execute phase in the transaction?**        
Prepare phase: access the information/data in user account.        
Execute phase: change the data on the blockchain.

**4.1) Add two new things inside your contract:**     
**A variable named myNumber that has type Int (set it to 0 when the contract is deployed)**         
**A function named updateMyNumber that takes in a new number named newNumber as a parameter that has type Int and updates myNumber to be newNumber**        
<br/><br/>
![Screenshot](images/chap2-day2-q4.1.PNG)
<br/><br/>

**4.2) Add a script that reads myNumber from the contract**            
<br/><br/>
![Screenshot](images/chap2-day2-q4.2.PNG)
<br/><br/>

**4.3) Add a transaction that takes in a parameter named myNewNumber and passes it into the updateMyNumber function. Verify that your number changed by running the script again.**     
<br/><br/>
![Screenshot](images/chap2-day2-q4.3.PNG)
![Screenshot](images/chap2-day2-q4.3-2.PNG)
<br/><br/>
