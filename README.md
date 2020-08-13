# MediaServer

[![Build Status](https://travis-ci.org/bodrich/MediaServer.svg?branch=master)](https://travis-ci.org/bodrich/MediaServer)


[Оригинал здесь](https://github.com/GAumala/MediaServer) 

Работает, как под винду, так и под линуксом (другие платформы не проверял).

## Отличие от оригинала

Работает под виндой, не требует wget и make

## Установка, сборка и запуск
```
git clone github.com/bodrich/MediaServer
cd MediaServer
go install
go build
./MediaServer config.json
```

## Пример конфига
``` JSON
{
  "port": 5678,
  "verbose": true,
  "videoDirs": [ 
    "/home/gabriel/Videos/",
    "MEGAsync Downloads",
    "/home/gabriel/Downloads/" 
  ]
}
```


