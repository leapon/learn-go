# run go code

mbp15a:simple yliu0$ go run hello.go 
hello world


mbp15a:simple yliu0$ ll
total 16
drwxr-xr-x  4 yliu0  staff  136 May 20 19:59 .
drwxr-xr-x  7 yliu0  staff  238 May 20 19:58 ..
-rw-r--r--  1 yliu0  staff   75 May 20 19:58 hello.go
-rw-r--r--  1 yliu0  staff  336 May 20 19:59 readme.txt



mbp15a:simple yliu0$ go build hello.go 

mbp15a:simple yliu0$ ll
total 4416
drwxr-xr-x  4 yliu0  staff      136 May 20 19:58 .
drwxr-xr-x  7 yliu0  staff      238 May 20 19:58 ..
-rwxr-xr-x  1 yliu0  staff  2253776 May 20 19:58 hello
-rw-r--r--  1 yliu0  staff       75 May 20 19:58 hello.go

mbp15a:simple yliu0$ ./hello 
hello world

