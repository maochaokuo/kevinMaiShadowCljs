# kevinMaiShadowCljs
follow Kevin Mai's How to Set Up Shadow CLJS

## step1
```
yarn init -y
```
then
```
touch shadow-cljs.edn
or
echo "" > shadow-cljs.edn
```

## step2
fill in initial shadow-cljs.edn
content

## step3
```
mkdir -p src\cljs\app
echo "" > src\cljs\app\core.cljs
```

## step4
```
yarn add shadow-cljs
```

## step5
```
yarn start
```

## step6
```
echo "" > resources\public\index.html
```

## step7
now in chrome developer tool 
1. click the gear setting button 
2. check Console enable custom formatters
3. then close the setting, and fresh
4. will see neater output in developer tool console