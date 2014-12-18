# Mi24 - File Corpses Finder

*Dieses Tool soll für den bisherigen Video Storage im Abgleich mit der FileLocation-Tabelle Dateileichen finden. Das Tool sollte in GO geschrieben werden, einfach um eine neue Sprache zu finden.
Der Output sollte die Dateien erfassen die nicht in der Tabelle vorliegen.*

![go go go](http://cdn.ientry.com/sites/webpronews/pictures/gogopher_320x245.jpg "joana looks like a pony ... sometimes")

## Development

Just checkout the repository, run `vagrant up` and go into the vm via `vagrant ssh`.
Inside the vm just go into the directory `share`.

    vagrant up
    vagrant ssh
    
    cd share
    
### Build

There is a shortcut for build job. Use `./build` ...

    core@vm-01 ~/share $ ./build 

### Run

The executable will be placed in director `bin` and will called `file-corpses-finder`.

    core@vm-01 ~/share $ bin/file-corpses-finder 
    
## Useful stuff

* [golang homepage](http://golang.org/) checkout the Tour!
* [basics for coding/testing](https://golang.org/doc/code.html)
* [testing: lib for assertations](https://github.com/stretchr/testify)