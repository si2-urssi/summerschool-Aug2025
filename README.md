# URSSI Summer School on Research Software and Open Science, August 2025
# Alaska Satellite Facility, University of Alaska Fairbanks
---

## Discussion and notes

[HackMD for notes/discussion](https://hackmd.io/@M0eajM-mS9CDKKt8Rq--0g/rJjaxzDdgg)

[Zulip chat room](https://urssi-softwareschool.zulipchat.com)

---

August 11-15 2025, Fairbanks, AK

Welcome! This is the repository for the 2025 URSSI Summer School on Research Software and Open Science, held at the University of Alaska Fairbanks.
We have had generous support organizing this school from the Alaska Satellite Facility and the Geophysical Institute, who are helping to host this school.
All instruction will happen in Butrovich Hall, room 109. The poster session
will be held in Akasofu Lobby, just up the hill from Butrovich hall.

We've created a map with various locations of the school highlighted, shown below.

![Map of University of Alaska Fairbanks, with buildings of interest for the
school boxed in blue](resources/UAF-Campus-map.png)


## Tentative schedule

| Time | Topic  | Instructor |
|:--|:--|:--|
| August 11th, 8:30-9am | Room Open, Coffee | |
| August 11th, 9-9:45am  | [Welcome and introductions](https://munkm.github.io/research-software-schools/school-intro-UAF.slides.html) | Madicken |
| August 11th, 9:45am-12 | [Collaboration with git and github / collaboration workflows](https://github.com/bsipocz/URSSI_2025Aug_first_PR) | Brigitta |
| August 11th, 12-1:00pm | Lunch | |
| August 11th, 1-2pm | [Collaboration with git and github / collaboration workflows](https://github.com/bsipocz/URSSI_2025Aug_first_PR) | Brigitta |
| August 11th, 2pm-5pm | [Software Design Principles, Modularity, Packaging](https://github.com/jakirkham/2025-packaging-python) | John |
|--|--|--|
| August 12th, 8:30-9am | Room Open, Coffee | |
| August 12th, 9am-12:30pm | [Peer Code Review and Community Approaches](resources/code_review.md) | Brigitta |
| August 12th, 12-1:30pm | Lunch | |
| August 12th, 1:30pm-3pm | Work Time | |
| August 12th, 3-5pm | Poster Session | Everybody |
|--|--|--|
| August 13th, 8:30-9am | Room Open, Coffee | |
| August 13th, 9am-12 | [Documentation and Versioning](https://github.com/TimMonko/urssi-docs) | Tim |
| August 13th, 12-1:00pm | Lunch | |
| August 13th, 1pm-3pm | Work Time | |
| August 13th, 3-4pm | Ethos of Open Science | Madicken |
| August 13th, 4-5pm | Open Tools and Resources | Joe |
| August 13th, 5-7pm | Optional: Tour at ASF Museum | Everybody |
|--|--|--|
| August 14th, 8:30-9am | Room Open, Coffee | |
| August 14th, 9am-12 | [Testing and Continuous Integration]() | John |
| August 14th, 12-1:00pm | Lunch | |
| August 14th, 1pm-2:30pm | Work Time | |
| August 14th, 3-4pm | Testing Notebooks | Brigitta |
| August 14th, 4-5pm | Open Data | Tim |
| August 14th, 6:00pm | School Dinner, Alaska Salmon Bake | Everybody |
|--|--|--|
| August 15th, 8:30-9am | Room Open, Coffee | |
| August 15th, 9am-12 | [Open Practices and Software Citation]() | Madicken |
| August 15th, 12-1:00pm | Lunch | |
| August 15th, 1pm-3pm | Work Time | |
| August 15th, 3-4pm | Open Results | Joe |
| August 15th, 4-5pm | [Working with the Cloud]() | Joe |
|--|--|--|

Each morning and afternoon session will be split up with a break, and we'll have lunch organized on-site M-F.

Monday-Wednesday evening of the school are free and you’re welcome to
self-organize dinners with other school participants! [fairbanks-food-locations.pdf](resources/fairbanks-food-locations.pdf) is a file with a list
of popular food / dining establishments around Fairbanks that you can
use to get started.

Please also check out the [UAF-resources.md](resources/UAF-info.md) document that includes information on how to get around campus, bike rentals, and information on your lodging.

We will have a final school dinner at Alaska Salmon Bake, in Pioneer Park.
If you have family nearby/joining you in Alaska, they are welcome to join
us for the dinner (and we’d love to have them!). Our funding will not cover
their meal, so when we are seated they will need to go to the cashier and
order off the menu.

[Distributing your Science]: https://github.com/matthewfeickert-talks/talk-urssi-summer-school-2024

## Code of Conduct

We have adopted a [code of conduct](CODE_OF_CONDUCT.md) for the URSSI Summer School and all associated spaces, both physical and digital. Please review this.

## Instructors

[Madicken Munk](https://github.com/munkm) is an Assistant Professor in the School of Nuclear Science and Engineering at Oregon State University. Previously, she was a postdoc at the University of Illinois' National Center for Supercomputing Applications where she was a maintainer and release manager of yt, a visualization package for simulation data.

[Joseph H. Kennedy](https://github.com/jhkennedy) is a Staff Scientist at the Alaska Satellite Facility. He has a background in computational glaciology and Earth system modeling, and develops (primarily) python-based, open-source scientific software and focuses on building open science workflows working at “big” data/computational scales.

[Brigitta Sipőcz](https://github.com/bsipocz) is a Research Software Engineer at Caltech/IPAC at the NASA/IPAC Infrared Science Archive. She has a research astronomy background and she is a maintainer for various astronomy Python libraries. She propaply cares way too much about tooling and infrastructure with a keen interest on solving CI/CD challenges of executable tutorial content.

[John Kirkham](https://github.com/jakirkham) is a Principal System Software Engineer at NVIDIA on the RAPIDS team. His background is in Physics with past research projects focused on the intersection of Physics and Biology. As a software engineer, John has worked on a range of different problems from software packaging, distributed computing, data storage, etc..

[Tim Monko](https://github.com/TimMonko) is a Postdoc in the Department of Pediatrics at the University of Minnesota studying neural development and creating bioimage analysis tools. He is also community manager and core team member of napari, a multidimensional Python data viewer that can be extended by many domain-specific plugins.

## Teaching assistants / aids

* Lucio Queiroz
* Sujay Shankar
* Cong Gao

## Requirements

You will need a laptop with a Mac, Linux, or Windows operating system (not a tablet, Chromebook, etc.) that you have administrative privileges on, and need some specific software packages installed:


**On your machine**
- the Bash shell; you should only have to set this up if you are using a Windows machine, following the [Software Carpentry setup instructions](http://carpentries.github.io/workshop-template/#setup)
- Git [installed](https://swcarpentry.github.io/git-novice/#installing-git) and [configured](https://swcarpentry.github.io/git-novice/02-setup.html) on your local machine to attribute commits to you and your email address. Note for windows users: if you do not already have git set up locally, you can choose either git bash or installing the windows subsystem for linux. Both install options are included in the link above.
- Github SSH keys set up. You will need this to be able to push/pull from
github with git on your local machine. If you prefer to use https and already
have that configured, that's fine. You can find out more about
[creating](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent) and setting up
ssh keys for your github account [here](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account).
- Python 3.x; we recommend installing [Miniforge](https://conda-forge.org/download/) to manage the dependencies you'll be using in this school. Some lessons will require additional dependencies that you'll install during the course.
- a text editor, preferably one designed for writing code. Instructors in this school use emacs, vim, and vscode. Choose something you are comfortable with.

**In the browser**
- You will need a [GitHub](https://github.com/) account to participate in the school. Make sure you have your [github authentication](https://swcarpentry.github.io/git-novice/#creating-a-github-account) set up as well. Note that we do understand that you may choose to use other git hosting options, such as gitlab. We will be instructing lessons through github because of its current ubiquity in the ecosystem, but you are welcome to continue your software work outside of the school with whichever tools you prefer.
- Sign in to the school's Zulip instance to communicate with students and instructors throughout the course: https://urssi-softwareschool.zulipchat.com

Specific Python packages will be installed during lessons throughout the school.

## Projects

Most of your work time will be spent on an individual project where you develop a research software package.
You are expected to come with idea or some basis for a project.

Ideally, this should be something that supports your work and that you would (or could) continue developing or using after the summer school.
We hope that most—or at least some—of the projects will eventually be submitted to the [Journal of Open Source Software (JOSS)](https://joss.theoj.org), which we'll briefly talk about on the final day.

## Reimbursements

Please follow the instructions you will receive over email and reach out to Madicken Munk with any questions or concerns. For detailed instructions on the
reimbursement process, please see [reimbursement-process.md](reimbursement-process.md).

## Feedback

TBD
