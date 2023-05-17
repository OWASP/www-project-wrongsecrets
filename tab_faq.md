---
title: Creating passwords
layout: col-sidebar
tab: true
order: 4
tags: wrongsecrets
---

## Creating Passwords
You can create various types of passwords. OWASP WrongSecrets has quite a few of them as an example.
There are complex passwords, which you can easily create with tools like OpenSSL and/or password managers.
There are short passphrases, which you can easily remember
There are longer passphrases with a more extensive set of words involved.

### Complex passwords
Complex passwords can be easily generated securely using tools like OpenSSL (using `openssl rand 20 -base64`) or a password manager. For instance, the generation of challenge 31’s password. The password (SGF2ZSBhIG5pY2UgZGF5) was obtained using random information generated through OpenSSL.

Of course, we need to reference the [(in)famous XKCD on this topic](https://xkcd.com/936/).

### Short passphrases
Short passphrases uses short combinations of words. These are easy to think of and easy to remember. The solution to challenge0 is a good example here. Here a short passphrase(The first answer) is used as a solution.

### Longer passphrases
In other challenges we packed longer passphrases, which are still easy to remember, but do have a lot more entropy to them.

## References
NIST Digital Identity Guidelines: https://pages.nist.gov/800-63-3/sp800-63b.html
OWASP Authentication cheatsheet: https://cheatsheetseries.owasp.org/cheatsheets/Authentication_Cheat_Sheet.html 

