# 資格取得計画提案ソリューション

以下は資格取得ソリューションのデモ動画です。

https://github.com/geekfujiwara/GenerateCompetencyPlanPowerApps/assets/96101315/91d1cf29-834c-4fe0-80fc-84e3f2ad9fa1

## 主要機能のご紹介

### キャンバスアプリ

簡単に資格、期間、受験者のレベルを選択するだけで、資格取得計画を生成AIが立案し、資格取得日をOutlookに登録することができます。

![image](https://github.com/geekfujiwara/GenerateCompetencyPlanPowerApps/assets/96101315/f733cb66-66c8-42cf-bcea-94b45b1c01f7)

### モデル駆動型アプリ

また、その生成した計画を一覧することができます。

#### ビュー

![image](https://github.com/geekfujiwara/GenerateCompetencyPlanPowerApps/assets/96101315/95959c11-756c-4644-a65e-6ac01d96ec40)

#### フォーム

![image](https://github.com/geekfujiwara/GenerateCompetencyPlanPowerApps/assets/96101315/c14061cd-94ff-46bf-a75c-d1a5d1c69061)

### Power Automate 

資格取得日が近づいたら、自動的に本人にリマインドされます。

![image](https://github.com/geekfujiwara/GenerateCompetencyPlanPowerApps/assets/96101315/4869fd19-e0a6-46d1-b4ef-13d03a744b73)

何日前にリマインドするのかは[環境変数](https://learn.microsoft.com/ja-jp/power-apps/maker/data-platform/environmentvariables)で設定することができます。

![image](https://github.com/geekfujiwara/GenerateCompetencyPlanPowerApps/assets/96101315/e2878ca6-8fa6-4b98-9daa-fac4928070a1)


## アーキテクチャ

仕組みとしては以下のコンポーネントが使われています。

![image](https://github.com/geekfujiwara/GenerateCompetencyPlanPowerApps/assets/96101315/b396e5fc-3ec9-4f64-b91c-f4d838e4532a)

## 前提条件

### 環境

環境にはDataverseが必要です。

### ライセンス

Power Apps Premium ライセンスが必要です。

## インポート手順

### 公式手順

[Microsoft 公式サイト](https://learn.microsoft.com/ja-jp/power-apps/maker/data-platform/import-update-export-solutions)にもソリューションのインポート方法が説明があります。

## ソリューションのインポート方法

### ソリューションの取得

[ソリューションはリリース](https://github.com/geekfujiwara/GenerateCompetencyPlanPowerApps/releases)から入手することができます。

### インポート手順


ソリューションをアップロードしてインポートします。

![image](https://github.com/geekfujiwara/GenerateCompetencyPlanPowerApps/assets/96101315/cc07158c-2cf2-47b8-a9c6-42ebca992536)


接続を作成します。

![image](https://github.com/geekfujiwara/GenerateCompetencyPlanPowerApps/assets/96101315/0b5dc8f7-d7e3-497b-9da2-9e0b10e26eb0)


資格を取得予定日に対して何日前にリマインドするかを環境変数で設定することができます。

![image](https://github.com/geekfujiwara/GenerateCompetencyPlanPowerApps/assets/96101315/bc1e6b11-5181-41ed-9965-d281200e2913)

インポートを実施します。



