# Hi, I'm Shunsuke Kamioka 👋

**Independent infrastructure engineer based in Kanagawa, Japan.**
I keep long-running production servers healthy, secure, and up to date. Many of them are legacy systems that others would rather not touch.

### What I do
- **Linux operations at scale**: day-to-day care of ~100 servers across many clients, from CentOS 6/7 to Rocky Linux 9/10, Ubuntu and Amazon Linux 2023
- **Legacy-to-modern migrations**: moving aging CentOS/Apache/PHP stacks to Rocky Linux with Ansible, planning cutovers, and running PHP upgrades (5.x → 8.4) side by side to minimize downtime
- **Cloud**: AWS (EC2, RDS, DMS, S3/Athena, SES) and GCP (Compute Engine, Cloud Run, GitHub Actions with Workload Identity Federation)
- **Security**: web shell cleanup and incident response, CSP rollout from Report-Only to enforce, hardening, and certificate automation
- **Mail**: Postfix, SPF/DKIM/DMARC, qmail → Postfix migrations, Amazon SES
- **Identity**: Microsoft 365 / Entra ID MFA (FIDO2, TAP), Windows Hello for Business, Entra Connect → Cloud Sync

### Selected work
- Migrated a MySQL 5.6 reporting database to AWS with DMS, splitting hot data into RDS and archives into S3/Athena
- Moved several organizations' CentOS 6/7 servers to Rocky Linux 10, fully codified in Ansible
- Recovered a DRBD + Pacemaker HA cluster from split-brain
- Built per-project Zabbix Proxies to monitor EC2 fleets on isolated networks
- Set up an always-on site-to-site VPN from AWS EC2 to an on-prem gateway, verified to survive reboots

### Toolbox
`Linux` `Ansible` `Terraform` `AWS` `GCP` `Zabbix` `Apache` `nginx` `PHP-FPM` `Tomcat` `MySQL` `PostgreSQL` `Postfix` `DRBD/Pacemaker` `Let's Encrypt` `GitHub Actions`


---

<details>
<summary>🇯🇵 日本語</summary>

### 上岡 俊介（Shunsuke Kamioka）

**神奈川を拠点とするインフラエンジニアです。**
長く動き続けている本番サーバーを、安定・安全・最新の状態に保つのが仕事です。他の人が触りたがらないレガシーなシステムも多く扱っています。

### 主な領域
- **Linuxサーバー運用**：複数のお客様にまたがる約100台のサーバーを日々運用。CentOS 6/7 から Rocky Linux 9/10、Ubuntu、Amazon Linux 2023 まで
- **レガシー環境の移行**：古いCentOS/Apache/PHP環境をAnsibleでRocky Linuxへ移行。切替計画の立案や、PHPの並行導入によるバージョンアップ（5.x → 8.4）で停止時間を最小化
- **クラウド**：AWS（EC2、RDS、DMS、S3/Athena、SES）、GCP（Compute Engine、Cloud Run、Workload Identity連携のGitHub Actions）
- **セキュリティ**：Webシェルの駆除とインシデント対応、CSPのReport-Onlyからブロックへの移行、サーバーの堅牢化、証明書更新の自動化
- **メール**：Postfix、SPF/DKIM/DMARC、qmailからPostfixへの移行、Amazon SES
- **ID・認証**：Microsoft 365 / Entra IDの多要素認証（FIDO2、TAP）、Windows Hello for Business、Entra Connect SyncからCloud Syncへの移行

### 主な実績
- MySQL 5.6のレポート用DBをDMSでAWSへ移行し、日常的に使うデータはRDS、過去データはS3/Athenaに分割
- 複数組織のCentOS 6/7サーバーをRocky Linux 10へ移行し、構成をすべてAnsibleでコード化
- DRBD + Pacemaker構成のHAクラスタをスプリットブレインから復旧
- 閉じたネットワーク上のEC2群を監視するため、案件ごとにZabbix Proxyを構築
- AWS EC2からオンプレミスのVPNゲートウェイへの常時接続を構築し、再起動後も接続が維持されることを検証


</details>
