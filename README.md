# ruby_and_ruby_on_rails
Professional Ruby on Rails

## After Install Ruby
```sh
$ ruby -v
ruby 2.7.6p219 (2022-04-12 revision c9c2245c0a) [x64-mingw32]

$ ruby -e "puts 'Hello World'"
Hello World

$ cat a01_hello_world.rb
puts 'Hello World'

$ ruby a01_hello_world.rb
Hello World
```

- Extensions Installation on VS Code IDE:
```css
vscode-runner
Ruby LSP (Ruby is deprecated)
```

- Intall rails
```css
$ gem install nokogiri -v 1.15.6 
/* $ gem install rails -v 3.2.4 */
gem install rails -v 4.2.5
$ gem install rails

$ rails -v
Rails 7.1.3.3
```

### Install rvm on windows:
```sh
# Install GPG keys:
gpg --keyserver keyserver.ubuntu.com --recv-keys 409B6B1796C275462A1703113804BB82D39DC0E3 7D2BAF1CF37B13E2069D6956105BD0E739499BDB
# Install RVM:
\curl -sSL https://get.rvm.io | bash -s stable
# Close the Ubuntu terminal and open it again and run
rvm
# Install the ruby version for the project
rvm install 3.2.4
rvm install 4.2.5

rvm version
rvm 1.29.12 (master) by Michal Papis, Piotr Kuczynski, Wayne E. Seguin [https://rvm.io]


# Configure git.
git config --global user.name "tchatua"
git config --global user.email "tchattua@gmail.com"
```

- To use a specific version of ruby:
```sh
rvm use ruby-3.2.4 # For example
```

- To ensure the version that I want tu user is set by default:
```sh
rvm --default ruby-3.2.4 # For example
```


```sh
clear
pwd

```