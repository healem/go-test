## To build

sudo docker run --rm -v ~/projects/go-test:/go -w /go golang:1.10 go install -v proj

## To run

sudo docker run -it -d --rm --name proj --net=host -v ~/projects/go-test:/go -w /go golang:1.10 proj

## To test

curl "http://localhost:18770/get?name=mike"

>Hello, "mike"

>You lucky number is: 4

