<!-- ELUCENIA technical documentation · superficie-corporal · ja · no clinical/professional/rights approval -->

# 体表面積・BMI

[条件・出典・許諾](https://elucenia.org/ja/tools/superficie-corporal)

## 使い方

ポータルでツールを使用するか、ローカルHTTPサーバー経由でindex.htmlを開いてください。言語を選択し、項目を入力して計算してください。

## 入力項目と単位

### 体重

`peso`

kg · 範囲: 2–350

### 身長

`altura`

cm · 範囲: 40–240

## 方法の版

Mosteller 1987 √(cm×kg/3600)、DuBois 1916係数0.007184・指数0.425/0.725、BMI別計算

## 記載された計算式

Mosteller: 体表面積 (m²) = √(身長 \[cm\] × 体重 \[kg\] ÷ 3600)

DuBois: 体表面積 (m²) = 0.007184 × 体重0.425 × 身長0.725

BMI = 体重 ÷ 身長² (m)

## 限界・対象集団

身長はcm、体重はkgで入力してください。結果はm²単位の推定体表面積で、BMIとは異なります。MostellerとDu Boisは異なる式であり、体表面の直接測定ではありません。引用したASCO2012ガイドラインは、肥満の成人がん患者における細胞傷害性化学療法の用量を扱い、その版の新規分子標的薬は対象にしていません。体表面積の計算だけで用量、面積上限、適応は決まりません。特定のプロトコルと薬剤に従い、この参考から普遍的な上限を推論しないでください。

## 参考文献

- [Mosteller RD. Simplified calculation of body-surface area. N Engl J Med, 1987.](https://doi.org/10.1056/NEJM198710223171717)

- [Griggs JJ et al. Appropriate chemotherapy dosing for obese adult patients with cancer: American Society of Clinical Oncology clinical practice guideline. J Clin Oncol, 2012.](https://doi.org/10.1200/JCO.2011.39.9436)

- [Lang RM et al. Recommendations for cardiac chamber quantification by echocardiography in adults (ASE/EACVI). J Am Soc Echocardiogr, 2015.](https://doi.org/10.1016/j.echo.2014.10.003)

## 技術テストの再現

このリポジトリのルートディレクトリでnode test.cjsを実行すると、記録された合成ケースを再実行できます。元の入力、期待結果、許容誤差は保持されています。技術テストは臨床的検証を意味しません。

```sh
node test.cjs
```

tool.jsonには出典、版、確認範囲が記録されています。examples.jsonには合成入力と期待結果が保持され、results.jsonには実際に得られた結果が記録されています。

[記録・参考文献](../tool.json) · [JavaScriptコード](../calculator.js) · [参照ケース](../examples.json) · [results.json](../results.json)

## 確認状況と使用条件

独立した臨床レビューは実施されていません。

このインターフェースは独自に作成した翻訳であり、公式版や認証済みの版ではありません。独立した臨床レビュー、専門家による言語レビュー、評価尺度等の権利許諾の確認は実施されていません。

式または分類の結果です。解釈、対応、適用可能性は専門家による評価と選択した出典に依存します。

## ライセンスと帰属表示

Apache-2.0はELUCENIAのコードにのみ適用されます。評価尺度等、出版物、翻訳、データの権利は、それぞれの権利者に帰属します。LICENSEとNOTICEを保持してください。

ELUCENIA · Felipe Guedes · Copyright © 2026

## 記録された結果

以下の情報は、合成例に対する手法の出力を保持したものです。独立した臨床的検証を示すものではありません。

### 1

BMI 24.2 kg/m²：標準体重

| 結果の詳細 | |
| --- | --- |
| DuBois | 1.81 m² |
| 体格指数（BMI） | 24.2 kg/m² |


### 2

BMI 19.5 kg/m²：標準体重

| 結果の詳細 | |
| --- | --- |
| DuBois | 1.50 m² |
| 体格指数（BMI） | 19.5 kg/m² |

