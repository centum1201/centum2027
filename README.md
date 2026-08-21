# 센텀직업전문학교 수료생 포트폴리오 아카이브

수료생 포트폴리오 링크 모음 사이트입니다. `index.html` 하나로 동작하는 정적 페이지입니다.

## GitHub Pages로 올리는 방법

1. GitHub에서 새 저장소를 만듭니다 (예: `centum-portfolio`).
2. 이 폴더의 `index.html` 파일을 저장소에 업로드합니다.
   - GitHub 웹사이트에서: 저장소 페이지 → **Add file → Upload files** → `index.html` 드래그 후 **Commit changes**
3. 저장소의 **Settings → Pages**로 이동합니다.
4. **Source**를 `Deploy from a branch`로 두고, Branch를 `main` (또는 `master`), 폴더를 `/ (root)`로 선택 후 **Save**.
5. 1~2분 후 `https://[사용자명].github.io/[저장소명]/` 주소로 접속하면 사이트가 열립니다.

## 내용 수정

`index.html` 안의 `GROUPS` 배열(자바스크립트)에 기수/과정별 이름과 링크가 정리되어 있습니다.
이름·링크를 추가/수정하려면 이 배열에 `['이름','링크주소']` 형태로 한 줄을 추가하거나 고치면 됩니다.
