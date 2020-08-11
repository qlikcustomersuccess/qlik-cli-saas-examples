# New Generic Repository

This is a repo templates that provides the basic files and config when creating a new project. 

## Example Files

__readme.md__

Simple way to document and describe a repository. GitHub automatically displays readme.md as the descriptive text on a repository page. 

* [GitHub: Mastering Markdown](https://guides.github.com/features/mastering-markdown/)
* [VS Code: Markdown](https://code.visualstudio.com/docs/languages/markdown)

__.gitignore__

Define files to be ignored from Git repository. Simple way to for example exclude secret or log files from being part of git commit. 

* [Ignoring files in the Pro Git book](https://git-scm.com/book/en/v2/Git-Basics-Recording-Changes-to-the-Repository#_ignoring)
* [.gitignore in the man pages for Git](https://git-scm.com/docs/gitignore)

__LICENSE__

License file is very important in the open source community, as it defines how a shared repository can be used by others. Default license in this template is MIT, but see below link for more alternatives. 

LICENSE file should be considered mandatory for each repository. It is also good practice to mention License reference at bottom of each readme.md, as well as in comment in each script file. 

* [Licensing a repository](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/licensing-a-repository)

## Setup repository 

* Most repositories should be public, private is also useful for internal projects
* Configure notifications so that pull requests are notified to the right sub set of people
* Invite maintainers group

## Pull request

* Good practice to enforce code review by your peers
* Configure Branch protection rule for master branch1. 

## License

This project is provided "AS IS", without any warranty, under the MIT License - see the [LICENSE](LICENSE) file for details
