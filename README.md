# hamonikr-fonts

하모니카 사용자들이 다른 운영체제의 폰트가 없어서 글씨가 깨어지는 경우
설치해서 사용할 수 있는 추가 폰트입니다.

Fonts for HamoniKR 4.0

 * KoPub (http://www.kopus.org/biz/electronic/font.aspx)
 * fake-Gulim (https://moordev.tistory.com/176)
 * ms-core-fonts
 * mac fonts and others (https://github.com/freshsomebody/mac-fonts/tree/master/macfonts)
 * fake-malgun (https://moordev.tistory.com/336)
 * wps-office-fonts for CJK

## 프로그램 설치 (하모니카 1.4, 하모니카 3.0, 하모니카 4.0)

하모니카 사용자는 `apt 저장소 추가 단계`가 필요없습니다.

1) 하모니카 apt 저장소를 추가하고 업데이트
```
curl -sL https://pkg.hamonikr.org/add-hamonikr.apt | sudo -E bash -
sudo apt install -y hamonikr-fonts
```
설치 과정에 라이선스 동의화면이 나오면 Ok를 선택하세요.


## 프로그램 삭제

```
sudo apt purge hamonikr-fonts
```

## 버그 또는 이슈 제출

사용 중 발견한 버그나 이슈는 root@hamonikr.org 로 메일을 보내주세요
