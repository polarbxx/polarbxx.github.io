# 03 Blog

Jekyll와 GitHub Pages로 운영하는 블로그 프로젝트입니다.

## 시작하기

```bash
bundle install
bundle exec jekyll serve
```

브라우저에서 `http://127.0.0.1:4000`으로 접속하면 로컬 미리보기를 볼 수 있습니다.

## GitHub Pages 설정

1. GitHub에 저장소를 푸시합니다.
2. 저장소가 `USERNAME.github.io`라면 `_config.yml`의 `baseurl`은 `""`로 유지합니다.
3. 저장소가 일반 이름이라면 `_config.yml`의 `url`과 `baseurl`을 아래처럼 바꿉니다.

```yml
url: "https://USERNAME.github.io"
baseurl: "/REPOSITORY_NAME"
github_username: USERNAME
```

4. GitHub 저장소의 `Settings > Pages`에서 GitHub Actions를 배포 소스로 사용합니다.

## 새 글 쓰기

`_posts/YYYY-MM-DD-title.md` 형식으로 파일을 만들면 됩니다.

예시:

```markdown
---
layout: post
title: "새 글 제목"
date: 2026-04-14 23:40:00 +0900
categories: [dev]
---
본문을 여기에 작성합니다.
```
