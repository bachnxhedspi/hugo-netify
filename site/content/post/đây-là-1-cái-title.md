---
title: Đây là 1 cái title
date: 2018-08-15T11:12:20.245Z
description: Chả có gì đâu mà
image: /img/nmveud7.png
---
When you start learning a new programming language, maybe you had been learning follow those steps: variable, assignment, string, operators… One major theme you need to focus is string operations. Fox example: get first name from fullname, find and censor all mobile numbers in message,…

Along the operation we usually need to process some common procedure. One repeated procedure is finding a substring and implement some operations over the substring. Maybe you had done like something like this in the very beginning of your learning path.

```
int checkMatchStubPattern(char* string) {
    for(int i = 0; i < strlen(string); i++) {
        // logic for checking string pattern
        ...
    }
    return ...
}
```
Not a wrong way, but a time consuming. You must change the checking logic in every case. More code, more bug and of course hard for maintainance. Luckily, Regular Expression - Regex come as a hero to solve those kind of problems: find, input validation… As a confirmation for the usage of Regex, every programming language supports Regex for string operations.
