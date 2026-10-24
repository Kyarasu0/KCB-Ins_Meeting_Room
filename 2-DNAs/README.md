# DNAs-Meeting-Room
## 用語の説明
| 用語 | 説明 |
| --- | --- |
| DNAs | Geneを集めたもの。このフォルダ |
| Gene | 思考プロセス(有起点・無起点・睡眠)に差し込む、1つずつの追加の動き。Geneごとに、「プロセスXで、このGeneが指定されているときは、こうする」という形で書く |
| 指定 | そのGeneを使うと決まっていること。ユーザーが指示したとき、またはGene名のカッコの条件に当てはまるときに、指定される。`x#` のGeneは、指定されない |
| Gene名の読み方 | `Gene(t#every)-Name` のように書く。カッコ内は、動く条件。t = tag(依頼のタグ)で、#の後ろがタグの値(every = すべてのタグ、Developments = `Developments-` で始まるタグ(`Developments-Design_Consultation`、`Developments-Implementation_Request` など))。条件に当てはまる依頼のときに、そのGeneが指定される |
| 無効のGene | 条件の文字を `x` にしたもの(例: `Gene(x#every)-Name`)。書いてあるだけで、実行しない。指定されても動かない。有効にするときは、`x` を `t` に書き換える |

## 目的
- 思考プロセスの本体は変えずに、依頼の種類や目的に応じた動きを、あとから差し込めるようにする
- 差し込む動きを、Geneごとに分けて管理する

## 役割
- 各Geneを、思考プロセスのどのタイミングで何をするか、という形で定義する
- Geneは、1つずつフォルダを作り、その中にmdを置く(Geneのmdのほかに、そのGeneが使うmdも、同じフォルダに置く)

## Geneの一覧
| Gene | フォルダ |
| --- | --- |
| Gene(t#Developments)-Issue_Reaper_from_monita | `Issue_Reaper_from_monita/`(`Gene(t#Developments)-Issue_Reaper_from_monita.md`) |
| Gene(t#every)-Request_Sorter(依頼のタグ付け・仕分け) | `Request_Sorter/`(`Gene(t#every)-Request_Sorter.md`、`Tag_List.md`) |
| Gene(t#every)-Pseudo_Emotion_Research(疑似感情の調査) | `Pseudo_Emotion_Research/`(`Gene(t#every)-Pseudo_Emotion_Research.md`、`Emotion_Vector_Table.md`) |
