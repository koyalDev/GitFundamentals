1. Install Homebrew:

```shell
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

2. Custom setup the Bash profile:

```shell
git clone https://github.com/supertopher/dotfiles.git
cd dotfiles
./install
```

3.Configure Git:

```shell
git config --global user.name "John Doe"
git config --global user.email johndoe@example.com
```

4. Setup Sublime as Global editor:

```shell
git config --global core.editor "subl -w"
```

5. Install Git:

```shell
brew install git
```
This installs git and autocompletion for git.

6.Configure custom Git commands:

```shell
git congif --global alisa.lga "log --graph --oneline --all --decorate"
```
