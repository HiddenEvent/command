# Windows 도구

아래 링크의 지시에 따라 chocolatey를 설치하세요.

https://chocolatey.org/docs/installation

```
choco install virtualbox --version=7.0.8 -y
```

```
choco install vagrant --version=2.3.7 -y
```

```
choco install git -y
```

```
choco install corretto11jdk -y
```

```
choco install maven -y
```

```
choco install awscli -y
```

```
choco install intellijidea-community -y
```

```
choco install vscode -y
```

```
choco install sublimetext3.app -y
```

# MacOS 도구

아래 링크의 지시에 따라 brew를 설치하세요.

https://brew.sh/

homebrew를 설치한 후 사용자 홈 디렉토리에 .curlrc라는 이름의 파일을 만들고 내용에 "-k"를 입력하세요.
("-k"는 따옴표 없이 입력하고 -k 뒤에 새 줄 문자를 넣습니다.)

단계:

1. 터미널 열기
2. 아래 명령어 실행

```
echo -k > ~/.curlrc
```

3. 아래 명령어를 실행하여 ~/.curlrc 파일에 -k가 있는지 확인

```
cat ~/.curlrc
```

터미널에서 아래의 모든 명령어를 실행하세요.

### (virtualbox 명령어는 MacOS M1/M2에는 적용되지 않습니다.)

```
brew install --cask virtualbox
```

```
brew install --cask vagrant
```

```
brew install --cask vagrant-manager
```

```
brew install git
```

```
brew install openjdk@11
```

```
sudo ln -sfn $HOMEBREW_PREFIX/opt/openjdk@11/libexec/openjdk.jdk /Library/Java/JavaVirtualMachines/openjdk.jdk
```

```
exec zsh -l
```

```
brew install maven
```

```
brew install --cask visual-studio-code
```

```
brew install --cask intellij-idea
```

```
brew install --cask intellij-idea-ce
```

```
brew install --cask sublime-text
```

```
brew install awscli
```
