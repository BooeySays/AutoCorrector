# AutoCorrector

v0.1
	- Just created dir
	- idea: script will create an alias for a typo and
		point it to the intended command
	- typos to be autocorrected will be stored in a file
		- one line per
	- alias will be loaded via
		for i in $(\cat file); do
			alias "$i"='command'
		done

