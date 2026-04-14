Natas 9
===============

solution
---------------
t7I5VHvpa14sJTUGV0cbEsbYfFP2dmOu

exploit
---------------
Read the sourcecode and see it puts user input into a bash command. So we can command line inject with `;` and run linux commands.
Then just `cat` the flag file in the `/etc/natas_webpass/` folder.
