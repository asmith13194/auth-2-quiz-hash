# Storing Passwords Quiz
## Would you like salt with your hash?


With your partner, in words both of you will understand 6 months from now, answer the following questions.

> A customer hires you to consult on a web app.  You notice that they are storing their passwords in plaintext.  What advice would you give the customer.  This advice should outline the risks of the current solution, and give a list of best practices for a new solution.

Risk: Storing plaintext passwords is utter buffoonery. Never store password to begin with let alone in plaintext.
Solution: Use a hashing algorithm. For added protection combine user passwords with salt(random generated string that is now tied to the password) then use hashing algorithm. Only store Hash/Salt.


> You are tasked for creating a RFP (request for proposal) for a new cryptographic hashing algorithm.  What requirements would you put in place for this new algorithm.

Requirements: No matter length of password hash always returns the same length. Small changes drastically change result, and even if the same password is used it generates a different hash.
