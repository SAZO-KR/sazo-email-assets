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
https://cdn.jsdelivr.net/gh/SAZO-KR/sazo-email-assets@main/logos/sazo_p_logo.png
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

- SNS 아이콘 (`social/`): [Simple Icons](https://simpleicons.org), CC0 1.0 (Public Domain)
  - 어트리뷰션 의무 없음
  - 색상은 `#999999`(푸터 텍스트와 동일) 단색으로 래스터라이즈한 96x96 PNG
