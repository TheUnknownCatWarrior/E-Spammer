# E-Spammer
# Note that if the script wont stop hold down F

msgBox, C to start, F to stop and R to exit.
looping := true
c::
	looping := true
	while(looping = true)
	{
		send, e
	}
return
f::
	looping := false
return
r::
	exitApp
return
