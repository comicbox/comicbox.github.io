---
question: How do I install ComicBox from source?
index: 2
---

If you are on a system that isn't officially supported you can always install from source.
It should work on anything platform that [go supports](https://github.com/golang/go/wiki/MinimumRequirements).
To install it you will need [go](https://golang.org/doc/install#install) 1.11+, [node + npm](https://nodejs.org/en/) 10+, gcc, and make.
1. Install go bindata with `go get github.com/zwzn/go-bindata/go-bindata`
1. Clone the repository with `git clone https://github.com/comicbox/comicbox.git`
1. Download the dependencies with `make get`
1. Build the project with `make`

Now you can run the server in the at `./bin/comicboxd` or `./bin/comicboxd.exe`