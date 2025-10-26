# TIL (Today I Learned) about Salesforce

> [!NOTE]
> TIL(Today I Learned)
>
>  - summarized-TIL : dairy-TILを要約したファイル
>  - dairy-TIL : 日々の学んだことのファイル

## 目次

<details>
<summary>目次を開く</summary>

- [TIL (Today I Learned) about Salesforce](#til-today-i-learned-about-salesforce)
  - [目次](#目次)
  - [TILs](#tils)
    - [Salesforce基礎知識](#salesforce基礎知識)
      - [認定資格](#認定資格)
      - [開発フレームワーク](#開発フレームワーク)
    - [組織設定](#組織設定)
      - [基本設定](#基本設定)
    - [ユーザー管理](#ユーザー管理)
      - [ライセンス管理](#ライセンス管理)
      - [ユーザー作成と設定](#ユーザー作成と設定)
      - [ユーザー無効化と凍結](#ユーザー無効化と凍結)
      - [トラブルシューティング](#トラブルシューティング)
    - [セキュリティ](#セキュリティ)
      - [アクセス制御](#アクセス制御)
    - [外部ユーザー](#外部ユーザー)
      - [カスタマーユーザー](#カスタマーユーザー)
    - [データモデル](#データモデル)
      - [標準オブジェクト](#標準オブジェクト)
      - [サービス機能](#サービス機能)
    - [Lightning Experience](#lightning-experience)
      - [アプリケーション管理](#アプリケーション管理)

</details>

---

## TILs

### Salesforce基礎知識

#### 認定資格

##### What

- **[2025.08.12.08.53] Salesforce Administrator認定資格とは** - [daily/2025.08.12.08.53_what_salesforce_administrator_certificate.md](daily/2025.08.12.08.53_what_salesforce_administrator_certificate.md)
  - Salesforce Administrator認定資格の概要、試験範囲、学習方法について

#### 開発フレームワーク

##### What

- **[2025.08.12.08.57] Salesforce Visualforceとは** - [daily/2025.08.12.08.57_what_salesforce_visualforce.md](daily/2025.08.12.08.57_what_salesforce_visualforce.md)
  - Visualforceフレームワークの基本概念、コンポーネント、使用方法について

- **[2025.08.12.09.09] Salesforce Apexとは** - [daily/2025.08.12.09.09_what_salesforce_apex.md](daily/2025.08.12.09.09_what_salesforce_apex.md)
  - Apexプログラミング言語の特徴、構文、ベストプラクティスについて

### 組織設定

#### 基本設定

##### What

- **[2025.08.12.19.34] Salesforceの組織情報で設定できる項目** - [daily/2025.08.12.19.34_what_salesforce_organization_information_settings.md](daily/2025.08.12.19.34_what_salesforce_organization_information_settings.md)
  - Salesforce組織の基本情報設定項目と設定方法について

- **[2025.08.12.19.54] Salesforceのロケール設定パラメータとは** - [daily/2025.08.12.19.54_what_salesforce_locale_settings_parameters.md](daily/2025.08.12.19.54_what_salesforce_locale_settings_parameters.md)
  - ロケール設定のパラメータと多言語対応について

- **[2025.08.12.20.05] Salesforceのリストビュー編集UI設定とは** - [daily/2025.08.12.20.05_what_salesforce_listview_edit_ui_settings.md](daily/2025.08.12.20.05_what_salesforce_listview_edit_ui_settings.md)
  - リストビューの編集とUI設定のカスタマイズ方法について

### ユーザー管理

#### ライセンス管理

##### How

- **[2025.08.12.20.12] Service Cloudユーザーライセンスの割り当て方法** - [daily/2025.08.12.20.12_how_assign_service_cloud_user_license_salesforce.md](daily/2025.08.12.20.12_how_assign_service_cloud_user_license_salesforce.md)
  - Service Cloudユーザーライセンスの割り当て手順について

- **[2025.08.12.20.56] 退職者のユーザーライセンスの処理方法** - [daily/2025.08.12.20.56_how_handle_retired_user_license_salesforce.md](daily/2025.08.12.20.56_how_handle_retired_user_license_salesforce.md)
  - 退職者のユーザーライセンスの適切な処理方法について

#### ユーザー作成と設定

##### What

- **[2025.08.12.20.19] 本番環境でユーザーを作成する際の考慮事項** - [daily/2025.08.12.20.19_what_consider_creating_user_production_salesforce.md](daily/2025.08.12.20.19_what_consider_creating_user_production_salesforce.md)
  - 本番環境でユーザーを作成する際の注意点について

- **[2025.08.12.20.23] Salesforceのユーザー名の考慮事項** - [daily/2025.08.12.20.23_what_salesforce_username_considerations_production.md](daily/2025.08.12.20.23_what_salesforce_username_considerations_production.md)
  - ユーザー名設定のベストプラクティスと制約について

#### ユーザー無効化と凍結

##### What

- **[2025.08.12.20.47] ユーザーの無効化と凍結の違い** - [daily/2025.08.12.20.47_what_difference_deactivate_freeze_user_salesforce.md](daily/2025.08.12.20.47_what_difference_deactivate_freeze_user_salesforce.md)
  - ユーザーの無効化と凍結の機能的違いと使い分けについて

##### How

- **[2025.08.12.20.44] 休日期間中の社員ログインを防止する方法** - [daily/2025.08.12.20.44_how_prevent_employee_login_during_holiday_salesforce.md](daily/2025.08.12.20.44_how_prevent_employee_login_during_holiday_salesforce.md)
  - 休暇期間中の社員ログインを一時的に制限する方法について

#### トラブルシューティング

##### How

- **[2025.08.12.20.37] 新規ユーザーのログインエラーのトラブルシューティング** - [daily/2025.08.12.20.37_how_troubleshoot_salesforce_new_user_login_error.md](daily/2025.08.12.20.37_how_troubleshoot_salesforce_new_user_login_error.md)
  - 新規ユーザーのログインエラー解決方法について

- **[2025.08.12.21.32] ユーザーを無効化できない場合のトラブルシューティング** - [daily/2025.08.12.21.32_how_troubleshoot_cannot_deactivate_user_salesforce.md](daily/2025.08.12.21.32_how_troubleshoot_cannot_deactivate_user_salesforce.md)
  - ユーザーを無効化できない場合の原因と解決策について

### セキュリティ

#### アクセス制御

##### What

- **[2025.08.12.21.05] ネットワークアクセスIPレンジのメリット** - [daily/2025.08.12.21.05_what_benefits_network_access_ip_range_salesforce.md](daily/2025.08.12.21.05_what_benefits_network_access_ip_range_salesforce.md)
  - ネットワークアクセスIPレンジ制限のメリットと設定方法について

##### How

- **[2025.08.12.21.13] 特定ユーザーのパスワード有効期限の設定方法** - [daily/2025.08.12.21.13_how_set_password_expiration_specific_user_salesforce.md](daily/2025.08.12.21.13_how_set_password_expiration_specific_user_salesforce.md)
  - 特定ユーザーのパスワード有効期限設定方法について

- **[2025.08.12.21.19] 役員のみがレポートを閲覧できるようにする制限方法** - [daily/2025.08.12.21.19_how_restrict_report_viewing_executive_only_salesforce.md](daily/2025.08.12.21.19_how_restrict_report_viewing_executive_only_salesforce.md)
  - 役員のみがレポートを閲覧できるようにする制限方法について

### 外部ユーザー

#### カスタマーユーザー

##### What

- **[2025.08.12.21.50] カスタマーユーザーアカウントとは** - [daily/2025.08.12.21.50_what_customeruser_account_salesforce.md](daily/2025.08.12.21.50_what_customeruser_account_salesforce.md)
  - カスタマーユーザーアカウントの概要と用途について

##### Why

- **[2025.08.12.21.46] カスタマーユーザーアカウントを無効化できない理由** - [daily/2025.08.12.21.46_why_cannot_disable_customeruser_account_salesforce.md](daily/2025.08.12.21.46_why_cannot_disable_customeruser_account_salesforce.md)
  - カスタマーユーザーアカウントを無効化できない理由について

### データモデル

#### 標準オブジェクト

##### What

- **[2025.08.12.22.03] Salesforceの標準オブジェクトとレコード種別** - [daily/2025.08.12.22.03_what_salesforce_standard_objects_by_records.md](daily/2025.08.12.22.03_what_salesforce_standard_objects_by_records.md)
  - Salesforceの標準オブジェクトとレコード種別の詳細について

- **[2025.08.12.22.09] Salesforceのキャンペーン関連オブジェクト** - [daily/2025.08.12.22.09_what_salesforce_campaign_related_objects.md](daily/2025.08.12.22.09_what_salesforce_campaign_related_objects.md)
  - キャンペーンオブジェクトとその関連オブジェクトの構造について

##### How

- **[2025.08.12.22.25] Salesforceオブジェクト間の関連性を理解する方法** - [daily/2025.08.12.22.25_how_salesforce_objects_relate_each_other.md](daily/2025.08.12.22.25_how_salesforce_objects_relate_each_other.md)
  - Salesforceオブジェクト間の関連性と関係図について

#### サービス機能

##### What

- **[2025.08.12.21.54] Salesforceのケースチームとは** - [daily/2025.08.12.21.54_what_salesforce_case_team.md](daily/2025.08.12.21.54_what_salesforce_case_team.md)
  - ケースチーム機能の概要と複数ユーザーでの協力体制について

### Lightning Experience

#### アプリケーション管理

##### How

- **[2025.08.12.22.34] App LauncherとLightning App Builderの違いを理解する方法** - [daily/2025.08.12.22.34_how_different_app_launcher_lightning_app_builder_salesforce.md](daily/2025.08.12.22.34_how_different_app_launcher_lightning_app_builder_salesforce.md)
  - App LauncherとLightning App Builderの違いと使い分けについて
