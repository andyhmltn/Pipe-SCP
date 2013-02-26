Pipe-SCP
=============

This is a really simple bash script for using `scp` in conjunction with pipes.

How do I use it?
----------------
Move it into a directory in your `$PATH` (or not if you prefer, but you'll have to reference it with the full path.) Then use like so:

	echo 'Hello world!' | pscp myserver:mydirectory/outputfile

You will need to specify a filename (in this case `outputfile`) or it'll be left as `pscp.tmp`
