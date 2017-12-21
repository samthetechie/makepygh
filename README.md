# README Boilerplate

A template of README best practices to make your README simple to understand and easy to use.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Support](#support)
- [Contributing](#contributing)

## Installation

1. install virtualenv
2. install virtualenvwrapper
3. create an authentication token via https://github.com/settings/tokens
Generate Access Token -> enter it in below in place of <token>
4. Have a look at [This Gist](https://gist.github.com/samthetechie/b9591482cec7abe3118f837def030a64) for my ~/.bashrc functions for creating and deleting github repos.
5. Copy the above ~/.bashrc snippets to the bottom of ~/.bashrc, and reload bash with source ~/.bash_profile:

```sh
git config --global github.token <token>
git config --global github.user <username>'
```

## Usage

Replace the contents of `README.md` with your project's:

- Name
- Description
- Installation instructions
- Usage instructions
- Support instructions
- Contributing instructions

Feel free to remove any sections that aren't applicable to your project.

## Support

Please [open an issue](https://github.com/fraction/readme-boilerplate/issues/new) for support.

## Contributing

Please contribute using [Github Flow](https://guides.github.com/introduction/flow/). Create a branch, add commits, and [open a pull request](https://github.com/fraction/readme-boilerplate/compare/).
