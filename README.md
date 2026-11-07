# SCE (Static Content Environment)

정적 HTML 호스팅을 위한 저장소입니다.

## 🚀 빠른 시작

1. **단일 페이지 배포**: 루트 디렉토리에 `index.html` 파일을 작성하거나 교체합니다.
2. **새로운 페이지 추가**: 서브 폴더(예: `demo1/index.html`) 또는 HTML 파일(예: `about.html`)을 추가합니다.
3. **변경사항 푸시**:
   ```bash
   git add .
   git commit -m "Add new page"
   git push origin main
   ```

## 🌐 GitHub Pages 설정 안내

저장소 푸시 후 GitHub Pages를 활성화하면 웹에서 바로 접속할 수 있습니다:

1. [GitHub sce 저장소](https://github.com/choonsik/sce) 방문
2. **Settings** > 좌측 메뉴의 **Pages** 클릭
3. **Build and deployment** 항목의 **Branch** 설정:
   - Branch: `main` 선택
   - Folder: `/ (root)` 선택
   - **Save** 클릭
4. 1~2분 후 `https://choonsik.github.io/sce/` 주소로 사이트가 라이브됩니다.
