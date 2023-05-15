# Automate the Boring Stuff - Al Sweigart
This repository documents my study of the book '**[Automate the Boring Stuff](https://automatetheboringstuff.com/2e/chapter0/)**' by **Al Sweigart**.

The code is my attempt at understanding the concepts and examples explained in the book.

I will be studying and referencing from the free online version of the book.

---

## Table of Contents:
- [Introduction](#Introduction)
- [Flow Control](##Flow-Control)


---

## Introduction:
### [passwordFile.py](https://github.com/nadupoy/Automate-the-Boring-Stuff-by-Al-Sweigart/blob/main/passwordFile.py)
I learnt about more [parameters](https://stackoverflow.com/questions/44901806/python-error-message-io-unsupportedoperation-not-readable) used in handling files after experiencing the following error when coding along to the book:

`io.UnsupportedOperation: not readable`

## Flow Control:
### [yourName.py](https://github.com/nadupoy/Automate-the-Boring-Stuff-by-Al-Sweigart/blob/main/yourName.py)
The while loop does not execute as expected even though the code is exactly the same as that used in the book.
The output is as shown below:

`Please type your name`

`John`

`Jane`

`Mary`

`your name`

`. . .`

The while loop does not exit even when the condition evaluates to `False`. Moreover, the `print` statement in the clause is seemingly ignored after the initial execution of the `while` loop.

The `while` loop clause should evaluate as follows:

`Please type your name.`

`John`

`Please type your name.`

`Jane`

`Please type your name.`

`Mary`

`Please type your name.`

`your name`

`Thank you!`