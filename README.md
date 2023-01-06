[![HitCount](http://hits.dwyl.com/SharkDemon/rd-dot-com.svg)](http://hits.dwyl.com/SharkDemon/rd-dot-com)

# rd-dot-com

This project contains the Hugo-generated HTML files comprising the website at [rorydickinson.com](https://rorydickinson.com).

I've been using the following command to run the website locally:
```
hugo server --disableFastRender -p 80 --buildDrafts
```

I've been using the following command to generate the site from source:
```
hugo ^
--baseURL https://www.rorydickinson.com ^
--cleanDestinationDir ^
--destination ../output ^
--minify ^
--source ./src
```
