# tmhiroak

バックオフィスの AI 活用推進を本業にしています。日々の仕事で感じた不便や非効率を、Claude CodeとCodex を使った個人開発のプロダクトで解決しています。
最近､Orcaを使って､Claude CodeとCodexを協業させて､開発しています｡

作るだけでなく、動かし続けることを大事にしています。ジョブスケジューラ（jete）で定期処理を回し、Cloudflare Workers と Healthchecks.io で外から監視し、障害は公開ステータスページで知らせるところまで、個人の規模で一通り自分で回しています。

## プロダクト

<p>
<a href="https://statuspage.incident.io/tmhiroak-products"><img src="https://img.shields.io/endpoint?url=https%3A%2F%2Fhealthchecks.io%2Fbadge%2F60e79c32-70f1-4570-8c60-c65ed1%2FdEYJw_dH%2Fs6.shields&style=for-the-badge&label=all%20systems" alt="全体の稼働状況" height="32" hspace="4"></a>
<a href="https://statuspage.incident.io/tmhiroak-products"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/status-button-dark.svg"><img src="assets/status-button.svg" height="32" alt="ステータスページを開く"></picture></a>
</p>

<p>
<a href="https://nabrahunt.com"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/card-nabrahunt-dark.svg"><img src="assets/card-nabrahunt.svg" width="400" alt="Nabrahunt（招待制ベータ）：電車・フェリーで行く釣行の計画ツール。天候・波浪・潮汐・交通を一つに束ね、「辿り着けて、釣りになるか」を判定"></picture></a>
<a href="https://statuspage.incident.io/tmhiroak-products"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/card-jete-dark.svg"><img src="assets/card-jete.svg" width="400" alt="jete（稼働中・非公開）：セルフホスト型ジョブスケジューラ。cron と GitHub Actions の置き換え。Go の単一バイナリで VPS 上で実運用"></picture></a>
<a href="https://statuspage.incident.io/tmhiroak-products"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/card-encrault-dark.svg"><img src="assets/card-encrault.svg" width="400" alt="Encrault（開発中・非公開）：.env / API キーの Vault。キーを一か所に置き、プロジェクト・環境・配布先を参照で結ぶデスクトップアプリ"></picture></a>
<a href="https://statuspage.incident.io/tmhiroak-products"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/card-stock-dark.svg"><img src="assets/card-stock.svg" width="400" alt="Stock（稼働中・非公開）：個人利用の自動売買システム。詳細は非公開"></picture></a>
</p>

## 使っている技術

| 領域 | 技術 |
|---|---|
| 言語 | Go / TypeScript / Python / Rust |
| ランタイム・FW | Node.js / Tauri v2 / Vite / htmx |
| データ | SQLite / Litestream / BigQuery / Cloudflare R2 |
| インフラ | Docker Compose / Cloudflare（Workers・Tunnel・Access・Pages）/ GCP / VPS / systemd / Tailscale |
| 外部 API | Open-Meteo / 気象庁 / 駅すぱあと / ODPT / OpenStreetMap / J-Quants / EDINET / SEC EDGAR / API Ninjas |
| 認証・通知 | Passkey（WebAuthn）/ LINE・Google・GitHub ログイン / Cloudflare Turnstile / Resend / Web Push / Discord |
| 監視・運用 | Healthchecks.io / incident.io / Cloudflare Workers / Prometheus |
| セキュリティ | gitleaks / Semgrep / cargo-deny / OSV / Landlock / age |
| AI・開発 | Claude Code / Codex / Orca / Claude Agent SDK / MCP / Groq / Ollama |

## 連絡先
[X](https://twitter.com/tmhiroak) · [LinkedIn](https://www.linkedin.com/in/tmhiroak)
