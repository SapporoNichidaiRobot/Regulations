# Regulations

札幌日本大学中高一貫ロボット部規則
This is regulation of SNJRC.

## 閲覧 ( View )

1. 閲覧は全ての人が可能です。

## 編集 ( Edit )

-----

1. 編集を希望する人は、管理者に確認を取り、リポジトリをCloneし該当箇所を編集した後、Push & Pull Request を出してください。

1. Conflict が発生した場合は該当箇所を提示するので修正の上再度、Pull Request を出してください。

## 改訂 ( Revision )

1. 改訂を用いて、バージョン管理を行います。プルリクエストの度に改訂番号を更新してください。
    1. betaは草案段階です。草案ごとにブランチを作ります。部員のみでの編集はこちらを用います。beta ブランチで編集を行います。
        1. 条項の追加、運用上大幅な変更をもたらすものはメジャーアップデートです。
        > beta 0.0.0 → beta 0.1.0
        1. 文言の修正、枝分の修正はマイナーアップデートです。
        > beta 0.0.0 → beta 0.0.1
    1. alphaは審査段階です。草案完成ごとにalphaブランチを作ります。顧問と共同で編集を行います。alpha ブランチで編集を行います。
        1. 条項の追加、運用上大幅な変更をもたらすものはメジャーアップデートです。
        > alpha 0.0 → alpha 1.0
        1. 文言の修正、枝分の修正はマイナーアップデートです。
        > alpha 0.0 → alpha 0.1
    1. Releaseは完全版です。実際の活動ではReleaseが適用されます。master ブランチで編集を行います。
        1. 条項の追加、運用上大幅な変更をもたらすものはメジャーアップデートです。
        > Release 0.0 → Release 1.0
        1. 文言の修正、枝分の修正はマイナーアップデートです。
        > Release 0.0 → Release 0.1
1. 改訂の手順は以下の通りです。
    1. 草案（beta）の作成。beta リポジトリを alpha1リポジトリにマージします。
    1. 審査版（alpha）の作成。alpha リポジトリを
    1. 完全版（Release）の配布