# Hugo practical test
build with [HUGO](https://gohugo.io/)


1. Download Hugo bin
```
https://github.com/gohugoio/hugo/releases
```
2. copy hugo bin in bin/ folder
3. start new site in current folder with 
```
./bin/hugo new site . --force
```
4. download theme into theme folder
5. set themename in config YAML
6. test static site
```
./bin/hugo server -wDEF --disableFastRender
```

## production
build site to /public with
```
./bin/hugo 
```

## TODO

- [x] Init custom Theme
- [x] Init Netifly CMS
- [ ] Check Identities
- [ ] Test Netifly Forms
- [ ] Test Alternatives to Netifly
- [ ] Building css in Netifly not possible

https://www.netlifycms.org/docs/intro/
https://gohugo.io/themes/creating/
