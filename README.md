# SYNORA Landing Page

밝고 프리미엄한 무드의 `SYNORA` AI 스마트 안경 제품 랜딩 페이지입니다.

## 포함 내용

- 풀스크린 히어로 비디오
- 민트 포인트 컬러 기반의 반응형 UI
- 햅틱 신호 시스템 소개
- 제품 디테일 이미지 섹션
- 모바일 메뉴와 스크롤 애니메이션

## 파일 구조

```text
.
├─ index.html
├─ styles.css
├─ script.js
├─ .nojekyll
├─ .github/
│  └─ workflows/
│     └─ deploy.yml
└─ assets/
   ├─ images/
   └─ video/
```

## 로컬에서 보기

아래 명령으로 간단히 실행할 수 있습니다.

```powershell
python -m http.server 4173
```

브라우저에서 아래 주소로 열면 됩니다.

- [http://127.0.0.1:4173/](http://127.0.0.1:4173/)

## GitHub 업로드

1. GitHub에서 새 저장소를 만듭니다.
2. 아래 명령으로 현재 폴더를 연결합니다.

```powershell
git add .
git commit -m "Initial SYNORA landing page"
git remote add origin https://github.com/사용자이름/저장소이름.git
git push -u origin main
```

## GitHub Pages 배포

이 프로젝트는 GitHub Pages 자동 배포 워크플로가 포함되어 있습니다.

1. 저장소를 GitHub에 올립니다.
2. GitHub 저장소의 `Settings > Pages`로 이동합니다.
3. `Source` 또는 `Build and deployment`에서 `GitHub Actions`를 선택합니다.
4. `main` 브랜치에 푸시하면 자동 배포됩니다.

배포 주소 예시는 아래와 같습니다.

- `https://사용자이름.github.io/저장소이름/`

저장소 이름을 `사용자이름.github.io` 로 만들면 아래 주소 형태도 가능합니다.

- `https://사용자이름.github.io/`

## 메모

- 모든 자산 경로는 상대경로로 연결되어 있어 GitHub Pages에서 바로 동작합니다.
- `.nojekyll` 파일이 포함되어 있어 정적 파일이 그대로 배포됩니다.

