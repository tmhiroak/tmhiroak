# tmhiroak

バックオフィスの AI 活用推進を本業にしています。日々の仕事で感じた不便や非効率を、Claude CodeとCodex を使った個人開発のプロダクトで解決しています。
最近､Orcaを使って､Claude CodeとCodexを協業させて､開発しています｡

作るだけでなく、動かし続けることを大事にしています。ジョブスケジューラ（jete）で定期処理を回し、Cloudflare Workers と Healthchecks.io で外から監視し、障害は公開ステータスページで知らせる——という運用まで、個人の規模で一通り自分で回しています。

## プロダクト

<p>
<a href="https://statuspage.incident.io/tmhiroak-products"><img src="https://img.shields.io/endpoint?url=https%3A%2F%2Fhealthchecks.io%2Fbadge%2F60e79c32-70f1-4570-8c60-c65ed1%2FdEYJw_dH%2Fs6.shields&style=for-the-badge&label=all%20systems" alt="全体の稼働状況" height="32"></a>
&nbsp; <a href="https://statuspage.incident.io/tmhiroak-products"><b>ステータスページを開く →</b></a>
</p>

<table>
<tr>
<td><a href="https://nabrahunt.com"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/row-nabrahunt-dark.svg"><img src="assets/row-nabrahunt.svg" width="648" alt="Nabrahunt：電車・フェリーで行く釣行の計画ツール（招待制ベータ）"></picture></a></td>
<td width="170" align="center"><a href="https://statuspage.incident.io/tmhiroak-products"><img src="https://img.shields.io/endpoint?url=https%3A%2F%2Fhealthchecks.io%2Fbadge%2F60e79c32-70f1-4570-8c60-c65ed1%2FgssbywFK%2Fnabrahunt.shields&style=for-the-badge&label=status" alt="Nabrahunt の稼働状況"></a></td>
</tr>
<tr>
<td><a href="https://statuspage.incident.io/tmhiroak-products"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/row-jete-dark.svg"><img src="assets/row-jete.svg" width="648" alt="jete：セルフホスト型ジョブスケジューラ（稼働中・非公開）"></picture></a></td>
<td width="170" align="center"><a href="https://statuspage.incident.io/tmhiroak-products"><img src="https://img.shields.io/endpoint?url=https%3A%2F%2Fhealthchecks.io%2Fbadge%2F60e79c32-70f1-4570-8c60-c65ed1%2FY_hV6y9I%2Fjete.shields&style=for-the-badge&label=status" alt="jete の稼働状況"></a></td>
</tr>
<tr>
<td><a href="https://statuspage.incident.io/tmhiroak-products"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/row-encrault-dark.svg"><img src="assets/row-encrault.svg" width="648" alt="Encrault：.env / API キーの Vault（開発中・非公開）"></picture></a></td>
<td width="170" align="center"><a href="https://statuspage.incident.io/tmhiroak-products"><img src="https://img.shields.io/endpoint?url=https%3A%2F%2Fhealthchecks.io%2Fbadge%2F60e79c32-70f1-4570-8c60-c65ed1%2F4dVe9KPq%2Fencrault.shields&style=for-the-badge&label=status" alt="Encrault の稼働状況"></a></td>
</tr>
<tr>
<td><a href="https://statuspage.incident.io/tmhiroak-products"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/row-stock-dark.svg"><img src="assets/row-stock.svg" width="648" alt="Stock：個人利用の自動売買システム（稼働中・非公開）"></picture></a></td>
<td width="170" align="center"><a href="https://statuspage.incident.io/tmhiroak-products"><img src="https://img.shields.io/endpoint?url=https%3A%2F%2Fhealthchecks.io%2Fbadge%2F60e79c32-70f1-4570-8c60-c65ed1%2FSwlc7aGp%2Fstock.shields&style=for-the-badge&label=status" alt="Stock の稼働状況"></a></td>
</tr>
</table>

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
