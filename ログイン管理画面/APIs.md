#### ・API一覧 （Element対応）

| ID    | 名称         | メソット | リクエスト                    | レスポンス           | リンク                                         | 参考 |
|-------|------------|------|--------------------------|-----------------|---------------------------------------------|----|
| API-1 | ユーザーログイン   | POST | { email, password }      | { token, user } | **server-IP:8080**/api/v1/login             | -  |
| API-2 | ユーザー登録     | POST | { email, password, ... } | { user }        | **server-IP:8080**/api/v1/signup            | -  |
| API-3 | Googleログイン | POST | { token }                | { token, user } | **server-IP:8080**/login/oauth2/code/google | -  |
| API-4 | パスワードリセット  | POST | { email }                | { status }      | **server-IP:8080**/api/v1/forgot-password   | -  |