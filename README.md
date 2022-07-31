## アップデート情報
* version 1.0 : ガントチャート作成、開発に使った参考資料リンク置き場作成

## スケジュール
```mermaid
gantt
  title 開発スケジュール
  section スケジュール
    データ選定 :data, 2022-07-30, 1d
    目的      :goal, after data, 1d
    要件定義  :definition, after goal, 2d
    設計     :design, after definition, 2d
    開発     :coding, after design, 3d
    考察     :thinking, after coding, 2d
    レポート  :report, after thinking, 1d
 
```

## 参考資料集
### git関連
[gitコマンド](https://docs.microsoft.com/ja-jp/azure/developer/javascript/how-to/with-visual-studio-code/clone-github-repository?tabs=create-repo-command-palette%2Cinitialize-repo-activity-bar%2Ccreate-branch-command-palette%2Ccommit-changes-command-palette%2Cpush-command-palette)

[vscodeとgithub, gitを連携させるには](https://miya-system-works.com/blog/detail/vscode-github/)

### データ
[データセット入手先](https://www.kaggle.com/datasets/datasnaek/youtube-new?resource=download)
※japanのcsv, jsonファイルを今回のデータ分析に用いる

### プロジェクト管理関連, markdown関連
[mermaid.jsを用いたガントチャート作成](https://qiita.com/miriwo/items/7df0024d4098302e5721)
[mermaidの公式ドキュメント](https://mermaid-js.github.io/mermaid/#/stateDiagram)
[テーブルセル結合](https://b1san-blog.com/post/vscode/vscode-md-first/)