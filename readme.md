readme.md

# React Github Page

Repo ini digunakan untuk template atau contoh project react yang akan di publish melalui Github Pages

## Requirement

Install gh-pages library

```
npm install --save gh-pages
```

## Clone Repo

Clone Project ini, dengan command berikut di Terminal

```
git clone https://github.com/kukodein/react-github-pages
```

## Install

```
npm install
```

## Deploy

Jalankan project ini dengan command berikut di Terminal

```
npm run start
```

## Deploy ke Github Pages

Untuk melakukan deployment ke github pages anda perlu melakukan langkah-langkah berikut:

1. Pastikan Requirement sudah dipenuhi
1. Pastikan ubah file `package.json`

   ```
    "homepage": "https://myusername.github.io/my-app",
   ```

1. Commit hasil perubahan ke repo baru

References: https://medium.com/@swarajgosavi20/how-to-deploy-react-on-github-pages-33e427f0bd36