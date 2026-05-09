# sazo-email-assets

사조 이메일 템플릿용 정적 자산 저장소. 템플릿 본체는 [SAZO-KR/sazo-email-templates](https://github.com/SAZO-KR/sazo-email-templates)(private)에 있음.

이 레포는 **public** 이며, [jsDelivr GitHub CDN](https://www.jsdelivr.com/github)을 통한 영구 캐시 배포 용도로만 사용된다.

## 구조

```
social/   SNS 아이콘 (Instagram, Kakao, X)
logos/    사조 로고 변형
```

## CDN URL

```
https://cdn.jsdelivr.net/gh/SAZO-KR/sazo-email-assets@main/social/social-x.png
https://cdn.jsdelivr.net/gh/SAZO-KR/sazo-email-assets@main/social/social-instagram.png
https://cdn.jsdelivr.net/gh/SAZO-KR/sazo-email-assets@main/social/social-kakao.png
```

URL은 영구 캐시. 한 번 발행한 메일은 동일 URL을 영원히 참조 가능.

특정 커밋 고정이 필요하면 `@main` 자리에 커밋 SHA를 넣는다:

```
https://cdn.jsdelivr.net/gh/SAZO-KR/sazo-email-assets@<commit-sha>/social/social-x.png
```

## 라이선스

- SNS 아이콘 (`social/`): Font Awesome Free, CC BY 4.0
  - 사이트 약관 페이지에 어트리뷰션 한 줄 명시 필요: `Icons by Font Awesome (https://fontawesome.com)`
