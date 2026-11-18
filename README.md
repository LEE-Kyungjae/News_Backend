# News_Backend

## Configuration

Secrets are read from environment variables instead of being committed:

| Variable | Used by |
| --- | --- |
| `DB_PASSWORD` | MySQL datasource (`dev` profile) and `MySQLTest` |
| `JWT_SECRET_KEY` | JWT signing key (`dev` and `prod` profiles) |
| `GITHUB_CLIENT_SECRET` (and `GITHUB_CLIENT_ID` for `prod`) | GitHub OAuth2 login |
| `KAKAO_CLIENT_ID`, `KAKAO_CLIENT_SECRET` | Kakao OAuth2 login |
