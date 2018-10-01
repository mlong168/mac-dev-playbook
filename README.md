# Mac Development Ansible Playbook

This playbook installs and configures most of the software you will use your Mac for web and software development. Some things in OS X are difficult to automate (notably, the Mac App Store and certain tools from Apple), so I still have some manual installation steps, but at least it's all documented here.

## Installation

  1. Install Ansible ( `sudo easy_install pip && sudo pip install ansible` )
  2. Ensure Apple's command line tools are installed (`xcode-select --install` to launch the installer).
  3. Clone this repository to your local drive.
  5. Run `ansible-playbook main.yml -i inventory --ask-sudo-pass` from the same directory as this README file.

## Included Applications / Configuration

Applications (installed with Homebrew Cask):

  - Homebrew
  - Java7
  - MacVim
  - Sequel Pro (MySQL client)
  - Sublime Text
  - TextMate
  - Tower (Git client)
  - Transmit (S/FTP client)
  - Vagrant (+ Vagrant Manager)
  - VirtualBox
  - ~~VLC~~
  - ~~Adium~~
  - ~~BetterTouchTool~~
  - ~~Google Chrome~~
  - ~~Dropbox~~
  - ~~Firefox~~
  - ~~Handbrake~~
  - ~~Menu Meters~~
  - ~~TimeMachineEditor~~
  - ~~Skype~~
  - ~~Skitch~~
  - ~~Seil~~
  - ~~Karabiner~~
  - ~~LICEcap~~
  - ~~nvALT~~

Packages (installed with Homebrew):

  - ansible
  - maven
  - gradle
  - autoconf
  - gettext
  - libevent
  - packer
  - python
  - sqlite
  - ssh-copy-id
  - cowsay
  - ios-sim
  - readline
  - openssl
  - pv
  - drush
  - wget
  - brew-cask

My [dotfiles](https://github.com/mlong168/dotfiles.git) are also installed into the current user's home directory, including the `.osx` dotfile for configuring many aspects of Mac OS X for better performance and ease of use.
