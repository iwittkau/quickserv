Quickserv 
===

Quickly serve some files.


# Install

```
go get github.com/iwittkau/quickserv/cmd/quickserv
``` 

# Run

```
quickserv [-p= port number ] [-d= file path ]
``` 

Default port is `8080` and the default path is the current working directory.


## Example 

```
quickserv -p=8081 -d=/home/user/web
``` 

Run `quickserv` on port `8081` and serve folder `/home/user/web`