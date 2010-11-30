開発者 Tomohiro が追加した機能です。
================================================================================

1. 新機能ブランチ作成&ブランチへ移動

       git checkout -b myfeauture develop

2. 新機能作成して commit

       touch Tomohiro-add-Feauture
       vi Tomohiro-add-Feauture
       git add Tomohiro-add-Feauture
       git commit -m '新機能追加'

3. 開発ブランチへ移動

       git checkout develop

4. 新機能をマージ

       git merge --no-ff myfeauture

5. 不要になった新機能ブランチを削除

       git branch -d myfeauture

6. origin の develop ブランチに反映

       git push origin develop
