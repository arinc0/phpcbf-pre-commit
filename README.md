## 前提
phpcbfのバージョンを3.7.* にしておかないと、PHP7.4以上とかで実行時にdeprecatedがたくさん出るので注意
phpcbfのバージョンは特に依存なく上げられるはず

.git/hooks/にphpcbf-pre-commitを作成してコピペ

.git/hooks/pre-commitに下記行を追加(なければ作成)

```bash
$(dirname "$0")/phpcbf-pre-commit
```
