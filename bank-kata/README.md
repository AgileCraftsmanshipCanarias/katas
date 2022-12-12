# Bank kata

> This kata is original from [sandromancuso/Bank-kata](https://github.com/sandromancuso/Bank-kata)
> 
> Which is based in [How Object-Oriented Are You Feeling Today? - Krzysztof Jelski](https://www.slideshare.net/KrzysztofJelski/how-object-oriented-are-you-feeling-today) (Session on the Software Craftsmanship UK 2011 conference)
> 
> Based also in the video [Outside In TDD](https://www.youtube.com/watch?v=XHnuMjah6ps)

## Requirements

Create a simple bank application with the following features

* Deposit into Account
* Withdraw from an Account
* Print a bank statement to the console

### Acceptance criteria

Given a client makes a deposit of 1000 on 20/01/2022

And a deposit of 2000 on 23/01/2022

And a withdrawal of 500 on 24/01/2022

When she prints her bank statement  

Then she would see at the terminal

```
DATE | AMOUNT | BALANCE
24/01/2012 | 500.00 | 2500.00
23/01/2012 | 2000.00 | 3000.00
20/01/2012 | 1000.00 | 1000.00
```

## Starting points and constraints

1. Start with a class using the following structure

    ```java
    public class Account {
        public void deposit(int amount);
        public void withdraw(int amount);
        public void printStatement();
    }
    ```

2. You are **not allowed** to add any other public method to this class.
3. Use Strings and Integers for dates and amounts (keep it simple)
4. Don't worry about spacing in the statement printed on the console

## Code templates

You can choose a tempalte from the [kata-setup](https://github.com/AgileCraftsmanshipCanarias/kata-setup) repo
