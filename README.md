# random-cowsay

Print a random message using cowsay, fortune, artii, and lolcat. If no startup mesasge is provided, then "Welcome" will be emitted instead.

## Terminal Headers

Add this line to the bottom of your terminal startup script in order to run a random cowsay fortune whenever the terminal is opened.

## Examples

```bash
sh random-cowsay/cowscript.sh
```

```bash
sh random-cowsay/cowscript.sh "Hello Dhruval"
```

```bash
sh random-cowsay/cowscript.sh "Hello Dhruval" "Some Custom Message"
```

Note: The below example uses the [chucknorris](https://github.com/robbyrussell/oh-my-zsh/tree/master/plugins/chucknorris) plugin for [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh).

```bash
sh random-cowsay/cowscript.sh "Hello Dhruval" "$(chuck)"
```

## Notes

When adding the script to a terminal, make sure to replace the cowsay script with the relative path to the script.
