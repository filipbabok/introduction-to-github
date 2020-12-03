## ステップ６：プルリクエストを作ろう

コミットの作成に成功しました :sparkles:

コミットの作成が完了したので、次にプルリクエストによって変更を提案してみましょう！イシューでは他のメンバーと議論をすることが行われますが、プルリクエストではあなたが行った変更を共有し、その変更についてのフィードバックをもらい、完璧になるまでそれを繰り返すのです！

<details><summary>プルリクエストとはなにか？</summary>

## プルリクエスト

GitHubフローを思い返してみましょう。ブランチの作成をし、ファイルを追加し、ブランチにそのファイルをコミットしました。次にこのファイルについて他のメンバーとコラボレートしましょう。プルリクエスト上でコラボレーションを行います。詳細はこのビデオを御覧ください：

:tv: [ビデオ：プルリクエストの紹介](https://youtu.be/kJr-PIfLDl4)
<hr>
</details>

このプルリクエストは、ブランチに対して行った変更を保持し、`main`ブランチへ取り込むためのものです。

### :keyboard: やってみよう：プルリクエストの作成

1. [このリンク]({{ url }})をクリックするか、下記手順によってプルリクエストを作成しましょう：
    - "Pull requests"タブから、**New pull request**をクリックしましょう
    - "base:"ドロップダウンメニューでは、"main"が選択されている事を確認しましょう
    - "compare:"ドロップダウンメニューでは、"{{ branch | remove: 'refs/heads/' }}"を選択しましょう
    - "Create pull request"ボタンを押しましょう
1. ブランチを選択したら、プルリクエストのタイトルを入力しましょう。例えば`{{ user.username }}のファイルを追加`などです。
1. 次のフィールドには、行った変更の説明を記載します。ここまでに行ってきたことについて、自由に記載しましょう。ちなみに、ここまででこれらの事をやってきています：ブランチの作成、新規ファイルの作成、コミットの追加、プルリクエストの作成
1. **Create pull request**をクリックしましょう

<hr>
<h3 align="center">新しいプルリクエストが作成されたら、そこにコメントを書き込みます</h3>