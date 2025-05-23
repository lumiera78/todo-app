# ✅ TODOアプリケーション

Spring Boot + Thymeleaf + MyBatis を使って作成した、シンプルで実用的なタスク管理アプリケーションです。  
タスクの登録・一覧表示・編集・削除に加えて、キーワード検索・状態別フィルター・バリデーション・エラー画面などの基本機能を網羅しています。

---

## 🚀 ポートフォリオ

- Notionポートフォリオ: https://tourmaline-vulture-4b0.notion.site/TODO-1f95c2a3e86180c7ad45d0d4f43e2fd1

---

## 🛠 使用技術

- **Java 17**
- **Spring Boot 3.1.2**
- **Thymeleaf**
- **Thymeleaf Layout Dialect**
- **MyBatis 3.0.2**
- **H2 Database**（インメモリDB）
- **Bootstrap 5**（WebJars）
- **Lombok**
- **Gradle**

---

## ✨ 主な機能

- ✅ タスクのCRUD（作成・表示・編集・削除）
- 🔍 タスクの検索（キーワード・状態フィルター）
- 📋 ステータス管理（TODO / DOING / DONE）
- ✅ 入力バリデーション（サーバー側）
- ⚠️ カスタム404・汎用エラーページ
- 🎨 レイアウトテンプレートによる共通デザイン
- 🚀 Devtoolsによるホットリロード開発


---

## 🔧 起動方法

以下の手順でローカル実行可能です：

```bash
git clone https://github.com/yourname/todo-app.git
cd todo-app
./gradlew bootRun
起動後、http://localhost:8080/ にアクセス