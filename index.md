---
title: title
layout: report
---

# 数理計画問題

目的関数
: $f(\boldsymbol{x}) \to$ 最小

制約条件
: $\boldsymbol{x} \in S$

$\boldsymbol{x}$を**実行可能解**、$S$を**実行可能領域**という。
実行可能界の中で目的関数が最小(最大)のものを**最適解**という。

- 生産計画問題
- 多期間計画問題
- 輸送問題
- 最短路問題
- 最大流問題・最小費用流問題
- ポートフォリオ選択問題
- 交通流割当問題
- ナップサック問題

# 線形計画問題

## 標準形

目的関数
: $\boldsymbol{c}^{\mathrm{T}} \boldsymbol{x} \to $ 最小

制約条件
: $A\boldsymbol{x} = \boldsymbol{b}, \boldsymbol{x} \geqq \boldsymbol{0}$

**非負変数**と**スラック変数**を用いて標準化する。

## 基底解と最適解

基底解
: $\boldsymbol{x}$

実行可能基底解
: $\boldsymbol{x} (\boldsymbol{x} \geqq 0)$

基底変数
: $\boldsymbol{x_B} = B^{-1} \boldsymbol{b}$

非基底変数
: $\boldsymbol{x_N}$

シンプレックス乗数
: $\boldsymbol{\pi}$

相対コスト係数
: $\boldsymbol{c}^{\mathrm{T}}_{N} - \boldsymbol{\pi}^{\mathrm{T}}N$

## 双対問題

主問題
: $\boldsymbol{c}^{\mathrm{T}} \boldsymbol{x} \to$ 最小
: $A\boldsymbol{x} = \boldsymbol{b}, \boldsymbol{x} \geqq \boldsymbol{0}$

双対問題
: $\boldsymbol{b}^{\mathrm{T}} \boldsymbol{\omega} \to$ 最大
: $A^{\mathrm{T}}\boldsymbol{\omega} \leqq \boldsymbol{c}$