---
layout: col-sidebar
title: OWASP WrongSecrets
tags: wrongsecrets
level: 3.5
type: tool
pitch: Examples with how to not use secrets
---

<!-- Rebuild 001 -->

<img src="assets/images/icon.png" alt="logo by Ben de Haan" width="100px" />

[![Github Stars](https://img.shields.io/github/stars/OWASP/wrongsecrets?label=Stars%20WrongSecrets&style=social)](https://github.com/OWASP/wrongsecrets/stargazers)
[![OWASP Production Project](https://img.shields.io/badge/OWASP-production%20project-48A646.svg)](https://owasp.org/projects/)
[![Release version](https://img.shields.io/github/v/release/OWASP/wrongsecrets)](https://github.com/OWASP/wrongsecrets/releases/latest)
[![OpenSSF Best Practices](https://bestpractices.coreinfrastructure.org/projects/7024/badge)](https://bestpractices.coreinfrastructure.org/projects/7024)
[![Docker pulls](https://img.shields.io/docker/pulls/jeroenwillemsen/wrongsecrets.svg)](https://hub.docker.com/r/jeroenwillemsen/wrongsecrets)
[![Tweet](https://img.shields.io/twitter/url/http/shields.io.svg?style=social)](https://twitter.com/intent/tweet?text=Want%20to%20dive%20into%20secrets%20management%20and%20do%20some%20hunting?%20try%20this&url=https://github.com/OWASP/wrongsecrets&hashtags=secretsmanagement,secrets,hunting,p0wnableapp,OWASP,WrongSecrets)
[<img src="https://img.shields.io/badge/-MASTODON-%232B90D9?style=for-the-badge&logo=mastodon&logoColor=white" width=86>](https://tootpick.org/#text=Want%20to%20dive%20into%20secrets%20management%20and%20do%20some%20hunting?%20try%20this%0A%0Ahttps://github.com/OWASP/wrongsecrets%20%23secretsmanagement,%20%23secrets,%20%23hunting,%20%23p0wnableapp,%20%23OWASP,%20%23WrongSecrets)

OWASP WrongSecrets is the first Secrets Management-focused vulnerable/p0wnable app! It can be used as a stand-alone game, as part of security trainings, awareness demos, as a test environment for secret detection tools, and bad practice detection tooling. It even has a supporting CTF platform to play the game in a larger group.

Want to give it a shot? Go to [our Heroku demo environment](https://wrongsecrets.herokuapp.com/)

![Image](https://raw.githubusercontent.com/OWASP/wrongsecrets/master/images/screenshot.png)

## Description

WrongSecrets is based on Java, Docker, Terraform, and a bit of scripting fun. It contains more than 40 exercises with various wrongly stored or misconfigured secrets - which you need to find. Finding these secrets will

- Help you to look for secrets being misconfigured at your own environment, or target environments for bug bounties.
- Help you to re-evaluate your own secrets management practices as well.

## Want to play?

There are multiple ways on how you can play/work with OWASP WrongSecrets.
Want to play locally? Try

```sh
docker run -p 8080:8080  jeroenwillemsen/wrongsecrets:latest-no-vault
```

Otherwise, try one of the following online environments:

- [Online demo env (Heroku)](https://wrongsecrets.herokuapp.com/ "Online demo on a Heroku Dyno")
- [Online CTF demo (Heroku)](https://wrongsecrets-ctf.herokuapp.com/ "Online CTF demo on a Heroku Dyno")
- [Online demo (Okteto Free)](https://wrongsecrets-commjoen.cloud.okteto.net/ "Online demo on a free Okteto namespace")
- [Online CTF demo (Okteto Free)](https://wrongsecrets-ctf-commjoen.cloud.okteto.net/ "Online demo on a free Okteto namespace")

Or try to deploy it using free services:

[![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy?repo=https://github.com/OWASP/wrongsecrets) 

[![Deploy to Okteto](https://okteto.com/develop-okteto.svg)](https://cloud.okteto.com/deploy?repository=https://github.com/OWASP/wrongsecrets.git&branch=master&filename=okteto/okteto.yml)


## Contributors

[![GitHub contributors WrongSecrets](https://img.shields.io/github/contributors/OWASP/Wrongsecrets?label=Contributors%20WrongSecrets)](https://github.com/OWASP/wrongsecrets/graphs/contributors) [![GitHub contributors WrongSecrets-ctf-party](https://img.shields.io/github/contributors/OWASP/Wrongsecrets-ctf-party?label=Contributors%20WrongSecrets-ctf-party)](https://github.com/OWASP/wrongsecrets-ctf-party/graphs/contributors) [![GitHub contributors WrongSecrets-binaries](https://img.shields.io/github/contributors/OWASP/Wrongsecrets-binaries?label=Contributors%20WrongSecrets-binaries)](https://github.com/OWASP/wrongsecrets-binaries/graphs/contributors)

Leaders:

- [Ben de Haan @bendehaan](https://www.github.com/bendehaan)
- [Jeroen Willemsen @commjoen](https://www.github.com/commjoen)

Top contributors:

- [Jannik Hollenbach @J12934](https://www.github.com/J12934)
- [Puneeth Y @puneeth072003](https://www.github.com/puneeth072003)
- [Joss Sparkes @RemakingEden](https://www.github.com/RemakingEden)

Contributors:

- [Nanne Baars @nbaars](https://www.github.com/nbaars)
- [Marcin Nowak @drnow4u](https://www.github.com/drnow4u)
- [Rodolfo Cabral Neves @roddas](https://www.github.com/roddas)
- [Osama Magdy @osamamagdy](https://www.github.com/osamamagdy)
- [Divyanshu Dev @Novice-expert](https://www.github.com/Novice-expert)
- [Tibor Hercz @tiborhercz](https://www.github.com/tiborhercz)
- [Chris Elbring Jr. @neatzsche](https://www.github.com/neatzsche)
- [Diamond Rivero @diamant3](https://www.github.com/diamant3)
- [Adarsh A @adarsh-a-tw](https://www.github.com/adarsh-a-tw)
- [Filip Chyla @fchyla](https://www.github.com/fchyla)
- [Dmitry Litosh @Dlitosh](https://www.github.com/Dlitosh)
- [Turjo Chowdhury @turjoc120](https://www.github.com/turjoc120)
- [Norbert Wolniak @nwolniak](https://www.github.com/nwolniak)
- [Josh Grossman @tghosth](https://www.github.com/tghosth)
- [alphasec @alphasecio](https://www.github.com/alphasecio)
- [CaduRoriz @CaduRoriz](https://www.github.com/CaduRoriz)
- [Madhu Akula @madhuakula](https://www.github.com/madhuakula)
- [Mike Woudenberg @mikewoudenberg](https://www.github.com/mikewoudenberg)
- [Spyros @northdpole](https://www.github.com/northdpole)
- [Vineeth Jagadeesh @djvinnie](https://www.github.com/djvinnie)
- [RubenAtBinx @RubenAtBinx](https://www.github.com/RubenAtBinx)
- [za @za](https://www.github.com/za)
- [Alex Bender @alex-bender](https://www.github.com/alex-bender)
- [Nicolas Humblot @nhumblot](https://www.github.com/nhumblot)
- [Rick M @kingthorin](https://www.github.com/kingthorin)
- [Shlomo Zalman Heigh @szh](https://www.github.com/szh)
- [Fern @f3rn0s](https://www.github.com/f3rn0s)

Testers:

- [Dave van Stein @davevs](https://www.github.com/davevs)
- [Marcin Nowak @drnow4u](https://www.github.com/drnow4u)
- [Marc Chang Sing Pang @mchangsp](https://www.github.com/mchangsp)
- [Vineeth Jagadeesh @djvinnie](https://www.github.com/djvinnie)

Special thanks:

- [Madhu Akula @madhuakula @madhuakula](https://www.github.com/madhuakula)
- [Björn Kimminich @bkimminich](https://www.github.com/bkimminich)
- [Dan Gora @devsecops](https://www.github.com/devsecops)
- [Xiaolu Dai @saragluna](https://www.github.com/saragluna)
- [Jonathan Giles @jonathanGiles](https://www.github.com/jonathanGiles)

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

[![AWS Open Source](assets/images/aws.svg.png)](https://aws.amazon.com/)

[AWS](https://aws.amazon.com/) for granting us AWS Open Source credits which we use to test our project and the [Wrongsecrets CTF Party](https://github.com/OWASP/wrongsecrets-ctf-party) setup on AWS.

#### Individual supporters

{% assign individual_supporter = site.data.ow_attributions | uniq %}
{% for supporter in individual_supporter %}

- {{ supporter | strip_html | strip_newlines | strip }}
  {% endfor %}
- _You want to appear on this list?_
  [Donate to OWASP here! 🤲](https://owasp.org/donate/?reponame=www-project-wrongsecrets&title=OWASP+wrongsecrets)<!-- @IGNORE PREVIOUS: link -->

## Licensing

[![license](https://img.shields.io/github/license/OWASP/wrongsecrets.svg)](https://github.com/OWASP/wrongsecrets/blob/master/LICENSE)

This program is free software: You can redistribute it and/or modify it under the terms of the [AGPLv3 License](https://github.com/OWASP/wrongsecrets/blob/master/LICENSE).
OWASP WrongSecrets and any contributions are Copyright © by Jeroen Willemsen & the OWASP WrongSecrets contributors 2020-2023.

## Want to help out?

You can help us in many ways:

- Star us on github: <a class="github-button" href="https://github.com/OWASP/WrongSecrets" data-color-scheme="no-preference: light; light: light; dark: light;" data-size="large" data-show-count="true" aria-label="Star OWASP/WrongSecrets on GitHub">Star Wrongsecrets on Github</a>
- Promote us using [![Tweet](https://img.shields.io/twitter/url/http/shields.io.svg?style=social)](https://twitter.com/intent/tweet?text=Want%20to%20dive%20into%20secrets%20management%20and%20do%20some%20hunting?%20try%20this&url=https://github.com/OWASP/wrongsecrets&hashtags=secretsmanagement,secrets,hunting,p0wnableapp,OWASP,WrongSecrets)
  [<img src="https://img.shields.io/badge/-MASTODON-%232B90D9?style=for-the-badge&logo=mastodon&logoColor=white" width=86>](https://tootpick.org/#text=Want%20to%20dive%20into%20secrets%20management%20and%20do%20some%20hunting?%20try%20this%0A%0Ahttps://github.com/OWASP/wrongsecrets%20%23secretsmanagement,%20%23secrets,%20%23hunting,%20%23p0wnableapp,%20%23OWASP,%20%23WrongSecrets).
- Promote us with a Blog, Vlog, Podcast, or presentation on a conference. Or use our materials to organize a CTF! If you do, let us know, so we can list your event or publication here on the webiste.
- Work with us on the project! Take a look at the [Readme of the project](https://github.com/OWASP/wrongsecrets), [How to contribute](https://github.com/OWASP/wrongsecrets/blob/master/CONTRIBUTING.md), and the [Github Issues](https://github.com/OWASP/wrongsecrets/issues). If you want to contribute to an issue: make sure it is not yet assigned to someone, comment on it with your intention, and then we can assign it to you.
- [Sponsor our project](https://owasp.org/donate/?reponame=www-project-wrongsecrets&title=OWASP+wrongsecrets)! We will use the money for covering our cloud costs (building & maintaining the project in 3 clouds costs money). And soon we hope to be able to buy you some stickers if you do ;-).

## Presentations about OWASP WrongSecrets

The project has been promoted at:

- [AllDayDevOps: Our secrets management journey from Code to Vault](https://www.alldaydevops.com/addo-speakers/jeroen-willemsen)
- [Conf42 DevSecOps 2021: Secrets-management: challenges from code to cloud](https://www.youtube.com/watch?v=EsMS7gOBrY4)
- [Club Cloud 2021: Securing your secrets in the cloud](https://youtu.be/lXMRTP5eg9Q)
- [OWASP Dutch Chapter Meetup: Our Secrets Management Journey: From Code to Vault](https://www.youtube.com/watch?v=qR6JCkZgOlY)
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
- [Azure Cloud Security Meetup: Cloud-Native Secrets Management with OWASP WrongSecrets by Dan Gora](https://www.youtube.com/watch?v=Aafvip8XGDI&t=2505s)
- [OWASP Benelux Days 2022 - CTF Kickoff](https://www.owaspbenelux.eu/program/conference#Jeroen-Willemsen-and-Ben-De-Haan) with actual [CTF info](https://www.owaspbenelux.eu/program/ctf)
- [WeHackPurple: Don’t make the same mistakes we did: How you can do secrets management better with OWASP WrongSecrets](https://community.wehackpurple.com/events/dont-make-the-same-mistakes-we-did-how-you-can-do-secrets-management-better-with-owasp-wrongsecrets)
- Coverage on youtube: [walkthrough by sec right](https://youtu.be/tSQATLTuSqQ?si=DwCnQ4FlQQALGVfZ)
- Various Blogs: [A blog by Gitguardian](https://blog.gitguardian.com/gitguardian-is-proud-sponsor-of-owasp/), [Another blog by Gitguardian](https://blog.gitguardian.com/a-beginners-guide-to-owasp/), [Blogs by the author(s)](https://dev.to/commjoen), [A blog by Okteto](https://www.okteto.com/blog/practice-secrets-management-in-kubernetes-with-owasp-wrongsecrets-and-okteto/), [A blog by Nec](https://jpn.nec.com/cybersecurity/blog/230707/index.html), [A blog from vineeth.dj](https://medium.com/@vineeth.dj/owasp-wrongsecrets-writeup-24ad3460be0a).
- Various Podcasts: [Application Security Podcast: Jeroen Willemsen & Ben de Haan -- Dirty little secrets](https://appsecpodcast.securityjourney.com/1730684/9864567-jeroen-willemsen-and-ben-de-haan-dirty-little-secrets), [Devsec for scale: Secrets Management Pt 1](https://www.youtube.com/watch?v=dxgXUQZgUnI), [Devsec for scale: Secrets Management Pt 2](https://www.youtube.com/watch?v=_gY0T9vIl4E), [Devsec for scale: Secrets Management Pt 3](https://www.youtube.com/watch?v=vtUk2bc34AY).

We would like to thank many people that have given a shoutout or a share about this project! Thank you for your forum-posts, blogs, and more!
