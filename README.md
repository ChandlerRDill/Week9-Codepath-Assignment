# Week9-Codepath-Assignment
Codepath Assignment for Week 9's honeypot challenge

I spent about 6 hours in total on this assignment.

Using the google cloud sdk through an mhn-admin VM, I deployed the Ubuntu - Dionaea with HTTP honeypot as specified in the instructions.

The biggest issues I ran into during the development of this lab was the constant caution I had before each step; making sure that I wasn't inputting the incorrect commands that would set the wrong configurations for the VM's took several minutes at a time.

I let my honeypot run for about ~35 minutes, in which I received 8 attacks, 7 of which were foreign attacks. I did not receive any malware samples in that time. I will continue to let my honeypot run for the next several hours before the due date in an attempt to capture malware samples.

As of this writing, no unresolved questions have been raised. Although, to my surprise, as time goes on it appears an american IP has committed the most attacks on this honeypot.

Included in this repo is a .gif of my admin-dashboard illustrating the attacks on my honeypot as well as the session details of the honeypot in .json format at that point in time.
