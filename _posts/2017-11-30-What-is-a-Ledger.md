---
layout: post
title: What is a Ledger?
---

Today's post will set some context to serve as a precursor to discussing what blockchain is.

If you've been banking since before online banking was a thing, then you will most likely already be familiar with what I'm about to share with you.

For the rest of us, here goes.

If you have a bank account, then you have a ledger. It's the record of transactions associated with your account. You've probably seen it if you've ever looked at your bank statement or logged in to your online banking portal.

Your bank account has a ledger, and your bank uses this as a way to keep a record of everything about their customers' accounts, including who you've been paying, who's paid you, and what your current balance is. 

This is useful for the bank in order to ensure everyone has the correct balance in their account at any given time, and it's also used in case your past transaction history needs to be accessed for things like a transaction dispute or a warrant from law enforcement.

At the most basic level, all transactions in your ledger have a format similar to this:

```
Date/Time of Transaction
Transaction Amount
Payee (or Credit Amount if you made a deposit of some kind)
```

Given this, here's three transactions in a pretend ledger:

```
11/30/2017 Starting Balance: $12,575.25

1.  11/30/2017   -$15.75    Pizza Shack
New Balance: $12,559.50

2.  11/30/2017   +$500      Payroll Deposit
New Balance: $13,059.50

3.  11/30/2017   -$83.63    Pizza Palooza
New Balance: $12,975.87
```

Say my friend Thad, who works as an aid worker in a refugee camp overseas, is raising money for his next trip:

```
Thad: "Hey J.C., will you donate some money for my next trip?"

J.C.: "Yeah dude, definitely. Coming your way."
```

I then call my bank (or hop online) and transfer funds to Thad's account. This will create a new transaction entry in my ledger, like so:

```
11/30/2017 Starting Balance: $12,575.25

1.  11/30/2017    -$15.75     Pizza Shack
New Balance: $12,559.50

2.  11/30/2017    +$500       Payroll Deposit
New Balance: $13,059.50

3.  11/30/2017    -$83.63     Pizza Palooza
New Balance: $12,975.87

4. 11/30/2017     -$5,000     Thaddeus Daniels
New Balance: $7,975.87 
```

My bank guy entered the transaction into my account's ledger and initiated a transfer to Thad's bank. Depending on where Thad banks, it then may go through other banks before finally reaching Thad's bank and being added as a deposit to his account's ledger.

Easy enough, right?

Well, here's the issue: when I sent money to Thad (or when I made a transaction of any kind, for that matter), I had to rely on my bank (as well as Thad's bank and any other banks in between) to act accurately, ethically, safely, and timely.

All of these are important because:

* What if my bank entered $6,000 instead of $5,000? What if I needed that extra $1,000 for some bills coming through that same day?

* What if $4,000 was entered instead of $5,000? Then I'd have to waste time initiating another transfer, which could take another few days to process.

* What if $5,000 was entered, but only $4,000 was sent to Thad and $1,000 was sent to my bank guy's account because he's a dirtbag?

* What if my Thad's bank is hacked and his ledger is changed to show that only $500 came in?

* What if both banks are destroyed by a nuke?

* What if Thad had procrastinated with his fundraising and really needed that money today, but the bank transfer was going to take 3-5 days?

All of these are obviously hypotheticals, but none of them are beyond the realm of possibility. Organizations can make mistakes. Organizations can be corrupted. Organizations can be destroyed.

What if we could take the ledger out of the organization? What if we could distribute it publicly across thousands of individuals and ensure it stays safe, accurate, and untamperable?

Enter blockchain.