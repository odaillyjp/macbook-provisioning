# Configuration Xcode

```sh
$ sudo xcodebuild -license
$ xcode-select --install
```

# Install homebrew

```sh
$ ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

# Install ansible

```sh
$ brew install python
$ brew install ansible
```

# Run ansible playbook

```sh
$ ansible-playbook -i hosts -vv localhost.yml
```
