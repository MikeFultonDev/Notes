To create a 'typical' developer ID:
tsocmd "permit \<acct-num> class(ACCTNUM) id(\<userid>)"
mkdir /u/\<userid>

ADDUSER \<userid> NAME(\<name>) OMVS(AUTOUID HOME(''/u/\<userid>'') PROGRAM(''/bin/sh")) TSO(ACCTNUM(\<acct-num>) PROC(\<proc>)  COMMAND(ISPF)) DFLTGRP(\<group-name>)

(https://tech.mikefulton.ca/ADDUSERSyntax)


References:
[[Determine what groups a user belongs to]]