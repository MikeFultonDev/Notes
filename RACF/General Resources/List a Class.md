Use SEARCH to search the RACF database, e.g.
tsocmd "SEARCH CLASS(\<class-name>) [GENERIC|NOGENERIC|__ALL__]"
(https://tech.mikefulton.ca/SEARCHSyntax)

Alternately:
RLIST \<class-name> \<profile-name> \[GENERIC|NOGENERIC]
	
To list all the generic profiles in a particular \<class-name>

tsocmd "RLIST \<class-name> * GENERIC" | grep '\<class-name>'

(https://tech.mikefulton.ca/RLISTSyntax)

Related:
	[[Delete a profile]]
	[[Define a profile]]
	[[Class Refresh]]