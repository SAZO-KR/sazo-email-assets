# sazo-email-assets

사조 브랜드 정적 이미지 자산 (로고 · SNS 아이콘) 저장소.

[jsDelivr GitHub CDN](https://www.jsdelivr.com/github)을 통해 영구 캐시 배포되는 용도로 사용됩니다.

## 구조

```
logos/    로고
social/   SNS 아이콘 (X · Instagram · KakaoTalk)
```

## CDN URL

```
https://cdn.jsdelivr.net/gh/SAZO-KR/sazo-email-assets@main/logos/sazo_p_logo.png
https://cdn.jsdelivr.net/gh/SAZO-KR/sazo-email-assets@main/social/social-x.png
https://cdn.jsdelivr.net/gh/SAZO-KR/sazo-email-assets@main/social/social-instagram.png
https://cdn.jsdelivr.net/gh/SAZO-KR/sazo-email-assets@main/social/social-kakao.png
```

`@main` 자리에 커밋 SHA를 넣으면 특정 시점의 자산을 영구 고정할 수 있습니다:

```
https://cdn.jsdelivr.net/gh/SAZO-KR/sazo-email-assets@<commit-sha>/social/social-x.png
```

## 라이선스

- SNS 아이콘 (`social/`): [Simple Icons](https://simpleicons.org), CC0 1.0 (Public Domain) — 어트리뷰션 의무 없음. 단색 `#999999` 96×96 PNG로 래스터라이즈.
