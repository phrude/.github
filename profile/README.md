![phrude logo](https://github.com/phrude/.github/blob/main/images/banner.png)

<https://phrude.com/>

Profiling History-based Runtime Detection System

PhrudeはWebアプリに任意の処理を挿入する攻撃を検知するために内部処理分析を用いる新たなセキュリティ対策ツールです。

- Webアプリに任意の処理を挿入する攻撃を検知
- システムコールを使わない処理からなる攻撃を検知
- 内部処理の記録から攻撃の原因を追跡可能

という特徴を持ち、WAFの検知を回避したHTTPリクエスト経由のWebアプリに任意の処理を挿入する攻撃や、汚染パッケージによるサプライチェーン攻撃に効果があります。

またシステムコールによる攻撃検知ツール(Linux向けEDR製品・Falco・Tracee・Tetragon)で検知できない、環境変数の取得(getenv関数)の実行の検知・内部処理履歴からの原因追跡が可能です。
