# hye343.github.io

개인 홈페이지 / 포트폴리오. [Jekyll](https://jekyllrb.com/) + [minimal-mistakes](https://mmistakes.github.io/minimal-mistakes/) 테마를 사용하며, GitHub Pages에서 바로 빌드됩니다.

## 폴더 구조

```
.
├── _config.yml          # 사이트 제목, 저자 정보, 메뉴 등 전체 설정
├── _data/navigation.yml # 상단 메뉴 항목
├── _pages/               # 소개/비전/목표/전략/계획/포트폴리오 페이지
├── assets/images/        # 프로필 사진, 포트폴리오 이미지 등
├── index.md              # 홈 화면
└── Gemfile
```

## 콘텐츠 채워 넣기 (TODO 찾기)

각 파일에 `> TODO` 또는 `<!-- TODO -->` 로 표시된 부분을 실제 내용으로 채워주세요.

1. `_config.yml` — 이름, 소개, 이메일, SNS 링크
2. `index.md` — 홈 화면 캐치프레이즈
3. `_pages/about.md` — 자기소개, 이력, 강점, 가치관
4. `_pages/vision.md` — 비전 선언문
5. `_pages/goals.md` — 단기/중기/장기 목표
6. `_pages/strategy.md` — 목표 달성 전략
7. `_pages/plans.md` — 실행 로드맵, 회고
8. `_pages/portfolio.md` — 공모전/프로젝트 목록
9. `assets/images/profile.jpg` — 프로필 사진 추가 (파일명은 `_config.yml`의 `author.avatar`와 맞추기)

## 로컬에서 미리보기 (선택 사항)

Ruby와 Bundler가 설치되어 있다면:

```bash
bundle install
bundle exec jekyll serve
```

브라우저에서 `http://localhost:4000` 접속.

로컬 환경을 세팅하지 않아도, GitHub에 push하면 GitHub Pages가 자동으로 빌드해줍니다.

## GitHub에 배포하기

1. GitHub에서 `hye343.github.io` 라는 이름으로 새 저장소 생성 (사용자 페이지는 이 이름이어야 자동으로 `https://hye343.github.io` 에서 서비스됩니다)
2. 이 폴더를 해당 저장소에 push
3. 저장소 **Settings → Pages** 에서 배포 브랜치가 `main` (또는 `master`) 로 설정되어 있는지 확인
4. 몇 분 후 `https://hye343.github.io` 에서 확인
