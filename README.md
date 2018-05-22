# scoop bucket for korean

네이버 나눔 폰트 등 국내용 패키지를 설치하기 위한  [Scoop](http://scoop.sh) bucket 입니다.

아래 명령으로 버킷을 설치하면 됩니다.

```sh
scoop bucket add scoop-bucket-for-korean https://github.com/lesstif/scoop-bucket-for-korean.git
```

나눔 폰트 검색
```sh
scoop search nanum
```

나눔 폰트 설치
```sh
scoop installnanum-coding
```

windows 폰트 dir 에 들어가지는 않으므로 %HOME%/scoop/shims/apps 에 다운받은 폰트를 직접 설치해야 합니다.
