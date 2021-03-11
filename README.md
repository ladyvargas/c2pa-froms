## Install Hugo with Brew
1. Step 1: Install brew if you haven’t already
`ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`
2. Step 2: Run the brew Command to Install hugo 
`brew install hugo`
3.  brew should have updated your path to include Hugo. You can confirm by opening a new terminal window and running a few commands:
`hugo version`
`Hugo Static Site Generator v0.13 BuildDate: 2015-03-09T21:34:47-05:00`

## Build from Source on Mac
1. Step 1: Intall Hugo


2.  Step 1: Get the Source
`git clone https://github.com/ladyvargas/c2pa-froms.git`


3. Step 3: Compiling
- Make the directory containing the source your working directory and then fetch Hugo’s dependencies
`hugo server --watch --buildDrafts --verbose`

4. Step 4: Open your browser
- Now, open up your browser and point it to the Web Server URL listed in the output. (It is usually http://localhost:1313.)

## Execute Via Docker
`./hugo-build.sh`
`./hugo-serve.sh` 
It didn't work, so I had to do:
`git submodule init` 
`git submodule update`
Then again:
`./hugo-build.sh`
`./hugo-serve.sh `

## End
