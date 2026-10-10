# 모모의 공부일지

개발 공부와 기술 기록을 정리하는 개인 블로그입니다.

## 기술 스택

- [Jekyll](https://jekyllrb.com/)
- [Chirpy 테마](https://github.com/cotes2020/jekyll-theme-chirpy)
- GitHub Pages 및 GitHub Actions

## 로컬 실행

Ruby와 Bundler가 설치된 환경에서 실행합니다.

```bash
bundle install
bundle exec jekyll serve
```

브라우저에서 http://127.0.0.1:4000 에 접속하면 됩니다.

## 배포

`main` 브랜치에 변경 사항을 반영하면 GitHub Actions가 사이트를 빌드하고 GitHub Pages에 배포합니다. 저장소의 **Settings → Pages → Build and deployment** 설정에서 배포 소스가 **GitHub Actions**인지 확인하세요.
