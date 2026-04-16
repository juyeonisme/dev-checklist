# Dev Checklist

개발 작업별 단계 체크리스트 앱입니다.

## 기능
- 작업별 체크리스트 관리
- 단계(Phase) 추가 / 편집 / 삭제
- 항목 추가 / 편집 / 삭제 / 체크
- 진행률 표시
- 브라우저 로컬스토리지 자동 저장

## GitHub Pages 배포 방법

### 1. 저장소 생성
```bash
git init
git add .
git commit -m "init: dev checklist app"
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
```

### 2. GitHub Pages 설정
1. 저장소 → **Settings** → **Pages**
2. Source: **GitHub Actions** 선택
3. `main` 브랜치에 push하면 자동 배포

### 3. 접속
배포 완료 후 `https://<your-username>.github.io/<repo-name>/` 으로 접속
