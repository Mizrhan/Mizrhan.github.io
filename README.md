# 이찬식 데이터 분석 포트폴리오

이 버전은 Jekyll을 사용하지 않는 정적 HTML/CSS 포트폴리오입니다.

## 왜 Jekyll을 제거했는가

기존 starter는 Jekyll 기반이었고, 로컬 실행 시 Ruby 4.x와 GitHub Pages 의존성 충돌이 발생할 수 있었습니다.
이번 버전은 `index.html`과 `assets/css/style.css`만으로 동작하므로 Ruby, Bundler, Jekyll 설치가 필요 없습니다.

## 로컬에서 확인하는 법

가장 쉬운 방법은 `index.html`을 더블클릭해 브라우저에서 여는 것입니다.

조금 더 안정적으로 확인하려면 터미널에서 아래 명령을 실행합니다.

```bash
python -m http.server 8000
```

그다음 브라우저에서 아래 주소를 엽니다.

```text
http://localhost:8000
```

## GitHub Pages에 올리는 법

1. 이 폴더 안의 파일을 `Mizrhan.github.io` 리포지토리 루트에 복사합니다.
2. 기존 Jekyll 파일이 필요 없다면 `_config.yml`, `Gemfile`, `Gemfile.lock`, `_layouts`는 삭제해도 됩니다.
3. GitHub에 commit/push합니다.
4. GitHub 리포지토리의 Settings > Pages에서 `main` branch와 `/ root`를 선택합니다.
5. `https://mizrhan.github.io`에서 확인합니다.

## 먼저 수정하면 좋은 부분

- `resume/index.html`: 실제 공개 여부에 따라 전화번호 추가 여부 결정
- `projects/visibility-research/index.html`: 논문 상태가 게재 완료인지 Minor Revision인지 최종 확인
- `projects/navigation-routing/index.html`: Tableau 링크가 정상 공개되는지 확인
- 각 프로젝트 페이지: 팀원 수, 사용 데이터 기간, 정량 지표 추가
- `assets/css/style.css`: 색상과 여백 조정

## 반영한 자료

- 최신 이력서 PDF
- Notion 포트폴리오 공개 페이지
- GitHub 공개 리포지토리
- Hugging Face 공개 리포지토리
