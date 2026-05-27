# Onecall Task Dashboard

원콜 통합 업무관리 대시보드 GitHub Pages 배포용 폴더입니다.

## Files

- `index.html`: PC/일반 화면용 V8 대시보드
- `tablet.html`: 태블릿 화면 최적화 V8_for tablet 대시보드

## GitHub Pages 설정

1. GitHub에서 새 저장소를 만듭니다.
2. 이 폴더의 파일을 저장소에 업로드합니다.
3. 저장소 `Settings > Pages`로 이동합니다.
4. `Build and deployment > Source`를 `Deploy from a branch`로 선택합니다.
5. Branch를 `main`, Folder를 `/root`로 선택하고 저장합니다.
6. 몇 분 후 `https://계정명.github.io/저장소명/` 주소로 접속합니다.

## 주의

이 대시보드는 standalone HTML 방식입니다. GitHub Pages는 열람/배포용이며, 업무 데이터는 각 브라우저의 localStorage 또는 `데이터 포함 HTML 저장` 파일에 저장됩니다.
