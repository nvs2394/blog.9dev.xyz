---
title: How to name your code follow Uncle Bob way
date: 2022-03-13
tags:
  - CleanCode
  - VariableNaming
  - FunctionNaming
banner: ./banner.png
---

banner: ./banner.png

⛔ Bad code

```go
function card() {
    return card
}
```

🆗 Good code

```go
function getCard() {
    return card
}
```

Here the name of the function is self-explanatory, and the variable names give us clues that the cities denote the start and end of something.

> Rule 1: Use nouns or short phrases with adjectives to name variables

⛔ 
```go
let u = {}
```

🆗 

```go
let user = {}
```
Aim to avoid redundancy in names as much as possible.

> Rule 2: The names of the booleans must resolve to a yes or no answer

⛔
```go
if(payment) {
	// do something
}
```
🆗 
```go
if(isValidPayment){
	// do something
}
```
Booleans have an on/off nature. As such, their names must reflect their character.

> Rule 3: Use verbs or short phrases with adjectives to name functions or methods

🆗
```go
function getPaymentMethod() {
 // do something()
}

function fetchWalletBalance(wallet Wallet) {
 return wallet.balance
}
```
*Avoid inconsistencies when using verbs for naming functions and stick to using the same verbs for the same actions.*

> Rule 4: Use nouns or short phrases with nouns to name classes

⛔
```javascript
class AppUser {
	// some methods/vars
}
```
🆗
```javascript
class User {
 // some methods/vars
}
```
*To avoid any confusion, make sure to use nouns and think before adding an extra word to the name.*

*Does it add any value, or does it make the meaning fuzzier?*

