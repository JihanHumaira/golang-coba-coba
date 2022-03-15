# cara-instal-golang
1. cd ~
2. curl -OL https://golang.org/dl/go1.16.7.linux-amd64.tar.gz
3. sha256sum go1.16.7.linux-amd64.tar.gz

Output
go1.16.7.linux-amd64.tar.gz
7fe7a73f55ba3e2285da36f8b085e5c0159e9564ef5f63ee0ed6b818ade8ef04  go1.16.7.linux-amd64.tar.gz

4. sudo tar -C /usr/local -xvf go1.16.7.linux-amd64.tar.gz
5. sudo nano ~/.profile

Then, add the following information to the end of your file:
6. export PATH=$PATH:/usr/local/go/bin

7. source ~/.profile

8. go version

9. go version go1.16.7 linux/amd64

Cara Buka Golang:
1. go run main.go

Buka postman
2. curl localhost:8080/staging



