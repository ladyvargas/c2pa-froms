## Install Hugo with Brew
1. Step 1: Install brew if you haven’t already
`ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`
2. Step 2: Run the brew Command to Install hugo 
`brew install hugo`
3.  brew should have updated your path to include Hugo. You can confirm by opening a new terminal window and running a few commands:
`hugo version`
`Hugo Static Site Generator v0.13 BuildDate: 2015-03-09T21:34:47-05:00`

## Build from Source on Mac
1.  Step 1: Get the Source
`git clone https://github.com/ladyvargas/c2pa-froms.git`
2. Step 2: Compiling
- Make the directory containing the source your working directory and then fetch Hugo’s dependencies:
  `mkdir -p src/github.com/gohugoio`
  `ln -sf $(pwd) src/github.com/gohugoio/hugo`
  `go get`
- Once you have properly configured your directory, you can compile Hugo using the following command:
  `go build -o hugo main.go`

## End
