# go_hello - Create your first go app
##### simple hello world app in go language.

Hey Mates! I am Deepanshu Narang, a Tech Learner. Today I am starting my journey to learn the GoLang. I thought, why learn alone when I have amazing people like you who would love to join with me and learn this together. From today I will be posting a story every day of what I have learned. So that you can come here and follow along with me. If this sounds interesting, then subscribe me and turn on the notifications.

## what is Golang?

* Golang(or just Go), is a statically typed, compiled programming language designed at Google by Robert Griesemer, Rob Pike, and Ken Thompson.

* You will find Golang similar to the C language. But it comes with memory safety, garbage collection, structural typing, and CSP-style concurrency.

* You don’t need to worry about any of the features of the Golang but you just need to get started with it first. Let’s start with Installing the Golang:

## Installing Golang

Follow these steps for Linux and mac versions:
1. Go the downloads page of the official Golang website.
1. Download the suitable version for your OS.(for me it is Linux, If you are a windows user you just need to follow the prompts.)

(steps from here are just for Linux and mac users)

3. You need to extract the downloaded archive to /usr/local

eg:
`tar -C /usr/local -xzf go1.13.4.linux-amd64.tar.gz`

note: you need to make sure that the name of the file(that ends with tar.gz) matches with the name of file that you have downloaded for your system.

4. Add /usr/local/go/bin to the PATH environment variable. You can do this by adding this line to your /etc/profile (for a system-wide installation) or $HOME/.profile:

eg:
`export PATH=$PATH:/usr/local/go/bin`

## Hello World Program in Golang

Let’s make a Hello World Program to check if Golang is installed properly in our environment.

1. Create a directory named ‘hello’ on Desktop.

1. Fire up your Terminal and change the directory to the newly created Directory:
`cd $HOME/Desktop/hello/`

1. Now create a file named ‘hello.go’ using your favorite Text Editor inside the current directory.(here I am using vs code)
`code hello.go`
`hello.go`

1. Now type or paste the following program in your text editor:

`package main
import “fmt”
func main() {
fmt.Printf(“hello, world\n”)
}`

Right Now you don’t need to understand this code. Just save the file and compile the program using following command in the terminal:

`go build`

If no errors appear, your program is compiled successfully!

You will notice that a new file named ‘hello’ is created. This is the compiled and executable version of the program.

To run this file, just type:
`./hello`

and hit return key.

If you get an output with Hello, World. Then cheers! You have successfully executed your first program in Golang. Also you have passed the most difficult step of learning: Installation and Getting started.
