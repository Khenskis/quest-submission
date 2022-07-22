# Svetlana's Quest Submissions

# Chapter 1. Day 1.

### Quests:
1) Explain what the Blockchain is in your own words. 
2) Explain what a Smart Contract is. 
3) Explain the difference between a script and a transaction.

### Answers:

1) Blockchain is a shared database. 
   It is open, decentralized and public.
   Everyone can interact with it.  
   Nobody owns it ( no single person or group has control - rather, all users collectively retain control). 
   Anyone can view the data on it. 
   Blockchain stores data in blocks that are then linked together via cryptography. 

2) Smart contracts are programs stored on a blockchain that run when predetermined conditions are met. 
   Once a smart contract is deployed on the blockchain it will then execute the actions that were written inside of the contract.

3) A transaction is a paid. Script is free.
   A transaction changes the data on the Blockchain. Script only view data on the Blockchain, and do not change it.


# Chapter 1. Day 2.

### Quests:
1) What are the 5 Cadence Programming Language Pillars?
2) In your opinion, even without knowing anything about the Blockchain or coding, why could the 5 Pillars be useful?

### Answers:

1) Safety and security,
   Clarity,
   Approachability, 
   Developer Experience,
   Resource Oriented Programming.

2) The 5 Pillars are useful because:
   Safety and Security -  Developers can focus on building their contracts without having to worry about there being any security exploits in their   contracts.
   Clarity - Users can verify that the contract is safe and see clearly the real intention of developer. That’s cool. 
   Approachability - Developers can do transition  to Cadence with ease because  Cadence is written is very familiar to other programming languages. 
   Developer Experience - Cadence makes error messages very clear. So developers can easily debug an error.



# Chapter 2. Day 1.

### Quests:
For todays quest, please load up a new Flow playground by going to https://play.onflow.org just like we did in this lesson. You will use that for writing your code.
1) Deploy a contract to account 0x03 called "JacobTucker". Inside that contract, declare a constant variable named is, and make it have type String. Initialize it to "the best" when your contract gets deployed.
2) Check that your variable is actually equals "the best" by executing a script to read that variable. Include a screenshot of the output.


### Answers:
<img width="1106" alt="Снимок экрана 2022-07-13 в 18 13 13" src="https://user-images.githubusercontent.com/109018467/178742845-56e88a44-33fa-4afc-8e69-a0ff4ccec113.png">
<img width="1104" alt="Снимок экрана 2022-07-13 в 18 15 27" src="https://user-images.githubusercontent.com/109018467/178742917-5e7d868b-4374-460a-8152-7c749165f444.png">

# Chapter 2. Day 2.

### Quests: 

Please answer in the language of your choice.

1) Explain why we wouldn't call changeGreeting in a script.

2) What does the AuthAccount mean in the prepare phase of the transaction?

3) What is the difference between the prepare phase and the execute phase in the transaction?

4) This is the hardest quest so far, so if it takes you some time, do not worry! I can help you in the Discord if you have questions.

Add two new things inside your contract:

A variable named myNumber that has type Int (set it to 0 when the contract is deployed)
A function named updateMyNumber that takes in a new number named newNumber as a parameter that has type Int and updates myNumber to be newNumber
Add a script that reads myNumber from the contract

Add a transaction that takes in a parameter named myNewNumber and passes it into the updateMyNumber function. Verify that your number changed by running the script again.

### Answers:

1) Because we cannot change any information in script.
2) In the prepare phase of the transaction 'AuthAccount' means access the data in your account. Because on Flow accounts can store their own data.
3) Prepare phase do access the information/data in your account. Execute phase can't do that. If we want to change only some data in smart contract we call function in  the execute phase.
4) <img width="1103" alt="Снимок экрана 2022-07-23 в 01 40 36" src="https://user-images.githubusercontent.com/109018467/180567137-2833f9f1-3923-4b83-9f32-552fe4b0419a.png">




# Chapter 2. Day 3.

## Quests:
1) In a script, initialize an array (that has length == 3) of your favourite people, represented as Strings, and log it.

2) In a script, initialize a dictionary that maps the Strings Facebook, Instagram, Twitter, YouTube, Reddit, and LinkedIn to a UInt64 that represents the order in which you use them from most to least. For example, YouTube --> 1, Reddit --> 2, etc. If you've never used one before, map it to 0!

3) Explain what the force unwrap operator ! does, with an example different from the one I showed you (you can just change the type).

4) Using this picture below, explain...

What the error message means
Why we're getting this error
How to fix it

## Answers:

# Chapter 2. Day 4.

## Quests: 

1) Deploy a new contract that has a Struct of your choosing inside of it (must be different than Profile).

2) Create a dictionary or array that contains the Struct you defined.

3) Create a function to add to that array/dictionary.

4) Add a transaction to call that function in step 3.

Add a script to read the Struct you defined.

That's all! See you tomorrow folks ;)

## Answers:


# Chapter 3. Day 1.
# Chapter 3. Day 2.
# Chapter 3. Day 3.
# Chapter 3. Day 4.
# Chapter 3. Day 5.



### = ^_^ =
