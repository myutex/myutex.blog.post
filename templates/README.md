---
cover:
  image:
    src: 'https://raw.githubusercontent.com/myutex/myutex.blog.post/refs/heads/main/assets/images/cover-news.png'
title: '테스트 포스팅'
summary: '포스팅'
author:
  name: '양석순'
  role: 'Team Myutex Fake Engineer'
date:
  published: '2024-10-10'
  updated: '2024-10-10'
---

## Markdown 작성 가이드

이 문서는 이 레포지토리에서 마크다운 문서를 작성하는 방법에 대한 가이드를 제공합니다.

### 1. 파일 구조

```
/myutex.blog.post/
├── assets/
│   └── images/
│       └── cover-news.png
├── templates/
│   └── README.md
└── posts/
  └── example-post.md
```

### 2. 메타데이터

각 문서의 상단에는 다음과 같은 메타데이터가 포함되어야 합니다:

```yaml
cover:
  image:
    src: '이미지 URL'
title: '문서 제목'
summary: '문서 요약'
author:
  name: '작성자 이름'
  role: '작성자 역할'
date:
  published: 'YYYY-MM-DD'
  updated: 'YYYY-MM-DD'
```

### 3. 제목

문서의 제목은 `#`을 사용하여 작성합니다:

```markdown
# 문서 제목
```

### 4. 섹션

각 섹션은 `##`을 사용하여 작성합니다:

```markdown
## 섹션 제목
```

### 5. 코드 블록

코드 블록은 백틱(```)을 사용하여 작성합니다:
\`\`\`언어
코드 내용
\`\`\`

### 6. 링크

링크는 다음과 같이 작성합니다:

```markdown
[링크 텍스트](링크 URL)
```

### 7. 이미지

이미지는 다음과 같이 작성합니다:

```markdown
![이미지 설명](이미지 URL)
```

### 8. 목록

목록은 다음과 같이 작성합니다:

- 항목 1
- 항목 2
- 항목 3

### 9. 인용

인용은 `>`을 사용하여 작성합니다:

```markdown
> 인용 내용
```

이 가이드를 따라 마크다운 문서를 작성해 주세요.
