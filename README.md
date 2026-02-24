# Portfolio

このページでは、個人開発で制作した **WPF レベルエディタ** と **Unreal Engine 5 ゲーム** を公開しています。  
詳細は各リポジトリの README をご参照ください。

---

## 🎨 WPF Level Editor

**Repository:** [wpf-level-editor](https://github.com/h-takahashi1228/wpf-level-editor)  
**制作期間:** 約1ヶ月  
**担当:** 個人制作

WPF を用いて制作した 3D グリッドベースのレベルエディタです。  
プランナーがレベルを構築し、データを Houdini → Unreal Engine へ連携することを想定して設計しました。

**特徴:**
- 3D Viewport 上でのブロック・オブジェクトの配置 / 編集 / 削除
- Undo / Redo 機能
- JSON 形式での Import / Export
- Houdini 用 CSV への変換機能（Python スクリプト）

※UE での最終利用は未実装ですが、  
WPF → Houdini → UE という **ツールパイプライン理解を目的**に制作。

---

## 🎮 SET – Solo Time Attack (Unreal Engine 5)

**Repository:** [SET-solo-time-attack](https://github.com/h-takahashi1228/SET)  
**制作期間:** 約1ヶ月  
**担当:** 個人制作

ボードゲーム「SET」を題材にした一人用タイムアタックゲームです。  
場にあるカードから SET（正しい組み合わせ3枚）を見つけ続け、組み合わせがなくなるまでの時間を競います。

**特徴:**
- Blueprint のみでゲームロジックを構築
- カード自動生成 (Python スクリプト)
- ローカルランキング機能
- 初回プレイ時にチュートリアル表示

---

## Contact
- Email: shall.marching@gmail.com
