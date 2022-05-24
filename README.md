# CWP - CentOS Web Panel Git Deploy

## Description

Example how to deploy to CWP and keep updated on push / pull requests 

## Getting Started - Ensure Git is installed and up to date

### Dependencies

* Make sure you have git installed and updated on your machine 
* an account with root privileges 
* Copy the link of the version that we want to install. For that go to this website.
[GIT](https://twitter.com/dompizzie)

Check for updates of os
```
yum -y update
```
You can check whether Git is installed and what version you are using by typing the following command: git --version
```
git --version
```

if not installed and you need to upgrade from version 1.* to 2 use
```
yum remove git
```
Then
```
yum -y install https://packages.endpointdev.com/rhel/7/os/x86_64/endpoint-repo.x86_64.rpm
```

check version by: 

```
git --version
```

Upgrading 
You can use yum upgrade git if you already have it installed, but yum install git works in either case.




### Installing

* How/where to download your program
* Any modifications needed to be made to files/folders

### Executing program

* How to run the program
* Step-by-step bullets
```
code blocks for commands
```

## Help

Any advise for common problems or issues.
```
command to run if program contains helper info
```

## Authors

Contributors names and contact info

ex. Dominique Pizzie  
ex. [@DomPizzie](https://twitter.com/dompizzie)

## Version History

* 0.2
    * Various bug fixes and optimizations
    * See [commit change]() or See [release history]()
* 0.1
    * Initial Release

## License

This project is licensed under the [NAME HERE] License - see the LICENSE.md file for details

## Acknowledgments

Inspiration, code snippets, etc.
* [awesome-readme](https://github.com/matiassingers/awesome-readme)
* [PurpleBooth](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2)
* [dbader](https://github.com/dbader/readme-template)
* [zenorocha](https://gist.github.com/zenorocha/4526327)
* [fvcproductions](https://gist.github.com/fvcproductions/1bfc2d4aecb01a834b46)