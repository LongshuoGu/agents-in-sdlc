---
slug: ja-jp/real-world-development
title: "実践的な開発"
authors:
  - geektrainer
lastUpdated: 2026-09-16
---

現実的なシナリオ、完成したアプリケーション、共有バックログを使って、ソフトウェア開発ライフサイクル全体で GitHub Copilot を活用します。変更を計画し、コードを作成し、動作をテストし、プルリクエストをレビューし、エージェントと作業を管理する方法を反復的に学びます。

## シナリオ

架空の企業 Tailspin Toys に新しく加わった開発者として取り組みます。この企業は開発者をテーマにしたボードゲームのクラウドファンディングを提供しています。チームのバックログは GitHub イシューとして登録済みで、すぐに着手できます。フィルタリングやページネーションなどの機能開発に加えて、アクセシビリティやコーディング標準などの品質改善も含まれています。

## 作業環境を選ぶ

GitHub Copilot は、どこで作業していても利用できます。開発方法に合った環境を選択してください。各ワークショップでは個別にセットアップし、共通の Tailspin Toys シナリオを使用します。

### [GitHub Copilot CLI][cli]

ターミナルでエージェント型アシスタントを使用します。Plan モードと Autopilot モード、指示、スキル、カスタム エージェント、Playwright MCP、Agent Merge、便利なスラッシュ コマンドを使って作業します。

### [GitHub Copilot アプリ][app]

エージェント セッションを並行して実行し、セッション モードを切り替え、Canvas で共同作業し、デスクトップ アプリで GitHub のイシューとプルリクエストを管理します。

### [GitHub Copilot クラウド エージェント][cloud]

GitHub イシューを非同期エージェントに割り当て、その作業を案内して進捗を監視し、エージェントが作成したプルリクエストをレビューします。

### [Visual Studio Code][vscode]

Visual Studio Code と GitHub Codespaces で GitHub Copilot を使用します。エディターを離れずに、Copilot Chat のエージェント モード、MCP サーバー、カスタム エージェントを利用します。

[cli]: cli/
[app]: app/
[cloud]: cloud/
[vscode]: vscode/
