# Text-Simplification_BART
- 日本語のテキスト平易化
* タスク
  * 難解な文を平易な文に変換
  * 評価指標： SARI

* データセット
  * データセットは [MATCHA](https://github.com/EhimeNLP/matcha)を使用
  * 訓練用：10,000件、検証用：3,000件、評価用：3,000件

* モデル
  * [Japanese BART Pretrained Model](https://github.com/utanaka2000/fairseq/blob/japanese_bart_pretrained_model/JAPANESE_BART_README.md)

- 実行手順
1. trainのフォルダをダウンロードし、以下のように実行<br>
   ```python luke_train.py --config_file train_config.json```

2. testのフォルダをダウンロードし、以下のように実行<br>
   ```python luke_test.py --config_file test_config.json```

