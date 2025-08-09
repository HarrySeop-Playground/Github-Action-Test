# 깃허브 관련 실험실

## 1. Github Labels 한번에 적용하는 방법

- 개인 레포지토리일 경우

```bash
npx github-label-sync --access-token {AccessToken} --labels ./{파일명}.json {사용자 이름}/{레포지터리 이름}
```

- 조직 레포지토리일 경우

```bash
npx github-label-sync --access-token {AccessToken} --labels ./{파일명}.json {조직 이름}/{레포지터리 이름}
```

> 토큰권한은
> Github -> Settings -> Developer Settings -> Personal Access Tokens -> Classic
> Repository 관련 Scope만 체크하면 됩니다.
