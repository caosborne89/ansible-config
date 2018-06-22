# ualibraries/ansible-config

*WORK IN PROGRESS*

Mike Simpson is to blame for this.

Some day, this will hopefully expand to control some non-trivial proportion of our
inventory and service offerings; starting out small by self-managing the ansible1
control host and (maybe) the OpenAZ service hosts.

Once this stabilizes, you would expect to find the master branch checked out into
ansible1.library.arizona.edu:/etc/ansible; for now, I've got the "initial_pass"
feature branch checked out on that host instead -- so I'm doing development in 
Eclipse et al. on my laptop in the feature branch, pushing it up to Github, then
pulling it down to ansible1 to test.

Yes, non-local feature branches are usually a really bad idea. :)

-mgs, 6/7/2018
