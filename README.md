# Recon Mindmap
## How to use
Run ./recon.sh
## Install needed tools
- wget https://golang.org/dl/go1.15.6.linux-amd64.tar.gz | tar -xvf go1.15.6.linux-amd64.tar.gz -C /usr/local
- chown -R root:root /usr/local/go
- go get -u github.com/tomnomnom/assetfinder
- export GO111MODULE=on
- go get -v github.com/OWASP/Amass/v3/...
- go get -u github.com/sensepost/gowitness
- go get github.com/tomnomnom/waybackurls
- go get github.com/haccer/subjack
### Edit .profile and add 2 these lines
- export PATH=$PATH:/usr/local/go/bin
- export PATH=$PATH:/root/go/bin
