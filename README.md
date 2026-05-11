# Mizrhan Portfolio Starter

이 폴더는 `Mizrhan.github.io` 리포지토리에 넣어 사용할 수 있는 GitHub Pages + Jekyll 포트폴리오 starter입니다.

## 사용 순서

1. 이 폴더의 파일들을 `Mizrhan.github.io` 리포지토리 루트에 복사합니다.
2. GitHub Pages 설정에서 `main` branch / `/root`를 선택합니다.
3. 로컬에서 미리 보려면 아래 명령을 실행합니다.

```bash
bundle install
bundle exec jekyll serve
```

4. 브라우저에서 `http://127.0.0.1:4000`을 열어 확인합니다.
5. 수정 후 commit/push하면 `https://mizrhan.github.io`에 반영됩니다.

## 먼저 수정할 부분

- `_layouts/default.html`의 이메일 주소
- `resume.md`의 학력/자격증/경력
- 각 프로젝트 페이지의 “My Role”
- 정확한 수치, 데이터 기간, 성능 개선율
- 프로젝트별 이미지 또는 대시보드 캡처
