---
title: CTF
layout: col-sidebar
tab: true
order: 2
tags: wrongsecrets
---

## CTF

### With just OWASP WrongSecrets

We support playing CTFs with OWASP WrongSecrets! Want to know more? Have a look at [the Git repo README](https://github.com/OWASP/wrongsecrets#ctf) and [the additional CTF documentation](https://github.com/OWASP/wrongsecrets/blob/master/ctf-instructions.md)

### With OWASP WrongSecrets-CTF-Party

Want to play OWASP WrongSecrets in a large group in CTF mode, but not go over all the hassle of setting up local copies of OWASP WrongSecrets? Here is [OWASP WrongSecrets CTF Party](https://github.com/OWASP/wrongsecrets-ctf-party)! This is a fork of [OWASP MultiJuicer](https://github.com/iteratec/multi-juicer), which is adapted to become a dynamic multi-tenant setup for doing a CTF together!

Note that we:

- have a [Webtop](https://docs.linuxserver.io/images/docker-webtop) integrated for each player
- have a WrongSecrets instance integrated for each player
- A working admin interface which can restart both or delete both (by deleting the full namespace)
- Do not support any progress watchdog as you will have access to it, we therefore disabled it.
- It can cleanup old & unused namespaces automatically.

## Special thanks

Special thanks to [@commjoen](https://github.com/commjoen), [@madhuakula](https://github.com/madhuakula), [@bendehaan](https://github.com/bendehaan), and [@mikewoudenberg](https://github.com/mikewoudenberg), and [@osamamagdy](https://github.com/osamamagdy) for making this port a reality!