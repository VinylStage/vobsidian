## oh-my-zsh setting

```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```
### plugins

1. autosuggestions 설치

```
git clone [https://github.com/zsh-users/zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions) ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
```

2. syntax-highlighting 설치

```
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
```

3. .zshrc에 추가
```
vi ~/.zshrc
```

```
plugins=(
	git
	zsh-syntax-highlighting
	zsh-autosuggestions
)
```


