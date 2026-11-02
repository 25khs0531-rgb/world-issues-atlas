# 세계 국가별 문제 탐색 지도

GitHub Pages로 공개할 수 있는 정적 웹사이트입니다. 국가별 문제 977개 항목(기존 지표 근거 확인 502건, 추가 조사 후보 475건)을 195개국 단위로 살펴볼 수 있습니다.

## GitHub Pages 공개 방법

1. GitHub에 로그인하여 https://github.com/new 에서 `world-issues-atlas`라는 **Public** 저장소를 만듭니다. 저장소를 만들 때 README를 추가해도 됩니다.
2. 저장소에서 **Add file → Upload files**를 선택합니다.
3. 이 압축파일을 **압축 해제**한 뒤 `index.html`, `.nojekyll`, `robots.txt`, `README.md`를 저장소 최상위 폴더에 업로드합니다. `.nojekyll`은 숨김 파일로 표시될 수 있으며 없어도 대부분의 경우 HTML이 게시됩니다.
4. **Commit changes** 버튼을 클릭합니다.
5. 저장소의 **Settings → Pages → Build and deployment → Source: Deploy from a branch**를 선택합니다.
6. **Branch: main / (root)**를 선택하고 **Save**합니다.
7. 게시된 주소를 **Settings → Pages**에서 확인합니다. 일반적인 형식은 `https://계정이름.github.io/world-issues-atlas/`입니다. 실제 게시 주소는 GitHub에서 생성된 뒤 확인해야 합니다.

공식 가이드: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site

## 주의사항

- **정적 시연용 사이트**입니다. 기존에 요청한 일반/관리자 비밀번호가 HTML 파일 안에 포함되어 있으므로 실제 보안 인증으로 사용할 수 없습니다. GitHub 저장소가 공개되면 누구나 소스를 읽을 수 있습니다.
- 관리자 편집 기능으로 변경한 내용은 **해당 브라우저의 로컬 저장소에만 보존**됩니다. 다른 이용자에게 동시에 표시되지 않습니다. 사이트 공용 편집 및 권한 제어를 위해서는 별도 서버 인증과 데이터베이스가 필요합니다.
- 비밀번호 5회 오류 시 접근 차단은 브라우저 단위입니다. 브라우저 밖의 강제 퇴출 기능은 제한되어 있습니다.
- 추가된 475개 항목은 사실 확인이 끝난 '발생 문제'가 아닌 **미검증 조사 후보**입니다.
- GitHub Pages는 HTML/CSS/JS 파일 게시만 가능하므로 서버형 API는 GitHub Pages 자체에서 실행할 수 없습니다.
