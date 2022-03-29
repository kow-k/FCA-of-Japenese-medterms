# FCA-on-medterms

FCA applied to Japanese medical terminology

2022年3月に実施された言語処理学会28回年次大会 (NLP28/2022) のPH1-1の発表「医療用語の is-a オントロジー構築の　FCA を使った効率化」で使ったデータの公開

## data

1. [fc-X-shou-dev.xlsx](data/fc-X-shou-dev.xlsx) [Concept Explorer に与える形式文脈 fc=formal context を生成するための Excel 作業本]
2. [fc-X-shou-full-6gram-sorted.csv](data/fc-X-shou-full-6gram.csv) ["X症" の全425事例の fc (csv形式)]
3. [fc-X-shou-set0-6gram-sorted.csv](data/fc-X-shou-set0-6gram.csv) ["X症" のsample0 68事例の fc (csv形式)]
4. [fc-X-shou-set1-6gram-sorted.csv](data/fc-X-shou-set1-6gram.csv) ["X症" のsample1 118事例の fc (csv形式)]
5. [fc-X-shou-set2-6gram-sorted.csv](data/fc-X-shou-set2-6gram.csv) ["X症" のsample2 207事例の fc (csv形式)]

## poster

[NLP28/2022 PH1-1 のポスター](https://www.dropbox.com/s/sb0um9nqnx7r1pt/PH1-1-poster-medont-dev-nlp28.pdf?dl=0)

## paper

[NLP28/2022 PH1-1 の論文](https://www.dropbox.com/s/34aafkuj0wvlxgt/paper-medont-dev-nlp28.pdf?dl=0)

### 論文の補足

論文の題は is-a 関係に特化している印象を与えますが，Hasse 図のノード間の関係は open なので，is-a 関係を含んでいるところが見やすいというだけの話です．その次に分類やすいのは has-a 関係でしょう．

## tools (external)

Hasse 図を描くためのツール [ConceptExplorer 1.3](http://conexp.sourceforge.net/)

