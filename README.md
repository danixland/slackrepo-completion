# SlackRepo Bash Completion

Bash completion file for [Slackrepo](http://idlemoor.github.io/slackrepo/index.html)

## Getting Started

Just copy this file to /etc/bash_completion.d and then run
```
source /etc/bash_completion.d/slackrepo
```

### Prerequisites

You need to have bash-completion and of course slackrepo

### Installing

If you want bash completion to be sourced everytime you run a shell add this at the beginning of your .bashrc file:
```
# turns on bash autocompletion
if [ -f /etc/profile.d/bash_completion.sh ]; then
 . /etc/profile.d/bash_completion.sh
fi
```

## Inspired by

The bash completion file for slackpkg

## Contributing

Feel free to open issues and contribute however you feel like, I know the code isn't perfect.

## Author

* **Danilo 'danix' Macrì** - *Initial work* - [danix.xyz](https://danix.xyz)

## License

This project is licensed under the GPLv3 License - see the [LICENSE.md](LICENSE.md) file for details
