![R](https://img.shields.io/badge/R-276DC3?logo=r&logoColor=white)
![Quarto](https://img.shields.io/badge/Quarto-39729E?logo=quarto&logoColor=white)
![License: MIT](https://img.shields.io/badge/License-MIT-green)

# Diamond Price Prediction using Statistical and Machine Learning Models

A reproducible predictive modelling workflow using **R** to estimate diamond prices through exploratory data analysis, feature engineering, multiple linear regression, Random Forest, and model evaluation.

### Full Report

https://reinasdatastudio.github.io/diamond-price-prediction/diamonds-price-prediction.html

## Overview

This project investigates the factors that influence diamond prices using the **ggplot2 Diamonds** dataset containing approximately **54,000 observations**.

The objective was to develop predictive models capable of estimating diamond prices while comparing the strengths and limitations of traditional statistical modelling and machine learning approaches. The workflow includes data cleaning, feature engineering, exploratory data analysis, predictive modelling, model diagnostics, and evaluation.

## Key Features

* Reproducible predictive modelling workflow using Quarto
* Data cleaning and feature engineering
* Exploratory Data Analysis (EDA)
* Correlation analysis
* Multiple Linear Regression
* Random Forest Regression
* Model comparison and diagnostics

## Technologies

* R
* tidyverse
* ggplot2
* ranger
* Quarto

## Repository Structure

- diamonds-price-prediction.qmd
- README.md

## Results

The project compares Multiple Linear Regression and Random Forest models for predicting diamond prices.

The analysis demonstrates that **carat** is the strongest predictor of price, while cut, colour, and clarity further improve predictive performance. Although the linear regression model achieved excellent explanatory power, diagnostic evaluation revealed violations of model assumptions for high-value diamonds. Random Forest provided improved predictive accuracy by capturing non-linear relationships within the data.

## Disclaimer

This project uses the publicly available **ggplot2 Diamonds** dataset for educational purposes. The analysis demonstrates reproducible statistical and machine learning workflows for predictive modelling.

## Author

**Reina Kaino**

Former Pharmacist | Data Scientist | System Engineer

**Website**
https://reinasdatastudio.github.io/webpage/

&ensp;

---

&ensp;

# 回帰分析および機械学習を用いたダイヤモンド価格予測

## 概要

本プロジェクトでは、**ggplot2 Diamonds**データセットを用いて、ダイヤモンド価格を予測するモデルを構築しました。

データ前処理、特徴量エンジニアリング、探索的データ解析（EDA）、重回帰分析、Random Forestによる機械学習、モデル評価までを、**R**と**Quarto**を用いて再現可能なワークフローとして実装しています。

### レポート

https://reinasdatastudio.github.io/diamond-price-prediction/diamonds-price-prediction.html

## 主な内容

* Quartoを用いた再現可能な解析ワークフロー
* データクリーニング・特徴量エンジニアリング
* 探索的データ解析（EDA）
* 相関分析
* 重回帰分析
* Random Forest
* モデル比較・性能評価

## 使用技術

* R
* tidyverse
* ggplot2
* ranger
* Quarto
  
## ディレクトリ構成

- diamonds-price-prediction.qmd
- README.md

## 解析結果

重回帰分析とRandom Forestを比較した結果、**カラット数**が価格に最も大きく影響する要因であることが確認されました。また、カット、カラー、クラリティを組み合わせることで予測性能が向上しました。

重回帰分析は高い説明力を示した一方で、高価格帯ではモデル仮定を満たさない傾向が見られました。Random Forestは非線形な関係を捉えることで、より高い予測性能を示しました。

## 注意事項

本プロジェクトでは、教育目的で公開されている**ggplot2 Diamonds**データセットを使用しています。解析内容は、統計解析および機械学習による予測モデリング手法を学習・実践することを目的としています。

## 作成者

**戒能 伶奈**

元薬剤師｜データサイエンティスト

**Website**
https://reinasdatastudio.github.io/webpage/
