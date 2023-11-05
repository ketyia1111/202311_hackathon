# 202311_hackathon

【プロジェクト概要】
手書きのノートの文字部分をOCRで文字データに変換する。そのあと、LLMで文字データの補完、要約を行い出力する

【技術】
・python (flask)
・OCR API
・LLM API

メンバーが開発した機能は「components」に配置してます

sample = 画像アップロードの機能のみを実装
※flask環境をインストールが必要

sample_r2 = アップロードした画像のOCRを実装
※pythonのAzureパッケージのインストールが必要

sample_r3 = r2に生成AIを加え、OCRの文字の整えや要約を実装　（確認未）
※Pytorchとtransformersのが必要
calm2-7b-chatのモデルが必要なので、事前に取得し配置する必要があり