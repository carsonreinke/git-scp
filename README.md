# git-scp
Secure copy your changes

## Installation

```
git clone git@github.com:carsonreinke/git-scp.git
cp git-scp /usr/local/bin
```

## Usage

```
git scp <username@hostname> <target-dir> N
git scp <username@hostname> <target-dir> origin
git scp <username@hostname> <target-dir> status
```

##Examples

Replace N with a number `git scp deploy@myhost.com /home/www/ 5` will use a git log of `HEAD~5..HEAD` and deploy the modifications to the target

Using `origin` will specify `origin..HEAD`.

Using `status` will specificy current `git status`





After several Gist versions going, finally decided to just put this in a repo, thanks @codeaid:
* https://gist.github.com/codeaid/5a97956bb0bacd6a38d5
* https://gist.github.com/carsonreinke/3c42730a80dba02e7940d38b193c791e
* https://gist.github.com/sgorman/9054fce3dd78908cfacfcb25ef0a53d0
