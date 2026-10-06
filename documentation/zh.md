<!-- ELUCENIA technical documentation · superficie-corporal · zh · no clinical/professional/rights approval -->

# 体表面积与 BMI

[条件、来源与许可](https://elucenia.org/zh/tools/superficie-corporal)

## 使用方法

在门户中使用工具，或通过本地 HTTP 服务器打开 index.html。选择语言，填写各字段，然后计算。

## 输入与单位

### 体重

`peso`

kg · 范围: 2–350

### 身高

`altura`

cm · 范围: 40–240

## 方法版本

Mosteller 1987 √(cm×kg/3600)；DuBois 1916系数0.007184、幂0.425/0.725；BMI另计

## 已记录的公式

Mosteller: 体表面积 (m²) = √(身高 \[cm\] × 体重 \[kg\] ÷ 3600)

DuBois: 体表面积 (m²) = 0.007184 × 体重0.425 × 身高0.725

BMI = 体重 ÷ 身高² (m)

## 限制与适用人群

请输入身高cm和体重kg；结果是以m²表示的体表面积估计值，与BMI不同。Mosteller和Du Bois是不同公式，并非对体表的直接测量。所引ASCO2012指南针对肥胖成年癌症患者的细胞毒性化疗剂量，不包括该版本中的新型靶向药物。计算体表面积不能决定剂量、体表面积上限或适应证：决策必须遵循特定方案和药物，不能由该参考推导普遍限制。

## 参考文献

- [Mosteller RD. Simplified calculation of body-surface area. N Engl J Med, 1987.](https://doi.org/10.1056/NEJM198710223171717)

- [Griggs JJ et al. Appropriate chemotherapy dosing for obese adult patients with cancer: American Society of Clinical Oncology clinical practice guideline. J Clin Oncol, 2012.](https://doi.org/10.1200/JCO.2011.39.9436)

- [Lang RM et al. Recommendations for cardiac chamber quantification by echocardiography in adults (ASE/EACVI). J Am Soc Echocardiogr, 2015.](https://doi.org/10.1016/j.echo.2014.10.003)

## 复现技术测试

在此仓库的根目录中运行 node test.cjs，以重复已记录的合成案例。原始输入、预期结果和容差保持不变。技术测试不构成临床验证。

```sh
node test.cjs
```

tool.json 包含来源、版本和审查范围。examples.json 保留合成输入与预期结果；results.json 记录实际得到的结果。

[记录与参考文献](../tool.json) · [JavaScript代码](../calculator.js) · [参考案例](../examples.json) · [results.json](../results.json)

## 审查与使用条件

尚未开展独立临床审查。

此界面为自主编写的翻译，并非官方或认证版本。尚未完成独立临床审查、专业语言审查或工具权利授权。

公式或分类结果。解释、处理及适用性须结合专业评估和所选来源。

## 许可与署名

Apache-2.0 仅适用于 ELUCENIA 代码。工具、出版物、翻译和数据的权利仍归各自权利人所有。请保留 LICENSE 和 NOTICE。

ELUCENIA · Felipe Guedes · Copyright © 2026

## 已记录的结果

以下信息保留该方法对合成示例的输出，不构成独立的临床验证。

### 1

BMI 24.2 kg/m²：正常体重

| 结果详情 | |
| --- | --- |
| DuBois | 1.81 m² |
| 体质指数（BMI） | 24.2 kg/m² |


### 2

BMI 19.5 kg/m²：正常体重

| 结果详情 | |
| --- | --- |
| DuBois | 1.50 m² |
| 体质指数（BMI） | 19.5 kg/m² |

