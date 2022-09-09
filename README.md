## WordPress 環境構築手順 (Windows 向け)

1. Docker Desktop をインストール
    * https://docs.docker.com/desktop/windows/install/
      * "Docker Desktop for Windows" からダウンロード、インストール。

    * インストール および Windows の再起動後、"WSL 2 installation is incomplete."
      というダイアログが表示される場合、ダイアログ中にある URL を開き
      "x64 マシン用 WSL2 Linux カーネル更新プログラム パッケージ"
      をダウンロードインストールする(再起動)。

2. start.bat を実行 (ダブルクリック)

3. ブラウザで http://localhost:8080 を表示


## WordPress 環境へのファイル配置方法

wp-study/html ディレクトリが
WordPress 環境の /var/www/html ディレクトリと同期している。

そのため、例えば WordPress 環境の /var/www/html/wp-content ディレクトリに
ファイルを配置したい場合は、
ローカル環境の wp-study/wp-content ディレクトリにファイルを配置すればよい。

