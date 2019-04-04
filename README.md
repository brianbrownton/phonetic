A POSIX commandline tool to turn a string into the NATO phonetic equivalent.

Having not personally been in the military or had to do much work on radios, I find it difficult to come up with the right words to use when giving postal codes, confirmation numbers, references numbers, etc., over the phone to people.

Now I can just paste them in my terminal and know how to say them clearly and unmistakably over the phone.

👍

# Usage

```
$ phonetic qwerty123
Quebec        (KEH-BECK)
Whiskey       (WISS-KEY)
Echo          (ECK-OH)
Romeo         (ROW-ME-OH)
Tango         (TANG-GO)
Yankee        (YANG-KEY)
One           (WUN)
Two           (TOO)
Three         (TREE)
```

# Installation

On any platform you should be able to just download a the shell script, either by cloning the repo, copying the script, or downloading a tgz release. After that, just place it in your `$PATH` and everything should be groovy.

## macOS

Easier installation is available via homebrew:
```
$ brew install brianmorton/tools/phonetic
```

# Contributing
Happy to have anyone open issues or PRs.