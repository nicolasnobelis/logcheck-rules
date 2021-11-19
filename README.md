Some ignore rules for pihole on RaspberryOS


The rules assume a hostname of `raspberrypi`. You may want to change that.

Put them in /etc/logcheck/ignore.d.XXX where XXX is
the verbosity set in Logcheck.
Then link them to /etc/logcheck/violations.ignore.d.
Credit to [1] for the hint.




[1]: http://www.agentbob.info/agentbob/g3/83-AB.html
