#git别名配置


###git别名配置
    git config --global alias.co checkout
    git config --global alias.ci commit
    git config --global alias.st status
    git config --global alias.br branch
    git config --global alias.hist "log --pretty=format:'%h %ad | %s%d [%an]' --graph --date=short"
    git config --global alias.type 'cat-file -t'
    git config --global alias.dump 'cat-file -p'

###.gitconfig配置文件
	[alias]
	  co = checkout
	  ci = commit
	  st = status
	  br = branch
	  hist = log --pretty=format:\"%h %ad | %s%d [%an]\" --graph --date=short
	  type = cat-file -t
	  dump = cat-file -p
  
###shell别名配置
	alias gs='git status '
	alias ga='git add '
	alias gb='git branch '
	alias gc='git commit'
	alias gd='git diff'
	alias go='git checkout '
	alias gk='gitk --all&'
	alias gx='gitx --all'
	
	alias got='git '
	alias get='git '