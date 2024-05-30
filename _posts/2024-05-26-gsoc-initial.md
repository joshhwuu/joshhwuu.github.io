---
layout: post
title: Google Summer of Code 2024 Initial Post
subtitle: My experience applying to GSoC.
share-img:
gh-repo: Rdatatable/data.table
gh-badge: [star]
tags: [R, GSoC, Google, data.table]
comments: true
author: Joshua Wu
---

Now that I'm just a few days away from officially starting work on my GSoC '24 project, I want to share my experience so far with the Google Summer of Code.

### About The Project
- Me: Joshua Wu
- Email: joshuawu2004@gmail.com
- Github: joshhwuu
- Mentors: Toby Dylan Hocking, Anirban Chetia
- Project Repo: [data.table](https://github.com/Rdatatable/data.table)

### First Impressions

As a first time participant in the Google Summer of Code and being new to open source software in general, I was very intimidated at the scale of GSoC and contributing. Going through each organization listed in past programs, I found every task/issue extremely daunting, which made me think that I wasn't talented enough to contribute. Eventually, I found data.table, which had a host of beginner-friendly tasks. With how my summer internship search was going at the time, I figured I might as well give it a try, otherwise I may find myself without work for the summer.

After some consideration, I found this [task](https://github.com/Rdatatable/data.table/issues/5096), which seemed like a simple enough fix and one that should get me through the door. Off the rip, the package maintainers were responsive and helpful. I spent a long time reproducing the described issue, and eventually was able to produce the problem locally, then I had to go through some iterations and tests. Along the way, the problem started spiraling in difficulty, as I was running into issues with encoding and GHA (GitHub Actions) automated tests, which caused the tests to fail on certain builds of Windows. But through a lot of trial and error, and the package maintainer's help, I was eventually able to get this PR merged. After merging, I contacted my GSoC mentors responsible for this data.table project via email, where I detailed the issue I chose, my PR, and asked the mentors to review.

Following that experience, I learned that:
- Being a good developer means more than just writing code, it also means having clear and effective communication.
- I shouldn't feel too intimidated by open source projects, the community is always willing to help!
- Large projects often contain big files, but if the code is readable and well documented, it makes future changes much easier.

### Applying to GSoC

After a few PRs merged, I was eventually invited to become a project member, which means I was able to make branches directly from the master branch of the GitHub repository, instead of pushing from a forked repository, making life easier for both reviewers and contributors. Around the same time, I realized I should start preparing my proposal for GSoC. It was a challenge to write the 15+ page proposal, detailing all the issues I planned to resolve while dealing with midterms, but with a few late nights I was able to get it done and submitted it to my mentors for review (and pass my exams).

Eventually, I was given the good news that my project has been selected for GSoC 2024, and I was ecstatic! It felt like my hard work has finally paid off, and now that I'm just days from the official start of coding, I'm looking forward to learning as much as I can from this fantastic opportunity.

If you are wanting to pursue the Google Summer of Code, just remember that although things may look intimidating, the open source community is always here to help you learn, and the only way to improve is to try!
