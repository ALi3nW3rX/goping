# goping
Simple ping sweeper written in GO


Git Clone goping <br>
cd goping


To use this ping sweeper, compile it using the go build command and then <br>
run the resulting binary file, passing the IP address as an argument.<br> 
For example:<br>

$ go build goping.go<br>
$ ./ping_sweeper 192.168.1.0

This will generate all possible combinations of the provided IP address (e.g. 192.168.1.0, 192.168.1.255)
