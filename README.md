# hugo-isl-ms
検証結果を外部公開するブログサイト

## DevEnv
| application    | note                      | link                                    |
| :------------- | :-------------            | :--                                     |
| HUGO           | static site generator     | [localhost:1313](http://localhost:1313) |

## Usage
Docker上でHUGOを動作させます。
静的HTML生成はDocker上で動作するHUGOで行います。

### 初期起動(初回のみ、２回目以降は「起動」参照)
```
$ git clone https://github.com/yoitsu1838/hugo-isl-ms
$ docker-compose build
$ docker-compose up -d
```

### 起動
```
$ docker-compose up -d
```

### 停止
```
$ docker-compose stop
```