---
title: "ページの作成方法"
date: 2023-04-18T16:35:48+09:00
draft: false
---

brew インストール
brewでhugoをインストール
テーマをインストール
<!--more-->
shoko@lupin ~ % /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
==> Checking for `sudo` access (which may request your password)...
Password:
==> You are using macOS 10.15.
==> We (and Apple) do not provide support for this old version.
This installation may not succeed.
After installation, you will encounter build failures with some formulae.
Please create pull requests instead of asking for help on Homebrew's GitHub,
Twitter or any other official channels. You are responsible for resolving any
issues you experience while you are running this old version.

==> This script will install:
/usr/local/bin/brew
/usr/local/share/doc/homebrew
/usr/local/share/man/man1/brew.1
/usr/local/share/zsh/site-functions/_brew
/usr/local/etc/bash_completion.d/brew
/usr/local/Homebrew

Press RETURN/ENTER to continue or any other key to abort:
==> /usr/bin/sudo /usr/sbin/chown -R shoko:admin /usr/local/Homebrew
==> Downloading and installing Homebrew...
remote: Enumerating objects: 237282, done.
remote: Counting objects: 100% (433/433), done.
remote: Compressing objects: 100% (280/280), done.
remote: Total 237282 (delta 174), reused 377 (delta 145), pack-reused 236849
Receiving objects: 100% (237282/237282), 69.22 MiB | 22.59 MiB/s, done.
Resolving deltas: 100% (173811/173811), done.
From https://github.com/Homebrew/brew
 * [new branch]      dependabot/bundler/Library/Homebrew/rubocop-rails-2.19.1 -> origin/dependabot/bundler/Library/Homebrew/rubocop-rails-2.19.1
 * [new branch]      master     -> origin/master
 * [new tag]             0.1        -> 0.1
 * [new tag]             0.2        -> 0.2
 * [new tag]             0.3        -> 0.3
 * [new tag]             0.4        -> 0.4
 * [new tag]             0.5        -> 0.5
 * [new tag]             0.6        -> 0.6
 * [new tag]             0.7        -> 0.7
 * [new tag]             0.7.1      -> 0.7.1
 * [new tag]             0.8        -> 0.8
 * [new tag]             0.8.1      -> 0.8.1
 * [new tag]             0.9        -> 0.9
 * [new tag]             0.9.1      -> 0.9.1
 * [new tag]             0.9.2      -> 0.9.2
 * [new tag]             0.9.3      -> 0.9.3
 * [new tag]             0.9.4      -> 0.9.4
 * [new tag]             0.9.5      -> 0.9.5
 * [new tag]             0.9.8      -> 0.9.8
 * [new tag]             0.9.9      -> 0.9.9
 * [new tag]             1.0.0      -> 1.0.0
 * [new tag]             1.0.1      -> 1.0.1
 * [new tag]             1.0.2      -> 1.0.2
 * [new tag]             1.0.3      -> 1.0.3
 * [new tag]             1.0.4      -> 1.0.4
 * [new tag]             1.0.5      -> 1.0.5
 * [new tag]             1.0.6      -> 1.0.6
 * [new tag]             1.0.7      -> 1.0.7
 * [new tag]             1.0.8      -> 1.0.8
 * [new tag]             1.0.9      -> 1.0.9
 * [new tag]             1.1.0      -> 1.1.0
 * [new tag]             1.1.1      -> 1.1.1
 * [new tag]             1.1.10     -> 1.1.10
 * [new tag]             1.1.11     -> 1.1.11
 * [new tag]             1.1.12     -> 1.1.12
 * [new tag]             1.1.13     -> 1.1.13
 * [new tag]             1.1.2      -> 1.1.2
 * [new tag]             1.1.3      -> 1.1.3
 * [new tag]             1.1.4      -> 1.1.4
 * [new tag]             1.1.5      -> 1.1.5
 * [new tag]             1.1.6      -> 1.1.6
 * [new tag]             1.1.7      -> 1.1.7
 * [new tag]             1.1.8      -> 1.1.8
 * [new tag]             1.1.9      -> 1.1.9
 * [new tag]             1.2.0      -> 1.2.0
 * [new tag]             1.2.1      -> 1.2.1
 * [new tag]             1.2.2      -> 1.2.2
 * [new tag]             1.2.3      -> 1.2.3
 * [new tag]             1.2.4      -> 1.2.4
 * [new tag]             1.2.5      -> 1.2.5
 * [new tag]             1.2.6      -> 1.2.6
 * [new tag]             1.3.0      -> 1.3.0
 * [new tag]             1.3.1      -> 1.3.1
 * [new tag]             1.3.2      -> 1.3.2
 * [new tag]             1.3.3      -> 1.3.3
 * [new tag]             1.3.4      -> 1.3.4
 * [new tag]             1.3.5      -> 1.3.5
 * [new tag]             1.3.6      -> 1.3.6
 * [new tag]             1.3.7      -> 1.3.7
 * [new tag]             1.3.8      -> 1.3.8
 * [new tag]             1.3.9      -> 1.3.9
 * [new tag]             1.4.0      -> 1.4.0
 * [new tag]             1.4.1      -> 1.4.1
 * [new tag]             1.4.2      -> 1.4.2
 * [new tag]             1.4.3      -> 1.4.3
 * [new tag]             1.5.0      -> 1.5.0
 * [new tag]             1.5.1      -> 1.5.1
 * [new tag]             1.5.10     -> 1.5.10
 * [new tag]             1.5.11     -> 1.5.11
 * [new tag]             1.5.12     -> 1.5.12
 * [new tag]             1.5.13     -> 1.5.13
 * [new tag]             1.5.14     -> 1.5.14
 * [new tag]             1.5.2      -> 1.5.2
 * [new tag]             1.5.3      -> 1.5.3
 * [new tag]             1.5.4      -> 1.5.4
 * [new tag]             1.5.5      -> 1.5.5
 * [new tag]             1.5.6      -> 1.5.6
 * [new tag]             1.5.7      -> 1.5.7
 * [new tag]             1.5.8      -> 1.5.8
 * [new tag]             1.5.9      -> 1.5.9
 * [new tag]             1.6.0      -> 1.6.0
 * [new tag]             1.6.1      -> 1.6.1
 * [new tag]             1.6.10     -> 1.6.10
 * [new tag]             1.6.11     -> 1.6.11
 * [new tag]             1.6.12     -> 1.6.12
 * [new tag]             1.6.13     -> 1.6.13
 * [new tag]             1.6.14     -> 1.6.14
 * [new tag]             1.6.15     -> 1.6.15
 * [new tag]             1.6.16     -> 1.6.16
 * [new tag]             1.6.17     -> 1.6.17
 * [new tag]             1.6.2      -> 1.6.2
 * [new tag]             1.6.3      -> 1.6.3
 * [new tag]             1.6.4      -> 1.6.4
 * [new tag]             1.6.5      -> 1.6.5
 * [new tag]             1.6.6      -> 1.6.6
 * [new tag]             1.6.7      -> 1.6.7
 * [new tag]             1.6.8      -> 1.6.8
 * [new tag]             1.6.9      -> 1.6.9
 * [new tag]             1.7.0      -> 1.7.0
 * [new tag]             1.7.1      -> 1.7.1
 * [new tag]             1.7.2      -> 1.7.2
 * [new tag]             1.7.3      -> 1.7.3
 * [new tag]             1.7.4      -> 1.7.4
 * [new tag]             1.7.5      -> 1.7.5
 * [new tag]             1.7.6      -> 1.7.6
 * [new tag]             1.7.7      -> 1.7.7
 * [new tag]             1.8.0      -> 1.8.0
 * [new tag]             1.8.1      -> 1.8.1
 * [new tag]             1.8.2      -> 1.8.2
 * [new tag]             1.8.3      -> 1.8.3
 * [new tag]             1.8.4      -> 1.8.4
 * [new tag]             1.8.5      -> 1.8.5
 * [new tag]             1.8.6      -> 1.8.6
 * [new tag]             1.9.0      -> 1.9.0
 * [new tag]             1.9.1      -> 1.9.1
 * [new tag]             1.9.2      -> 1.9.2
 * [new tag]             1.9.3      -> 1.9.3
 * [new tag]             2.0.0      -> 2.0.0
 * [new tag]             2.0.1      -> 2.0.1
 * [new tag]             2.0.2      -> 2.0.2
 * [new tag]             2.0.3      -> 2.0.3
 * [new tag]             2.0.4      -> 2.0.4
 * [new tag]             2.0.5      -> 2.0.5
 * [new tag]             2.0.6      -> 2.0.6
 * [new tag]             2.1.0      -> 2.1.0
 * [new tag]             2.1.1      -> 2.1.1
 * [new tag]             2.1.10     -> 2.1.10
 * [new tag]             2.1.11     -> 2.1.11
 * [new tag]             2.1.12     -> 2.1.12
 * [new tag]             2.1.13     -> 2.1.13
 * [new tag]             2.1.14     -> 2.1.14
 * [new tag]             2.1.15     -> 2.1.15
 * [new tag]             2.1.16     -> 2.1.16
 * [new tag]             2.1.2      -> 2.1.2
 * [new tag]             2.1.3      -> 2.1.3
 * [new tag]             2.1.4      -> 2.1.4
 * [new tag]             2.1.5      -> 2.1.5
 * [new tag]             2.1.6      -> 2.1.6
 * [new tag]             2.1.7      -> 2.1.7
 * [new tag]             2.1.8      -> 2.1.8
 * [new tag]             2.1.9      -> 2.1.9
 * [new tag]             2.2.0      -> 2.2.0
 * [new tag]             2.2.1      -> 2.2.1
 * [new tag]             2.2.10     -> 2.2.10
 * [new tag]             2.2.11     -> 2.2.11
 * [new tag]             2.2.12     -> 2.2.12
 * [new tag]             2.2.13     -> 2.2.13
 * [new tag]             2.2.14     -> 2.2.14
 * [new tag]             2.2.15     -> 2.2.15
 * [new tag]             2.2.16     -> 2.2.16
 * [new tag]             2.2.17     -> 2.2.17
 * [new tag]             2.2.2      -> 2.2.2
 * [new tag]             2.2.3      -> 2.2.3
 * [new tag]             2.2.4      -> 2.2.4
 * [new tag]             2.2.5      -> 2.2.5
 * [new tag]             2.2.6      -> 2.2.6
 * [new tag]             2.2.7      -> 2.2.7
 * [new tag]             2.2.8      -> 2.2.8
 * [new tag]             2.2.9      -> 2.2.9
 * [new tag]             2.3.0      -> 2.3.0
 * [new tag]             2.4.0      -> 2.4.0
 * [new tag]             2.4.1      -> 2.4.1
 * [new tag]             2.4.10     -> 2.4.10
 * [new tag]             2.4.11     -> 2.4.11
 * [new tag]             2.4.12     -> 2.4.12
 * [new tag]             2.4.13     -> 2.4.13
 * [new tag]             2.4.14     -> 2.4.14
 * [new tag]             2.4.15     -> 2.4.15
 * [new tag]             2.4.16     -> 2.4.16
 * [new tag]             2.4.2      -> 2.4.2
 * [new tag]             2.4.3      -> 2.4.3
 * [new tag]             2.4.4      -> 2.4.4
 * [new tag]             2.4.5      -> 2.4.5
 * [new tag]             2.4.6      -> 2.4.6
 * [new tag]             2.4.7      -> 2.4.7
 * [new tag]             2.4.8      -> 2.4.8
 * [new tag]             2.4.9      -> 2.4.9
 * [new tag]             2.5.0      -> 2.5.0
 * [new tag]             2.5.1      -> 2.5.1
 * [new tag]             2.5.10     -> 2.5.10
 * [new tag]             2.5.11     -> 2.5.11
 * [new tag]             2.5.12     -> 2.5.12
 * [new tag]             2.5.2      -> 2.5.2
 * [new tag]             2.5.3      -> 2.5.3
 * [new tag]             2.5.4      -> 2.5.4
 * [new tag]             2.5.5      -> 2.5.5
 * [new tag]             2.5.6      -> 2.5.6
 * [new tag]             2.5.7      -> 2.5.7
 * [new tag]             2.5.8      -> 2.5.8
 * [new tag]             2.5.9      -> 2.5.9
 * [new tag]             2.6.0      -> 2.6.0
 * [new tag]             2.6.1      -> 2.6.1
 * [new tag]             2.6.2      -> 2.6.2
 * [new tag]             2.7.0      -> 2.7.0
 * [new tag]             2.7.1      -> 2.7.1
 * [new tag]             2.7.2      -> 2.7.2
 * [new tag]             2.7.3      -> 2.7.3
 * [new tag]             2.7.4      -> 2.7.4
 * [new tag]             2.7.5      -> 2.7.5
 * [new tag]             2.7.6      -> 2.7.6
 * [new tag]             2.7.7      -> 2.7.7
 * [new tag]             3.0.0      -> 3.0.0
 * [new tag]             3.0.1      -> 3.0.1
 * [new tag]             3.0.10     -> 3.0.10
 * [new tag]             3.0.11     -> 3.0.11
 * [new tag]             3.0.2      -> 3.0.2
 * [new tag]             3.0.3      -> 3.0.3
 * [new tag]             3.0.4      -> 3.0.4
 * [new tag]             3.0.5      -> 3.0.5
 * [new tag]             3.0.6      -> 3.0.6
 * [new tag]             3.0.7      -> 3.0.7
 * [new tag]             3.0.8      -> 3.0.8
 * [new tag]             3.0.9      -> 3.0.9
 * [new tag]             3.1.0      -> 3.1.0
 * [new tag]             3.1.1      -> 3.1.1
 * [new tag]             3.1.10     -> 3.1.10
 * [new tag]             3.1.11     -> 3.1.11
 * [new tag]             3.1.12     -> 3.1.12
 * [new tag]             3.1.2      -> 3.1.2
 * [new tag]             3.1.3      -> 3.1.3
 * [new tag]             3.1.4      -> 3.1.4
 * [new tag]             3.1.5      -> 3.1.5
 * [new tag]             3.1.6      -> 3.1.6
 * [new tag]             3.1.7      -> 3.1.7
 * [new tag]             3.1.8      -> 3.1.8
 * [new tag]             3.1.9      -> 3.1.9
 * [new tag]             3.2.0      -> 3.2.0
 * [new tag]             3.2.1      -> 3.2.1
 * [new tag]             3.2.10     -> 3.2.10
 * [new tag]             3.2.11     -> 3.2.11
 * [new tag]             3.2.12     -> 3.2.12
 * [new tag]             3.2.13     -> 3.2.13
 * [new tag]             3.2.14     -> 3.2.14
 * [new tag]             3.2.15     -> 3.2.15
 * [new tag]             3.2.16     -> 3.2.16
 * [new tag]             3.2.17     -> 3.2.17
 * [new tag]             3.2.2      -> 3.2.2
 * [new tag]             3.2.3      -> 3.2.3
 * [new tag]             3.2.4      -> 3.2.4
 * [new tag]             3.2.5      -> 3.2.5
 * [new tag]             3.2.6      -> 3.2.6
 * [new tag]             3.2.7      -> 3.2.7
 * [new tag]             3.2.8      -> 3.2.8
 * [new tag]             3.2.9      -> 3.2.9
 * [new tag]             3.3.0      -> 3.3.0
 * [new tag]             3.3.1      -> 3.3.1
 * [new tag]             3.3.10     -> 3.3.10
 * [new tag]             3.3.11     -> 3.3.11
 * [new tag]             3.3.12     -> 3.3.12
 * [new tag]             3.3.13     -> 3.3.13
 * [new tag]             3.3.14     -> 3.3.14
 * [new tag]             3.3.15     -> 3.3.15
 * [new tag]             3.3.16     -> 3.3.16
 * [new tag]             3.3.2      -> 3.3.2
 * [new tag]             3.3.3      -> 3.3.3
 * [new tag]             3.3.4      -> 3.3.4
 * [new tag]             3.3.5      -> 3.3.5
 * [new tag]             3.3.6      -> 3.3.6
 * [new tag]             3.3.7      -> 3.3.7
 * [new tag]             3.3.8      -> 3.3.8
 * [new tag]             3.3.9      -> 3.3.9
 * [new tag]             3.4.0      -> 3.4.0
 * [new tag]             3.4.1      -> 3.4.1
 * [new tag]             3.4.10     -> 3.4.10
 * [new tag]             3.4.11     -> 3.4.11
 * [new tag]             3.4.2      -> 3.4.2
 * [new tag]             3.4.3      -> 3.4.3
 * [new tag]             3.4.4      -> 3.4.4
 * [new tag]             3.4.5      -> 3.4.5
 * [new tag]             3.4.6      -> 3.4.6
 * [new tag]             3.4.7      -> 3.4.7
 * [new tag]             3.4.8      -> 3.4.8
 * [new tag]             3.4.9      -> 3.4.9
 * [new tag]             3.5.0      -> 3.5.0
 * [new tag]             3.5.1      -> 3.5.1
 * [new tag]             3.5.10     -> 3.5.10
 * [new tag]             3.5.2      -> 3.5.2
 * [new tag]             3.5.3      -> 3.5.3
 * [new tag]             3.5.4      -> 3.5.4
 * [new tag]             3.5.5      -> 3.5.5
 * [new tag]             3.5.6      -> 3.5.6
 * [new tag]             3.5.7      -> 3.5.7
 * [new tag]             3.5.8      -> 3.5.8
 * [new tag]             3.5.9      -> 3.5.9
 * [new tag]             3.6.0      -> 3.6.0
 * [new tag]             3.6.1      -> 3.6.1
 * [new tag]             3.6.10     -> 3.6.10
 * [new tag]             3.6.11     -> 3.6.11
 * [new tag]             3.6.12     -> 3.6.12
 * [new tag]             3.6.13     -> 3.6.13
 * [new tag]             3.6.14     -> 3.6.14
 * [new tag]             3.6.15     -> 3.6.15
 * [new tag]             3.6.16     -> 3.6.16
 * [new tag]             3.6.17     -> 3.6.17
 * [new tag]             3.6.18     -> 3.6.18
 * [new tag]             3.6.19     -> 3.6.19
 * [new tag]             3.6.2      -> 3.6.2
 * [new tag]             3.6.20     -> 3.6.20
 * [new tag]             3.6.21     -> 3.6.21
 * [new tag]             3.6.3      -> 3.6.3
 * [new tag]             3.6.4      -> 3.6.4
 * [new tag]             3.6.5      -> 3.6.5
 * [new tag]             3.6.6      -> 3.6.6
 * [new tag]             3.6.7      -> 3.6.7
 * [new tag]             3.6.8      -> 3.6.8
 * [new tag]             3.6.9      -> 3.6.9
 * [new tag]             4.0.0      -> 4.0.0
 * [new tag]             4.0.1      -> 4.0.1
 * [new tag]             4.0.10     -> 4.0.10
 * [new tag]             4.0.11     -> 4.0.11
 * [new tag]             4.0.12     -> 4.0.12
 * [new tag]             4.0.13     -> 4.0.13
 * [new tag]             4.0.14     -> 4.0.14
 * [new tag]             4.0.2      -> 4.0.2
 * [new tag]             4.0.3      -> 4.0.3
 * [new tag]             4.0.4      -> 4.0.4
 * [new tag]             4.0.5      -> 4.0.5
 * [new tag]             4.0.6      -> 4.0.6
 * [new tag]             4.0.7      -> 4.0.7
 * [new tag]             4.0.8      -> 4.0.8
 * [new tag]             4.0.9      -> 4.0.9
HEAD is now at cf2539718 Merge pull request #15251 from Homebrew/dependabot/bundler/Library/Homebrew/regexp_parser-2.8.0
==> Downloading https://ghcr.io/v2/homebrew/portable-ruby/portable-ruby/blobs/sha256:61029cec31c68a1fae1fa90fa876adf43d0becff777da793f9b5c5577f00567a
######################################################################### 100.0%
==> Pouring portable-ruby-2.6.10_1.el_capitan.bottle.tar.gz
==> Tapping homebrew/core
Cloning into '/usr/local/Homebrew/Library/Taps/homebrew/homebrew-core'...
remote: Enumerating objects: 1464345, done.
remote: Counting objects: 100% (269/269), done.
remote: Compressing objects: 100% (134/134), done.
remote: Total 1464345 (delta 170), reused 228 (delta 135), pack-reused 1464076
Receiving objects: 100% (1464345/1464345), 570.17 MiB | 25.24 MiB/s, done.
Resolving deltas: 100% (1023201/1023201), done.
Updating files: 100% (6970/6970), done.
Tapped 2 commands and 6625 formulae (6,981 files, 626.2MB).
==> Installation successful!

==> Homebrew has enabled anonymous aggregate formulae and cask analytics.
Read the analytics documentation (and how to opt-out) here:
  https://docs.brew.sh/Analytics
No analytics data has been sent yet (nor will any be during this install run).

==> Homebrew is run entirely by unpaid volunteers. Please consider donating:
  https://github.com/Homebrew/brew#donations

==> Next steps:
- Run these two commands in your terminal to add Homebrew to your PATH:
    (echo; echo 'eval "$(/usr/local/bin/brew shellenv)"') >> /Users/shoko/.zprofile
    eval "$(/usr/local/bin/brew shellenv)"
- Run brew help to get started
- Further documentation:
    https://docs.brew.sh

shoko@lupin ~ % brew help 
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
shoko@lupin ~ % brew install hugo
Warning: You are using macOS 10.15.
We (and Apple) do not provide support for this old version.
It is expected behaviour that some formulae will fail to build in this old version.
It is expected behaviour that Homebrew will be buggy and slow.
Do not create any issues about this on Homebrew's GitHub repositories.
Do not create any issues even if you think this message is unrelated.
Any opened issues will be immediately closed without response.
Do not ask for help from Homebrew or its maintainers on social media.
You may ask for help in Homebrew's discussions but are unlikely to receive a response.
Try to figure out the problem yourself and submit a fix as a pull request.
We will review it but may or may not accept it.

==> Fetching dependencies for hugo: go
==> Fetching go
==> Downloading https://storage.googleapis.com/golang/go1.17.13.darwin-amd64.tar
######################################################################## 100.0%
==> Downloading https://go.dev/dl/go1.20.3.src.tar.gz
==> Downloading from https://dl.google.com/go/go1.20.3.src.tar.gz
######################################################################## 100.0%
==> Fetching hugo
==> Downloading https://github.com/gohugoio/hugo/archive/v0.111.3.tar.gz
==> Downloading from https://codeload.github.com/gohugoio/hugo/tar.gz/refs/tags/
             -#O=-  #    #     #                                              
Warning: Your Xcode (12.0) is outdated.
Please update to Xcode 12.4 (or delete it).
Xcode can be updated from the App Store.

Warning: A newer Command Line Tools release is available.
Update them from Software Update in System Preferences.

If that doesn't show you any updates, run:
  sudo rm -rf /Library/Developer/CommandLineTools
  sudo xcode-select --install

Alternatively, manually download them from:
  https://developer.apple.com/download/all/.
You should download the Command Line Tools for Xcode 12.4.

==> Installing dependencies for hugo: go
==> Installing hugo dependency: go
Warning: Your Xcode (12.0) is outdated.
Please update to Xcode 12.4 (or delete it).
Xcode can be updated from the App Store.

Warning: A newer Command Line Tools release is available.
Update them from Software Update in System Preferences.

If that doesn't show you any updates, run:
  sudo rm -rf /Library/Developer/CommandLineTools
  sudo xcode-select --install

Alternatively, manually download them from:
  https://developer.apple.com/download/all/.
You should download the Command Line Tools for Xcode 12.4.

==> ./make.bash
==> /usr/local/Cellar/go/1.20.3/bin/go install std cmd
🍺  /usr/local/Cellar/go/1.20.3: 11,978 files, 234.2MB, built in 2 minutes 10 seconds
==> Installing hugo
==> go build -ldflags=-s -w -tags extended
==> /usr/local/Cellar/hugo/0.111.3/bin/hugo gen man
==> Caveats
zsh completions have been installed to:
  /usr/local/share/zsh/site-functions
==> Summary
🍺  /usr/local/Cellar/hugo/0.111.3: 48 files, 58.6MB, built in 2 minutes 40 seconds
==> Running `brew cleanup hugo`...
Disable this behaviour by setting HOMEBREW_NO_INSTALL_CLEANUP.
Hide these hints with HOMEBREW_NO_ENV_HINTS (see `man brew`).
==> Caveats
==> hugo
zsh completions have been installed to:
  /usr/local/share/zsh/site-functions
shoko@lupin ~ %  
