# tmhiroak

バックオフィスの AI 活用推進を本業にしています。日々の仕事で感じた不便や非効率を、Claude Code を使った個人開発のプロダクトで解決しています。

## いま作っているもの

### 🎣 [Nabrahunt](https://nabrahunt.com)（招待制ベータ）
電車・フェリーで行く釣行のための計画ツール。天候・風・波浪・潮汐に加え、電車経路と離島フェリーの欠航まで一つの正規化データ層に束ね、「そこへ辿り着けて、かつ釣りになるか」を判定する。Web / API / CLI / MCP の4つの口を持つ。

### ⏱ jete（稼働中・非公開）
cron + GitHub Actions の置き換えを狙う、セルフホスト型のジョブスケジューラ。Go 製の単一バイナリ。停止中に逃した実行の追いつき、ジョブ連鎖、承認ゲートなど。CLI・REST API・MCP サーバを備え、スクリプトや LLM エージェントからも操作できる。VPS 上で実運用している。

### 🔐 Encrault（開発中・非公開）
.env / API キーを一か所の Vault に置き、プロジェクト・環境・配布先を参照で結ぶデスクトップアプリ。Cloudflare・VPS・GCP への配布までを一つの操作で行う。

### 📈 自動売買システム（稼働中・非公開）
個人利用の自動売買システム。詳細は非公開。

## 使っている技術

| 領域 | 技術 |
|---|---|
| 言語 | Go / TypeScript / Python / Rust |
| ランタイム・FW | Node.js / Tauri v2 |
| データ | SQLite / Litestream / BigQuery |
| インフラ | Docker Compose / Cloudflare / GCP / systemd |
| CI/CD | GitHub Actions |
| 開発 | Claude Code |

## 連絡先
[X](https://twitter.com/tmhiroak) · [LinkedIn](https://www.linkedin.com/in/tmhiroak)
