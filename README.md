# transE_project

關聯網路實作_by_transE

# TransE-Pytorch-Implementation
Simple implementation of transe framework based on pytorch

This repository draws on [LYuhang/Trans-Implementation](https://github.com/LYuhang/Trans-Implementation)

build data preprocessing, dataset construction, negative samples generation, model training, MR verification, model preservation functions.

基於pytorch的TransE模型輕量實現方法

本倉庫的方法借鑒了[LYuhang/Trans-Implementation](https://github.com/LYuhang/Trans-Implementation) 中的TransE模型構建，訓練過程。對整個流程進行大量精簡和重構，優化了數據輸入和處理過程，為自建數據集的構建提供基類和基本方法。對入門更為友好，另外新增模型輸出端口及新增None值簡易處理方法，用以預測及計算成效。

## 環境配置

- pytorch
- numpy
- pickle

## 運行

默認使用`FB15k-237`數據集，其他數據集可以直接放到dataset文件夾中，然後在train.py文件中