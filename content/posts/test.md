---
title: "hugo残念なハマり方、、、"
date: 2021-02-21T13:51:49+09:00
draft: false
---

### 試行錯誤したけど、、、
Github Pagesへの自動登録など色々とやっていて、netlifyにもアップしていたけど、トップ画面とPostの中身が一向に見えなかった、、、

### 原因は

---
title: "hugo残念なハマり方、、、"
date: 2021-02-21T13:51:49+09:00
draft: false
---

`draft`を`true`にしていたから。

ローカルで見れていたのは、`hugo server -D`で起動していたからだった

`draft`を`false`にしたらGithub Pages上にも正常に反映された

めっちゃ時間つかってしまった。


