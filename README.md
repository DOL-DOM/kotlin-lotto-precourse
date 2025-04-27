# kotlin-lotto-precourse

## Feature List
1. Receive the purchase amount from the user.
2. Validate that the purchase amount is divisible by 1,000 KRW
3. Issue lottery tickets based on the purchase amount.
4. Each lottery ticket must consist of six unique numbers between 1 and 45.
5. Print the numbers of the purchased lottery tickets.
6. Receive six winning numbers from the user.
7. Receive one bonus number from the user.
8. Compare the user's tickets with the winning numbers to calculate the rank.
9. Print the number of winning tickets for each rank.
10. Calculate and print the total profit rate.
11. Throw an IllegalArgumentException and re-prompt the input if invalid data is entered.



#Project Structure
```
src
└── main
    └── kotlin
        └── lotto
            ├── Application.kt         
            ├── Lotto.kt                
            ├── Rank.kt                 
            ├── view
            │   ├── InputView.kt        
            │   └── OutputView.kt
            └── domain
                ├── LottoGenerator.kt
                ├── LottoManager.kt
                └── WinningLotto.kt
```

