### Hugo 基礎安裝步驟
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

### [Beautiful Hugo - An adaptation of the Beautiful Jekyll theme](https://github.com/halogenica/beautifulhugo)
```
hugo new site web
cd web
git init
git submodule add https://github.com/halogenica/beautifulhugo.git themes/beautifulhugo
git clone https://github.com/adityatelange/hugo-PaperMod themes/PaperMod --dept
複製 example site
```

### [Hugoplate](https://themes.gohugo.io/themes/hugoplate/)
#### 需要安裝 Node v22+ 以及 Go v1.24+
- [Node v22+](https://nodejs.org/en/download/)
- [Go v1.24+](https://go.dev/doc/install)

```
hugo new site web
cd web
git init
git submodule add https://github.com/zeon-studio/hugoplate themes/hugoplate
npm run project-setup
npm install
npm run dev
```
