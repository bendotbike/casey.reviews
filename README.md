# casey.reviews
The source and production code for http://casey.reviews

## Dependancies
- git
- nodejs
- npm
- hexo
- [bootstrap-theme](https://github.com/bendotbike/bootstrap-theme)

## Build
### Install
```
mkdir casey.reviews

cd casey.reviews

git clone https://github.com/bendotbike/casey.reviews.git

npm install

git clone https://github.com/bendotbike/bootstrap-theme themes/bootstrap-theme
```
Now open ```/casey.reviews/_config.yml```, and change ```theme``` to ```bootstrap-theme```
```
hexo clean
hexo generate
hexo serve
```
