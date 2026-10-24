# 로난 프롤로그 웹툰 · GitHub Pages

## 업로드 방법

1. GitHub에서 **ronan-prologue** 이름으로 **Public** 저장소를 생성합니다.
2. 이 ZIP 파일의 압축을 **해제**합니다. ZIP 파일을 통째로 저장소에 업로드하면 웹툰 사이트가 열리지 않습니다.
3. 압축 해제 후 `index.html`, `images` 폴더, `.nojekyll`, `README.md`를 저장소 최상위(root)에 업로드하고 **Commit changes**를 누릅니다. (`.nojekyll`은 숨김 파일입니다.)
4. 저장소의 **Settings → Pages → Build and deployment → Source: Deploy from a branch**를 선택합니다.
5. **Branch: main, Folder: /(root)**를 지정하고 **Save**합니다.
6. 웹사이트 주소는 일반적으로 `https://깃허브아이디.github.io/ronan-prologue/` 형식입니다.

## 사이트 구성

- 이미지 30장, 001.png부터 030.png까지 숫자순
- 원본 PNG의 실제 바이트를 **수정 없이** 보존
- 최대 폭 800px, 스마트폰 화면에서는 자동 맞춤
- 이미지는 위아래 여백 없이 세로로 이어짐
- 사이트 바깥 배경 #202124 / 이미지 구역 아래 기본 배경 #11111f
- 상단 표지 화면이나 별도 메뉴 없이 접속 즉시 1컷부터 시작

이미지를 업데이트하려면 `images` 폴더의 파일을 같은 이름으로 교체하면 됩니다. 이미지 수가 달라지면 `index.html`의 `<img>` 목록도 수정해야 합니다.
