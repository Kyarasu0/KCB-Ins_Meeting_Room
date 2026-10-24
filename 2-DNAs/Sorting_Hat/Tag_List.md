# Tag_List(現在見つけているタグの一覧)
## このファイルについて
- Sorting_Hat が、依頼を分類するときに使う。新しいタグを作ったら、ここに追記する(タグの数は必要最小限にする)
- タグ名は、英語で書く。`グループ-名前`(例: `Developments-Design_Consultation`)の形で、グループ名は、Gene名のカッコの値(`t#Developments`)と同じにする
- 変更は、睡眠のときに、KCBへ反映(push)する

## タグ
| タグ | 内容 | 指定されるGene(`t#every` のGeneは、すべてのタグで指定される) |
| --- | --- | --- |
| Daily_Chat | 作業を伴わない、雑談などの会話 | なし |
| Question_Answering | 調べものや質問への回答 | なし |
| Developments-Design_Consultation | 開発の設計についての相談 | `Gene(t#Developments)-Issue_Reaper_from_monita` |
| Developments-Implementation_Request | 開発の実装の依頼 | `Gene(t#Developments)-Issue_Reaper_from_monita` |
| Tools-Slide_Creation | PowerPointなどのツールを使った、資料の作成 | なし |
