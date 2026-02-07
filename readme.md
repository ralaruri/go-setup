## Setup 

### Installing Go using asdf
- This is how I manage my local Go installations 

1. Installing asdf using homebrew
- `brew install asdf`
- `echo -e "\n. $(brew --prefix asdf)/libexec/asdf.sh" >> ~/.zsh_profile`

2. Installing go 
- `asdf plugin add golang`
- `asdf install golang latest`

3. Setting a Version 
- `asdf global go latest`
if you need to a set a local env.
- `asdf local go latest`


### Setting Up Golang 

``` 
go mod initmod init github.com/ralaruri/repo
```




