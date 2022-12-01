.git/hooks/にphpcbf-pre-commitを作成してコピペ

.git/hooks/pre-commitに下記行を追加(なければ作成)

```bash
$(dirname "$0")/phpcbf-pre-commit
```
