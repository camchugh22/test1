Last login: Sat Feb 14 09:20:59 on ttys000
(base) cailinmchugh@Cailins-MacBook-Pro ~ % /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
==> Checking for `sudo` access (which may request your password)...
Password:
==> This script will install:
/opt/homebrew/bin/brew
/opt/homebrew/share/doc/homebrew
/opt/homebrew/share/man/man1/brew.1
/opt/homebrew/share/zsh/site-functions/_brew
/opt/homebrew/etc/bash_completion.d/brew
/opt/homebrew
/etc/paths.d/homebrew

Press RETURN/ENTER to continue or any other key to abort:
==> /usr/bin/sudo /usr/sbin/chown -R cailinmchugh:admin /opt/homebrew
==> Downloading and installing Homebrew...
==> /usr/bin/sudo /bin/mkdir -p /etc/paths.d
==> /usr/bin/sudo tee /etc/paths.d/homebrew
/opt/homebrew/bin
==> /usr/bin/sudo /usr/sbin/chown root:wheel /etc/paths.d/homebrew
==> /usr/bin/sudo /bin/chmod a+r /etc/paths.d/homebrew
==> Updating Homebrew...
Installing from the API is now the default behaviour!
You can save space and time by running:
  brew untap homebrew/core
==> Installation successful!

==> Homebrew has enabled anonymous aggregate formulae and cask analytics.
Read the analytics documentation (and how to opt-out) here:
  https://docs.brew.sh/Analytics
No analytics data has been sent yet (nor will any be during this install run).

==> Homebrew is run entirely by unpaid volunteers. Please consider donating:
  https://github.com/Homebrew/brew#donations

==> Next steps:
- Run these commands in your terminal to add Homebrew to your PATH:
    echo >> /Users/cailinmchugh/.zprofile
    echo 'eval "$(/opt/homebrew/bin/brew shellenv zsh)"' >> /Users/cailinmchugh/.zprofile
    eval "$(/opt/homebrew/bin/brew shellenv zsh)"
- Run brew help to get started
- Further documentation:
    https://docs.brew.sh

(base) cailinmchugh@Cailins-MacBook-Pro ~ % brew help
Example usage:
  brew search TEXT|/REGEX/
  brew info [FORMULA|CASK...]
  brew install FORMULA|CASK...
  brew update
  brew upgrade [FORMULA|CASK...]
  brew uninstall FORMULA|CASK...
  brew list [FORMULA|CASK...]

Troubleshooting:
  brew config
  brew doctor
  brew install --verbose --debug FORMULA|CASK

Contributing:
  brew create URL [--no-fetch]
  brew edit [FORMULA|CASK...]

Further help:
  brew commands
  brew help [COMMAND]
  man brew
  https://docs.brew.sh
(base) cailinmchugh@Cailins-MacBook-Pro ~ % echo >> /Users/cailinmchugh/.zprofile
(base) cailinmchugh@Cailins-MacBook-Pro ~ % echo 'eval "$(/opt/homebrew/bin/brew shellenv zsh)"' >> /Users/cailinmchugh/.zprofile
(base) cailinmchugh@Cailins-MacBook-Pro ~ % eval "$(/opt/homebrew/bin/brew shellenv zsh)"
(base) cailinmchugh@Cailins-MacBook-Pro ~ % brew help
Example usage:
  brew search TEXT|/REGEX/
  brew info [FORMULA|CASK...]
  brew install FORMULA|CASK...
  brew update
  brew upgrade [FORMULA|CASK...]
  brew uninstall FORMULA|CASK...
  brew list [FORMULA|CASK...]

Troubleshooting:
  brew config
  brew doctor
  brew install --verbose --debug FORMULA|CASK

Contributing:
  brew create URL [--no-fetch]
  brew edit [FORMULA|CASK...]

Further help:
  brew commands
  brew help [COMMAND]
  man brew
  https://docs.brew.sh
(base) cailinmchugh@Cailins-MacBook-Pro ~ % brew install git
==> Fetching downloads for: git
✔︎ Bottle Manifest git (2.53.0)                       Downloaded   20.9KB/ 20.9KB
✔︎ Bottle Manifest libunistring (1.4.1)               Downloaded    7.3KB/  7.3KB
✔︎ Bottle Manifest gettext (1.0)                      Downloaded   13.7KB/ 13.7KB
✔︎ Bottle Manifest pcre2 (10.47_1)                    Downloaded   11.7KB/ 11.7KB
✔︎ Bottle Manifest libiconv (1.18)                    Downloaded    7.5KB/  7.5KB
✔︎ Bottle libunistring (1.4.1)                        Downloaded    1.9MB/  1.9MB
✔︎ Bottle libiconv (1.18)                             Downloaded    1.6MB/  1.6MB
✔︎ Bottle pcre2 (10.47_1)                             Downloaded    2.4MB/  2.4MB
✔︎ Bottle gettext (1.0)                               Downloaded   10.3MB/ 10.3MB
✔︎ Bottle git (2.53.0)                                Downloaded   22.6MB/ 22.6MB
==> Installing dependencies for git: libunistring, gettext, pcre2 and libiconv
==> Installing git dependency: libunistring
==> Pouring libunistring--1.4.1.arm64_sequoia.bottle.tar.gz
🍺  /opt/homebrew/Cellar/libunistring/1.4.1: 59 files, 5.8MB
==> Installing git dependency: gettext
==> Pouring gettext--1.0.arm64_sequoia.bottle.tar.gz
🍺  /opt/homebrew/Cellar/gettext/1.0: 2,499 files, 35.4MB
==> Installing git dependency: pcre2
==> Pouring pcre2--10.47_1.arm64_sequoia.bottle.tar.gz
🍺  /opt/homebrew/Cellar/pcre2/10.47_1: 244 files, 7.3MB
==> Installing git dependency: libiconv
==> Pouring libiconv--1.18.arm64_sequoia.bottle.tar.gz
🍺  /opt/homebrew/Cellar/libiconv/1.18: 32 files, 2.9MB
==> Installing git
==> Pouring git--2.53.0.arm64_sequoia.bottle.tar.gz
==> Caveats
The Tcl/Tk GUIs (e.g. gitk, git-gui) are now in the `git-gui` formula.
Subversion interoperability (git-svn) is now in the `git-svn` formula.
==> Summary
🍺  /opt/homebrew/Cellar/git/2.53.0: 1,741 files, 62.1MB
==> Running `brew cleanup git`...
Disable this behaviour by setting `HOMEBREW_NO_INSTALL_CLEANUP=1`.
Hide these hints with `HOMEBREW_NO_ENV_HINTS=1` (see `man brew`).
==> Caveats
zsh completions and functions have been installed to:
  /opt/homebrew/share/zsh/site-functions
==> git
The Tcl/Tk GUIs (e.g. gitk, git-gui) are now in the `git-gui` formula.
Subversion interoperability (git-svn) is now in the `git-svn` formula.
(base) cailinmchugh@Cailins-MacBook-Pro ~ % git --version
git version 2.39.5 (Apple Git-154)
(base) cailinmchugh@Cailins-MacBook-Pro ~ % git config --global user.name "<Cailin McHugh>"
(base) cailinmchugh@Cailins-MacBook-Pro ~ % 
(base) cailinmchugh@Cailins-MacBook-Pro ~ % git config --global user.name "<Cailin McHugh>"
(base) cailinmchugh@Cailins-MacBook-Pro ~ % git config --global user.email"<cailin.mchugh@eastern.edu>"
error: invalid key: user.email<cailin.mchugh@eastern.edu>
(base) cailinmchugh@Cailins-MacBook-Pro ~ % git config --global user.email "<cailin.mchugh@eastern.edu>"

(base) cailinmchugh@Cailins-MacBook-Pro ~ % git init <test1>
zsh: parse error near `\n'
(base) cailinmchugh@Cailins-MacBook-Pro ~ % cd Documents
mkdir data-analytics-project
cd data-analytics-project
git init

Initialized empty Git repository in /Users/cailinmchugh/Documents/data-analytics-project/.git/
(base) cailinmchugh@Cailins-MacBook-Pro data-analytics-project % git init example
Initialized empty Git repository in /Users/cailinmchugh/Documents/data-analytics-project/example/.git/
(base) cailinmchugh@Cailins-MacBook-Pro data-analytics-project % touch readme.md
(base) cailinmchugh@Cailins-MacBook-Pro data-analytics-project % git add readme.md
(base) cailinmchugh@Cailins-MacBook-Pro data-analytics-project % git commit -m 'add readme'
[main (root-commit) ed88400] add readme
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 readme.md
(base) cailinmchugh@Cailins-MacBook-Pro data-analytics-project % git config --global core.editor "code --wait"
(base) cailinmchugh@Cailins-MacBook-Pro data-analytics-project % remote add origin https://github.com/camchugh22/test1.git
zsh: command not found: remote
(base) cailinmchugh@Cailins-MacBook-Pro data-analytics-project % git remote add origin https://github.com/camchugh22/test1.git
(base) cailinmchugh@Cailins-MacBook-Pro data-analytics-project % git push -u origin master
error: src refspec master does not match any
error: failed to push some refs to 'https://github.com/camchugh22/test1.git'
(base) cailinmchugh@Cailins-MacBook-Pro data-analytics-project % git push -u origin main
Username for 'https://github.com': camchugh22
Password for 'https://camchugh22@github.com': 
remote: Invalid username or token. Password authentication is not supported for Git operations.
fatal: Authentication failed for 'https://github.com/camchugh22/test1.git/'
(base) cailinmchugh@Cailins-MacBook-Pro data-analytics-project % git push -u origin main
Username for 'https://github.com': camchugh22
Password for 'https://camchugh22@github.com': 
remote: Invalid username or token. Password authentication is not supported for Git operations.
fatal: Authentication failed for 'https://github.com/camchugh22/test1.git/'
(base) cailinmchugh@Cailins-MacBook-Pro data-analytics-project % git push -u origin main
Username for 'https://github.com': camchugh22
Password for 'https://camchugh22@github.com': 
remote: Invalid username or token. Password authentication is not supported for Git operations.
fatal: Authentication failed for 'https://github.com/camchugh22/test1.git/'
(base) cailinmchugh@Cailins-MacBook-Pro data-analytics-project % git push -u origin main
Username for 'https://github.com': camchugh22
Password for 'https://camchugh22@github.com': 
remote: Invalid username or token. Password authentication is not supported for Git operations.
fatal: Authentication failed for 'https://github.com/camchugh22/test1.git/'
(base) cailinmchugh@Cailins-MacBook-Pro data-analytics-project % git remote -v

origin	https://github.com/camchugh22/test1.git (fetch)
origin	https://github.com/camchugh22/test1.git (push)
(base) cailinmchugh@Cailins-MacBook-Pro data-analytics-project % git credential-osxkeychain erase
host=github.com
protocol=https


git push -u origin main
bad input: git push -u origin main
(base) cailinmchugh@Cailins-MacBook-Pro data-analytics-project % 
(base) cailinmchugh@Cailins-MacBook-Pro data-analytics-project % 
git push -u origin main
Username for 'https://github.com': camchugh22
Password for 'https://camchugh22@github.com': 
remote: Invalid username or token. Password authentication is not supported for Git operations.
fatal: Authentication failed for 'https://github.com/camchugh22/test1.git/'
(base) cailinmchugh@Cailins-MacBook-Pro data-analytics-project % git remote -v

origin	https://github.com/camchugh22/test1.git (fetch)
origin	https://github.com/camchugh22/test1.git (push)
(base) cailinmchugh@Cailins-MacBook-Pro data-analytics-project % git push -u origin main
Username for 'https://github.com': camchugh22
Password for 'https://camchugh22@github.com': 
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 220 bytes | 220.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
remote: error: GH007: Your push would publish a private email address.
remote: You can make your email public or disable this protection by visiting:
remote: https://github.com/settings/emails
To https://github.com/camchugh22/test1.git
 ! [remote rejected] main -> main (push declined due to email privacy restrictions)
error: failed to push some refs to 'https://github.com/camchugh22/test1.git'
(base) cailinmchugh@Cailins-MacBook-Pro data-analytics-project % git push -u origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 220 bytes | 220.00 KiB/s, done.
