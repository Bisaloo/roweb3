---
slug: "commcall-pkg-community"
title: Set Up Your Package to Foster a Community - Community Call Summary
author:
  - Maëlle Salmon
  - Hugo Gruson
  - Steffi LaZerte
  - Stefanie Butland
date: 2021-04-28
tags:
  - packages
  - community
  - contributors
  - community-call
  - labelathon
  - github
description: "Summary of the Community Call on Setting Up Your Package to Foster a Community"
output: 
  html_document:
    keep_md: true
---

Last Thursday we held a [Community Call](/commcalls/apr2021-pkg-community/) discussing how to set up a Package to Foster a Community. 

This call included speakers [Maëlle Salmon](/author/maëlle-salmon/), [Hugo Gruson](/author/hugo-gruson) and [Steffi LaZerte](/author/steffi-lazerte), and was moderated by [Stefanie Butland](/author/stefanie-butland).

{{< figure src = "speakers.png" class = "center" width = "600" alt = "Headshots of the three speakers">}}



## Summarizing the community call

Scientific software development - and with that R packages - is a community effort. While there are often just a handful of developers maintaining an R package, the development really starts to thrive when users start to contribute to the code base. 

In principle, every open source package has an unspoken open invitation to contribute. The question is how this invisible rule can be turned into something more explicit (and less intimidating) so that users who want to contribute can do so easily and feel welcomed and at ease. This brings us to the topic of rOpenSci's last community call. 

During one hour, several  speakers mentioned the bits and pieces of an R package that invite code contribution and manage expectations of users/contributors (say a contributor guide or using well-defined issues on Github), as well as the importance of the soft skills of the maintainer; for example how they interact with a contributor (not ignoring them, leaving opportunities to learn, being kind when saying "no"). 


### Speakers

The three speakers were: 

- Maëlle Salmon, a research software engineer, part-time with rOpenSci
- Hugo Gruson, a research software engineer and evolutionary biologist
- Steffi LaZerte, an R programming consultant, teacher, and part-time community assistant at rOpenSci


### Material

1. Living document
https://docs.google.com/document/d/1UpYoeMoPWR11JTmxYoypXkA5xvWgV-e4aXCy6pd-Ri8/edit

2. Recording: https://ropensci.org/commcalls/apr2021-pkg-community/

**Moments** 

- 0:00 Stefanie Butland: Welcome + introductions
- 4:55 Maëlle Salmon: Community of a package
- 20:00 Hugo Gruson: Journey from user to contributor
- 32:28 Steffi LaZerte: Github Issues as the low hanging fruits
- 43:58 Q & A

### Maëlle Salmon: Community of a package

A package has many different actors - the package authors, the users, the contributors - and they may act more or less with each other. 

Each role has slightly different needs. Everyone wants a better, well-maintained package. But the authors may want citations and grateful users, the users themselves may want certain features, and the contributors might seek recognition. 

Also, authors may need help in tackling issues and who better to help than someone with a user perspective!

Before diving into tips, Maëlle talked about how authors can improve their communication with contributors. Being kind will certainly retain contributors, rather than driving them away. But emojis can also be a great tool to compensate for nuances, for example, when having to say "no". 

Maëlle then suggested **three steps** to foster a community for a package: 

1. Define rules & standards for your package
2. Add them in publicly visible places
3. Help users & contributor find them (put links to these things everywhere: in Github repository and pkgdown website)

Some "rules & standards" include: 

- Add a **code of conduct**: `usethis::use_code_of_conduct()`
- Add a **citation** to help people to cite your package: `usethis::use_citation()`
- Add a **contribution guide**: store as `CONTRIBUTING.md`, add style preferences, process preferences, scope lined out, how you prefer testing to work.

{{<figure src = "summary_maelle.png" class = "center" width = "600" alt = "Summary slide of Maelles talk.">}}



### Hugo Gruson: Journey from user to contributor

Hugo spelled out the obvious - that every package contributor is a) a user first and b) starts out as a beginner. 

Hugo himself followed his favourite package where at one point he noticed something that needed fixing. So he fixed it - an intimidating process at first. But he repeated that, and after some time became an official maintainer. 

Hugo's talk focussed on how to facilitate the transition from user to contributor and suggested **five tips** for package maintainers to make contributing less scary:

1) **Have confidence in your project + expect contribution**

(if you don't, you may miss messages from users)

2) **Show that you are available and want to communicate**

Use Github, Twitter, email for that. For example, tweet NEWS file after a release.

3) **Don't let contributors work for nothing / feel ignored**. 

- Mention the name of the person. 
- Keep them in the loop. 
- Always have the latest version on Github. 
- Share a roadmap of project. 

4) **Reduce workload for contributors**

Disable failing tests. Disable unimportant bots (Hugo mentioned the the notoriously confusing coverage bot)

5) **Leave opportunities to learn**

In Github, disable "allow edits from maintainers", as this is demotivating ("Don't take the keyboard from the learner", Carpentry)

{{<figure src = "summary_hugo.png" class = "center" width = "600" alt = "Summary slide of Hugo's talk.">}}



### Steffi LaZerte: Github Issues as the low hanging fruits

Steffi found the low-hanging fruits in making packages more contributor-friendly - [Github issues](https://github.com/issues)!

Github issues can be labeled, and labels can be searched by users who want to become contributors but are maybe too shy to tackle an unlabelled issue. 

So why not label some well-defined issues with `"help wanted"`, a clear open invitation to users. 

Other options for labeling include: 


{{<figure src = "summary_steffi.png" class = "center" width = "600" alt = "Alternative issue labels from Steffi's talk.">}}


Because package maintainers rarely have time for this, the idea of a labelathon - labeling issues in a social setting - was born (sign up here [LINK]).


## Questions

There were lots of questions and not all could be answered during the call (see the [living document](https://docs.google.com/document/d/1UpYoeMoPWR11JTmxYoypXkA5xvWgV-e4aXCy6pd-Ri8/edit) for questions and answers). 

An interesting one was "Contributor license agreement" or CLA in short (mentioned in Maëlle's talk): Apparently, this is important for large collaborations (at least in the US) to make sure that software does not break because users ask any code back.

## Labelathon
