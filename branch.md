## ブランチとは何か

```
[rev.A1] --> [rev.A2] --> [rev.A3] # branch_A
         \
          \-> [rev.B1] --> [rev.B2] # branch_B
                        \
                         \-> [rev.C1] --> [rev.C2] # branch_C
プロジェクトの進展 ----------------------------->
```

ブランチとはひとつのリビジョンを指し示すポインタの名前であり、更新の履歴全体、リビジョンの流れを指すものではない。例えば上図のrev.C1はbranch_Cの一部ではなく、"過去にbranch_Cが示していたリビジョン"である。

## rebaseを行うべきでないケース

## コンフリクト

## ハッシュ値
