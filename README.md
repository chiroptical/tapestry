TaPesTRY (Guided `T`our `P`ython `T`h`R`ough jup`Y`ter)
---

#### Purpose

This workshop is designed to introduce users of differing experience levels to
new concepts in Python through Jupyter. The problem with traditional lectures
(personal opinion) is that I can't reach all of my audience. Either I am too
general or too complex and users walk away feeling like they wasted 3-4 hours.
Additionally, the resources I host are Linux based which I have been told are
intimidating. I have built a JupyterHub at Pitt to give users who are
unfamiliar with Linux (majority of them) access to our advanced research computer
at Pitt without the barrier of Linux command line, SSH, etc.

#### Location Specific Details

At Pitt, I built a JupyterHub server sitting behind the Pitt load balancer
supporting single-sign-on. Additionally, we have an Isilon filesystem on the
cluster where users files exist. There are some things in the slides which are
specific to my instance. You could for example launch these from
[binder](https://mybinder.org), but I haven't done any testing with this yet.

#### Motivation

The workshop was modeled after [Jake VanderPlas's Whirlwind Tour of
Python](https://github.com/jakevdp/WhirlwindTourOfPython). 

#### Running the Workshop

The key is to be available. The students are going to explore Python by
themselves but they are going to have hiccups. I suggest using a system to
identify issues.  Give every student a blue and red cup. Blue cup is good, red
cup is bad. The assistants can then move around and answer questions. If you
have any frequently asked questions, address them in front of the class.

#### Suggestions

I appreciate any and all suggestions. For each workshop, I embed a Google Form
at the bottom asking for suggestions (note it is empty because I ask specific
questions). Additionally, if you have any suggestions for me, submit an issue
here on Github.

#### To Do

1. Test binder service with these notebooks for users which don't have accounts
   at Pitt (and for general usability of the workshop)
