# 業務改善ポートフォリオ
事務職として働きながら、社内DXを推進しています。
以下、ツール開発実績です。

- [営業成績管理アプリ](https://house-dog.github.io/project-sales-app/)
- [KPI管理ダッシュボード](https://house-dog.github.io/project-kpi-dashboard/)
- [家電見積りシミュレーター](https://house-dog.github.io/project-simulator/)
- [休暇管理・申請システム](https://house-dog.github.io/Leave-Management-System/)
- [LINE通知システム](https://house-dog.github.io/project-line-system/)


## 開発実績
### 1. 営業成績管理アプリ
- 概要：営業成績をスプレッドシートではなくWebアプリで集計・管理。
- 使用技術：GAS, Firebase, HTML/CSS
- 成果：集計時間を月間10時間削減。リアルタイムで進捗可視化を実現。

| 画面1 | 画面2 |
| :---: | :---: |
| <img src="https://github.com/user-attachments/assets/5b3e3ee1-9e91-46e0-8c52-e1c018070fd1" width="250"> | <img src="https://github.com/user-attachments/assets/898c537a-0dab-44e8-8714-093751c60f2c" width="250"> |
| **画面3** | **画面4** |
| <img src="https://github.com/user-attachments/assets/ba8132ff-a026-4c80-a2b9-71a5ed772899" width="250"> | <img src="https://github.com/user-attachments/assets/5d262bb0-ffaa-43e4-b746-e95e1bcd6ea7" width="250"> |
| **画面5** | **画面6** |
| <img src="https://github.com/user-attachments/assets/52d6cb09-f9f7-4d5e-b00c-8654463899bb" width="250"> | <img src="https://github.com/user-attachments/assets/f8a3f779-210c-4a1e-9b9c-ad04cc6dc47b" width="250"> |

### 2. KPI管理ダッシュボード
- 概要：複雑な指標を直感的に把握するため、複数のスプレッドシートからデータを自動抽出し、リアルタイムで可視化するダッシュボードを開発。
- 使用技術：GAS, HTML/CSS, Google Sheets API
- 成果：工数削減： 手作業で行っていた週次レポート作成業務を自動化し、担当者の作業時間を月間10時間削減。
- 即時性の向上： 月次更新だった指標をリアルタイム更新に変更し、経営判断のスピードアップに貢献。
- UI/UX： 非エンジニアでも直感的に操作できるよう、ダッシュボードの配色とレイアウトを簡素化。

| 月次表示 | 自由入力欄 |
| :---: | :---: |
| <img src="https://github.com/user-attachments/assets/62b87f45-c3d4-45ca-a123-f33bad08d961" width="200"> | <img src="https://github.com/user-attachments/assets/68d63b16-91ba-4835-bb62-c63574e0c074" width="200"> |
| **個人別日報一覧** | **翌週目標入力欄** |
| <img src="https://github.com/user-attachments/assets/2ba8c451-ff33-4d66-95f1-2422f2505705" width="200"> | <img src="https://github.com/user-attachments/assets/a4ae2394-2ca2-4456-a8d2-ac9329644234" width="200"> |

### 3. 家電見積りシミュレーター
- 概要：複雑な家電の組み合わせやオプション選択をWeb上で完結させ、その場で概算見積りを確認できるシミュレーター。
- 使用技術：GAS, HTML/CSS, JavaScript
- 成果・工夫した点：  
  ・顧客満足度の向上： 従来は担当者が後日提出していた見積りを即時回答可能にし、顧客の検討スピードを向上。  
  ・問い合わせ精度向上：事前見積導入により、購入意欲の高いお客様への対応効率を向上。   
  ・保守性への配慮：商品価格の変動が頻繁にあるため、価格データをスプレッドシート上で管理し、コードを修正せずに更新できる仕組みを構築。  
  
| 画面1 | 画面2 |
| :---: | :---: |
| <img src="https://github.com/user-attachments/assets/bbe563a7-de20-4618-b201-b9309d76619f" width="250"> | <img src="https://github.com/user-attachments/assets/4de4f9d2-11d8-4ee4-a49a-54d7bdf368fa" width="250"> |
| **画面3** | **画面4** |
| <img src="https://github.com/user-attachments/assets/220543b6-8aa5-48c2-a7ba-229c16b45245" width="250"> | <img src="https://github.com/user-attachments/assets/a80335f9-a1fb-4829-becc-6ed69acfb137" width="250"> |
| **画面5** | **画面6** |
| <img src="https://github.com/user-attachments/assets/afe8e1ff-bb72-41a1-b4e9-ac3e2aaf3829" width="250"> | <img src="https://github.com/user-attachments/assets/d24b6ff7-613d-42fd-b0e2-6e108fa3e5e5" width="250"> |

### 4. 休暇管理・申請システム
- 概要：LINEや口頭、スプレッドシートで手動で管理されていた休暇申請・承認フローをWebアプリ化。申請者・承認者双方の工数を削減し、情報の透明化を実現。
- 主な機能：カレンダーUIによる休暇取得状況のリアルタイム確認。申請内容の自動集計と、管理者へのLINE通知。
- 使用技術：GAS, HTML/CSS/JavaScript, Google Sheets
- 成果・工夫した点：  
  ・事務作業の効率化：申請後のシート転記や集計作業を完全に自動化し、管理者の集計ミス・手間をゼロに。  
  ・透明性の向上：チーム全体で誰がいつ休むかを共有しやすくし、業務の属人化を防ぐ環境を構築。  
  ・ユーザビリティの追求：スマホからでも3タップで完了できるUIを採用。  

| 画面1 | 画面2 |
| :---: | :---: |
| <img src="https://github.com/user-attachments/assets/46e429c1-6f1d-4b0c-9cc0-26fdb89df1b1" width="250"> | <img src="https://github.com/user-attachments/assets/8b08227d-2360-4272-b34d-574ba9d96feb" width="250"> |
| **画面3** |
| <img src="https://github.com/user-attachments/assets/cac1c8cd-b93a-4551-b9f7-2da4018201c7" width="250">

### 5. LINE自動通知システム
- 概要：予約の問い合わせを自動で社内LINEへ通知。
- 使用技術：GAS, LINE Messaging API, Googleフォーム
- 成果：手動で文章を作成していた時間を削減。顧客情報やメニュー内容・料金などの誤入力を阻止。
<img src="https://github.com/user-attachments/assets/e5dce9c3-5c3d-403b-a386-6d847ee179f5" style="width: 100%; max-width: 500px; border-radius: 8px;">
