---

layout: col-sidebar
title: OWASP WrongSecrets
tags: wrongsecrets
level: 3
type: tool
pitch: Examples with how to not use secrets

---
<img src="assets/images/icon.png" alt="logo by Ben de Haan" width="100px" />

[![Github Stars](https://img.shields.io/github/stars/OWASP/wrongsecrets?label=Stars%20WrongSecrets&style=social)](https://github.com/OWASP/wrongsecrets/stargazers)
[![OWASP Lab Project](https://img.shields.io/badge/OWASP-lab%20project-48A646.svg)](https://owasp.org/projects/)
[![Release version](https://img.shields.io/github/v/release/OWASP/wrongsecrets)](https://github.com/OWASP/wrongsecrets/releases/latest)
[![Docker pulls](https://img.shields.io/docker/pulls/jeroenwillemsen/wrongsecrets.svg)](https://img.shields.io/docker/pulls/jeroenwillemsen/wrongsecrets.svg)
[![Tweet](https://img.shields.io/twitter/url/http/shields.io.svg?style=social)](https://twitter.com/intent/tweet?text=Want%20to%20dive%20into%20secrets%20management%20and%20do%20some%20hunting?%20try%20this&url=https://github.com/OWASP/wrongsecrets&hashtags=secretsmanagement,secrets,hunting,p0wnableapp,OWASP,WrongSecrets)
[<img src="https://raw.githubusercontent.com/mastodon/mastodon/main/app/javascript/images/app-icon.svg" width=16> Share on Mastodon](https://tootpick.org/#text=Want%20to%20dive%20into%20secrets%20management%20and%20do%20some%20hunting?%20try%20this%0A%0Ahttps://github.com/OWASP/wrongsecrets%20%23secretsmanagement,%20%23secrets,%20%23hunting,%20%23p0wnableapp,%20%23OWASP,%20%23WrongSecrets)

OWASP WrongSecrets is the first Secrets Management-focused vulnerable/p0wnable app! It can be used in security trainings, awareness demos, as a test environment for secret detection tools, and bad practice detection tooling.

![Image](https://raw.githubusercontent.com/OWASP/wrongsecrets/master/images/screenshot.png)

## Description

WrongSecrets is based on Java, Docker, Terraform, and a bit of scripting fun. It contains more than 25 exercises with various wrongly stored or misconfigured secrets - which you need to find. Finding these secrets will
 - Help you to look for secrets being misconfigured at your own environment, or target environments for bug bounties.
 - Help you to re-evaluate your own secrets management practices as well.

## Want to play?

There are multiple ways on how you can play/work with OWASP WrongSecrets. 
Want to play locally? Try 

```sh
docker run -p 8080:8080  jeroenwillemsen/wrongsecrets:latest-no-vault
``` 

Otherwie try one of the following online environments:

- [Online demo (Heroku Free)](https://wrongsecrets-ctf.herokuapp.com/ "Online demo on a free Heroku Dyno")
- [Online CTF demo env (Heroku Free)](https://wrongsecrets.herokuapp.com/ "Online demo on a free Heroku Dyno")
- [Online demo (Fly Free)](https://wrongsecrets.fly.dev/ "Online demo on a free Fly instance")
- [Online demo (Okteto Free)](https://wrongsecrets-commjoen.cloud.okteto.net/ "Online demo on a free Okteto namespace")

## Contributors

[![GitHub contributors](https://img.shields.io/github/contributors/OWASP/wrongsecrets.svg)](https://github.com/OWASP/wrongsecrets/graphs/contributors)

Leaders:

- [Ben de Haan @bendehaan](https://github.com/bendehaan)
- [Jeroen Willemsen @commjoen](https://github.com/commjoen)

Top contributors:

- [Nanne Baars @nbaars](https://github.com/nbaars)
- [Joss Sparkes @remakingeden](https://github.com/remakingeden)
- [Marcin Nowak @MarcinNowak-codes](https://github.com/MarcinNowak-codes)
- [Tibor Hercz @tiborhercz](https://github.com/tiborhercz)
- [Chris Elbring Jr. @neatzsche](https://github.com/neatzsche)
- [Puneeth Y](https://github.com/puneeth072003)
- [Filip Chyla @fchyla](https://github.com/fchyla)
- [Dmitry Litosh @Dlitosh](https://github.com/Dlitosh)
- [Josh Grossman @tghosth](https://github.com/tghosth)
- [Spyros @northdpole](https://github.com/northdpole)
- [Mike Woudenberg @mikewoudenberg](https://github.com/mikewoudenberg)
- [Ruben Kruiver @RubenAtBinx](https://github.com/RubenAtBinx)
- [Nicolas Humblot @nhumblot](https://github.com/nhumblot)
- [Finn @f3rn0s](https://github.com/f3rn0s)
- [Alex Bender @alex-bender](https://github.com/alex-bender)
- [Rick M @kingthorin](https://github.com/kingthorin)

Testers:

- [Dave van Stein @davevs](https://github.com/davevs)
- [Marcin Nowak @MarcinNowak-codes](https://github.com/MarcinNowak-codes)
- [Marc Chang Sing Pang @mchangsp](https://github.com/mchangsp)

Special mentions for helping out:

- [Madhu Akula @madhuakula](https://github.com/madhuakula)
- [Björn Kimminich @bkimminich](https://github.com/bkimminich)
- [Xiaolu Dai @saragluna](https://github.com/saragluna)
- [Jonathan Giles @jonathanGiles](https://github.com/JonathanGiles)

[Actual contributors at this point in time.](https://github.com/OWASP/wrongsecrets/graphs/contributors)

### Sponsorships

We would like to thank the following parties for helping us out:

[![gitguardian_logo.png](assets/images/gitguardian_logo.jpeg)](https://blog.gitguardian.com/gitguardian-is-proud-sponsor-of-owasp/)

[GitGuardian](https://blog.gitguardian.com/gitguardian-is-proud-sponsor-of-owasp/) for their sponsorship which allows us to pay the bills for our cloud-accounts.

[![jetbrains_logo.png](assets/images/jetbrains_logo.png)](https://www.jetbrains.com/)

[Jetbrains](https://www.jetbrains.com/) for licensing an instance of Intellij IDEA Ultimate edition to the project leads. We could not have been this fast with the development without it!

[![docker_logo.png](assets/images/docker_logo.png)](https://www.docker.com)

[Docker](https://www.docker.com) for granting us their Docker Open Source Sponsored program.

[![1password_logo.png](assets/images/1password_logo.png)](https://github.com/1Password/1password-teams-open-source/pull/552)

[1Password](https://github.com/1Password/1password-teams-open-source/pull/552) for granting us an open source license to 1Password for the secret detection testbed.

## Licensing

[![license](https://img.shields.io/github/license/OWASP/wrongsecrets.svg)](https://github.com/OWASP/wrongsecrets/blob/master/LICENSE)

This program is free software: You can redistribute it and/or modify it under the terms of the [AGPLv3 License](https://github.com/OWASP/wrongsecrets/blob/master/LICENSE).
OWASP WrongSecrets and any contributions are Copyright © by Jeroen Willemsen & the OWASP WrongSecrets contributors 2020-2023.

## Presentations about OWASP WrongSecrets

The project has been promoted at:

- [AllDayDevOps: Our secrets management journey from Code to Vault](https://www.alldaydevops.com/addo-speakers/jeroen-willemsen)
- [Conf42 DevSecOps 2021: Secrets-management: challenges from code to cloud](https://www.youtube.com/watch?v=EsMS7gOBrY4)
- [Club Cloud 2021: Securing your secrets in the cloud](https://youtu.be/lXMRTP5eg9Q)
- [OWASP Dutch Chapter Meetup: Our Secrets Management Journey: From Code to Vault](https://www.youtube.com/watch?v=qR6JCkZgOlY)
- [Application Security Podcast: Jeroen Willemsen & Ben de Haan -- Dirty little secrets](https://appsecpodcast.securityjourney.com/1730684/9864567-jeroen-willemsen-and-ben-de-haan-dirty-little-secrets)
- [Open Security Summit: OWASP Wrong Secrets: project goals, under the hood, and where do we go from here?](https://www.youtube.com/watch?v=EYkjgGuhOYw)
- [WrongSecrets demo - How not to store secrets with the project founder Jeroen Willemsen](https://www.youtube.com/watch?v=nqzxpgvLEv4&t=709s)
- [Security Journey: Jeroen Willemsen and Ben de Haan - Dirty little secrets](https://www.youtube.com/watch?v=0HGPnQAYFNY)
- [Meetup OWASP Bay Area: OWASP WrongSecrets: how to NOT mange your secrets](https://www.youtube.com/watch?v=oRUPVhp1Bfw)
- [Code to Cloud Virtual Summit: Learn How to (Not) Use Secrets with OWASP WrongSecrets!](https://start.paloaltonetworks.com/code-to-cloud-summit.html)
- [Teqnation 2022 Utrecht](https://teqnation.com/timetable-2022/)
- [Devops Pro Europe: Introducing OWASP WrongSecrets: How You Should NOT Handle Your Secrets](https://devopspro.lt/Jeroen-Willemsen/)
- [OWASP Virtual Appsec Europe 2022: OWASP WrongSecrets: We have a secret for Everyone!](https://whova.com/web/GKSmlhCK%2FWzBY2c8qqJ%2Bp7kNcnjsUQAQJ%2ByBsjLrbOo%3D/Agenda)
- [Tweakers Developers Summit: OWASP WrongSecrets - waar je je applicatiegeheimen (niet) moet neerzetten](https://tweakers.net/partners/devsummit2022/1684/bendehaan/)
- [OWASP Frankfurt #55 In-Person Event: Cloud Secrets,Cyber-Crime & Threat Modeling: Can't you keep a secret? Learn Secrets Management with OWASP WrongSecrets by Dan Gora, OWASP Frankfurt](https://www.meetup.com/nl-NL/it-security-stammtisch-frankfurt-owasp-u-w/events/286925136/)
- OWASP Hamburg Stammtich
- [DevSecOps Days 2022 Washington DC (Virtual): Learn How To (Not) Use Secrets With OWASP Wrong Secrets!](https://resources.sei.cmu.edu/library/asset-view.cfm?assetid=887917) and [see the Youtube recording here](https://www.youtube.com/watch?v=bYDnMYkRUN0)
- [AllDayDevOps - Learn how to (not) use secrets with OWASP WrongSecrets!](https://www.alldaydevops.com/addo-speakers/jeroen-willemsen)
- [Azure Cloud Security Group - Can't You Keep a Secret ? Cloud Native Secrets Management with OWASP Wrong Secrets](https://www.youtube.com/watch?v=Aafvip8XGDI)
- [OWASP Benelux Days 2022 - CTF Kickoff](https://www.owaspbenelux.eu/program/conference#Jeroen-Willemsen-and-Ben-De-Haan) with actual [CTF info](https://www.owaspbenelux.eu/program/ctf)
- Various Blogs: [A blog by Gitguardian](https://blog.gitguardian.com/gitguardian-is-proud-sponsor-of-owasp/), [Another blog by Gitguardian](https://blog.gitguardian.com/a-beginners-guide-to-owasp/), [Blogs by the author(s)](https://dev.to/commjoen), [A blog by Okteto](https://www.okteto.com/blog/practice-secrets-management-in-kubernetes-with-owasp-wrongsecrets-and-okteto/)
- Various Vlogs [Devsec for scale: Secrets Management Pt 1](https://www.youtube.com/watch?v=dxgXUQZgUnI)[Devsec for scale: Secrets Management Pt 2](https://www.youtube.com/watch?v=_gY0T9vIl4E), [Devsec for scale: Secrets Management Pt 3](https://www.youtube.com/watch?v=vtUk2bc34AY)

We would like to thank many people that have given a shoutout or a share about this project! Thank you for your forum-posts, blogs, and more!
