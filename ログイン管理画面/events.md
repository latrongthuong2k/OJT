#### ・イベント説明

| ID    | イベント名称     | 動作                         | API              | リンク                                    | 説明                                            | 参考 |
|-------|------------|----------------------------|------------------|----------------------------------------|-----------------------------------------------|----|
| EVT-1 | ログイン試行     | 入力したメールアドレスとパスワードでログインを試みる | [API-1](APIs.md) | -                                      | ユーザー認証を行い、成功時にはメイン画面へ遷移する。失敗時にはエラーメッセージを表示する。 | -  |
| EVT-2 | パスワードリセット  | パスワードリセットページへ遷移する          | -                | **server-IP:3000**/auth/password-reset | クリックするとパスワードリセットのページへ遷移する。                    | -  |
| EVT-3 | Googleログイン | Googleアカウントでログインを試みる       | [API-3](APIs.md) | -                                      | Google APIを使用して認証を行う。                         | -  |
| EVT-4 | パスワードを表示   | 入力したパスワードを表示する             | -                | -                                      | チェックボックスをクリックすると入力したパスワードが表示する。               | -  |
| EVT-5 | 新規登録遷移     | 新規登録ページへ遷移する               | -                | **server-IP:3000**/auth/register       | クリックすると新規登録のページへ遷移する。                         | -  |

