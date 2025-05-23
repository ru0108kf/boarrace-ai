# boarrace-ai
競艇アルゴリズムの構築を目指すプロジェクトです。

## 機能概要
- 番組表/結果のスクレイピング機能&データ分析
- 直前情報のスクレイピング機能
- アルゴリズム（未実装）
- 機械学習（仮実装）
- Web/スマホアプリ化（未実装）

---

## ディレクトリ構成
```text
boatrace-analyzer/
├── data/                  # 生データ（TXT,csvなど）
│   ├── K_lzh  # 競走成績_lxh
│   ├── B_lzh  # 番組表_lzh
│   ├── K_txt  # 競走成績_txt
│   ├── B_txt  # 番組表_txt
│   ├── K_csv  # 競走成績_csv
│   ├── B_csv  # 番組表_csv
│   ├── o_csv  # オッズ_csv
│   ├── merged_csv  # 番組表と競走成績をマージしたcsv
│   └── agg_results # 集計結果をまとめたフォルダ
├── scripts/
│   ├── base.py  # 処理をまとめたクラス
│   ├── scraper.py    # スクレイピング処理
│   ├── analyzer.py     # 分析処理
│   └── machinelearning.py     # 機械学習
├── main.py                # 実行用スクリプト
├── requirements.txt       # 必要ライブラリ
└── README.md
```
## 開発環境
- Python 3.9+

## Author
- 管理者：@ru0108kf
- リーダー：usami
  
