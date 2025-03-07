### Hugo 基礎安裝步驟
若無法使用 winget install Hugo.Hugo.Extended 則採取手動安裝
- [hugo_extended_0.145.0_windows-amd64.zip](https://github.com/gohugoio/hugo/releases/download/v0.145.0/hugo_extended_0.145.0_windows-amd64.zip)
- 將 hugo.exe 複製到 C:\User\User 目錄下

```
winget install Hugo.Hugo.Extended
winget install -e --id Git.Git
hugo version
git --version
git config --global user.name "Your Name"
git config --global user.email name@example.com
git config --list
```

### 範本網站建置
- [Hugo Themes](https://themes.gohugo.io/) 


### [Hugoplate](https://themes.gohugo.io/themes/hugoplate/)
#### 需要安裝 Node v22+ 以及 Go v1.24+
- [Node v22+](https://nodejs.org/en/download/)
- [Go v1.24+](https://go.dev/doc/install)
- 建議使用 VSCode 搭配 Git Bash
```
hugo new site web
cd web
git init
git submodule add https://github.com/zeon-studio/hugoplate hugoplate
cd hugoplate
npm run project-setup
npm install
npm run dev
```

### [Beautiful Hugo - An adaptation of the Beautiful Jekyll theme](https://github.com/halogenica/beautifulhugo)
```
hugo new site web
cd web
git init
git submodule add https://github.com/halogenica/beautifulhugo.git themes/beautifulhugo
git clone https://github.com/adityatelange/hugo-PaperMod themes/PaperMod --dept
複製 example site
```

