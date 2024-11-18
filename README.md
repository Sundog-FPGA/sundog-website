# Sundog FPGA Website

## Setup

1. Install Ruby: <https://www.ruby-lang.org/en/documentation/installation/>
2. Install Jekyll dependencies:


```shell
gem install bundler jekyll
```

3. Ensure the following lines are added as-is to your `..rc` file (such as `~/.zshrc` or `~/.bashrc`):
4. Restart your terminal shell

```
export GEM_HOME="$(ruby -e 'puts Gem.user_dir')"
export PATH="$PATH:$GEM_HOME/bin"
```

## Build and Serve

1. Execute `bundle` command:

```shell
bundle exec jekyll serve
```

