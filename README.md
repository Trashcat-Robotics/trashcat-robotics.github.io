# Trashcat Robotics Blog

Hosted with GitHub Pages at [trashcat-robotics.github.io](https://trashcat-robotics.github.io)

## Install Requirements

See [requirements](https://jekyllrb.com/docs/installation/).

Ubuntu:

```bash
sudo apt-get install ruby-full build-essential zlib1g-dev
echo '# Install Ruby Gems to ~/gems' >> ~/.bashrc
echo 'export GEM_HOME="$HOME/gems"' >> ~/.bashrc
echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc
gem install jekyll bundler
```

Blog was created with `jekyll new blog`.

## Build

If changes are made to the Gemfile:
```
bundle install
```

To view in browser:
```
bundle exec jekyll serve
```