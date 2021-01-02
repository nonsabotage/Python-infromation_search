

# Pythonではじめる情報検索プログラミング

information-searchにレポジトリ名を変更. 

## 1章：文字

- テキストデータは文字コードの集まり
- 文字と文字コードの対応付は複数ある
- エンコーディングを間違えると文字化け
- 本来のエンコーディングを推定することで文字化けは解消
- 正規表現で文字の並びのパターンを探しだすことが出来る


## 2章：語

- 形態素解析で，日本語のテキストデータを語に分解(分かち書き)できる
- 形態素解析で品詞を推定することもできる
- 正しく語に分解できると「東京都」と「東 京都」を区別することができる
- 文書は，個頻度で出現する少数の語と，低頻度で出現する多数の語に分かれる

## 3章：特徴語

- 高頻度で出現する語として，助詞などの機能語がある
- 文書の主題に関する語も高頻度で出現
- ある語が出現する文書の数で，その語のありふれ方がわかる
- 出現頻度を手がかりに文書に現れる語の重要度を推定できる
- 語の重要度の計算にはコーパスが必要
- Web上にあるテキストデータはコーパスとしても有用である

## 4章：文書のランキング

- 文書はそこに現れるごの重要度を列挙することでベクトルとして表現できる
- 文書ベクトルを比較することで文書の類似度がわかる
- 同様にクエリから作成したベクトルと文書ベクトルを比較することで検索ができる
- 検索対象の文書をクエリとの類似度順に並べることでランキングが可能となる

## ５章以降

なんか，あまり興味がわかなかったため，ざっと読んで終わり．

