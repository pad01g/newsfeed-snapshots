# newsfeed-snapshots

World Front Pages の日次スナップショット(GitHub Pages)。

世界各国の報道機関のトップページを定点観測し、一面記事の見出しを日本語化して、同じ出来事を言語横断でまとめ、人口カバー率順に並べたもの。
収集・翻訳・集計はローカル環境で行い、その結果だけを静的 JSON として毎日ここに追加しています。

- `data/days/<YYYY-MM-DD>/clusters.json` — その日の話題 (クラスタ) と一面に載せた媒体・関連報道
- `data/days/<YYYY-MM-DD>/front.json` — 媒体ごとの一面上位リンク
- `data/days.json`, `sources.json`, `countries.json`, `coverage.json`, `config.json` — 日付一覧・媒体・国・人口カバー率・集計設定

公開しているのは見出し・リンク・集計値のみで、記事本文は含みません。見出しの著作権は各媒体に帰属します。
