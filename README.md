# LOp9
情報の濁流の波に乗りたい人生だった・・・


# ✅ 開発環境導入手順

## 📦 対象

* Windows 10/11 64bit
* Servlet + Pure JS 開発（LnoteEditor など）
* スタンドアロンWebアプリ（Tomcatでローカル動作）

---

## 🪛 Step 1. Amazon Corretto（Java 17）を導入

1. [Corretto 17 ダウンロードページ](https://docs.aws.amazon.com/corretto/latest/corretto-17-ug/downloads-list.html) にアクセス
2. 「Windows x64 MSI Installer」をダウンロード・実行
3. コマンドプロンプトで以下を確認：

   ```sh
   java -version
   ```

   ```
   openjdk version "17.x.x"（Amazon Corretto） ← OK！
   ```

---

## 🪛 Step 2. Eclipseを導入

1. [Eclipseダウンロードページ](https://www.eclipse.org/downloads/packages/)
2. 「Eclipse IDE for Enterprise Java and Web Developers」を選択
3. ZIPを解凍 or インストーラからインストール
4. `eclipse.exe` 起動

---

## 🪛 Step 3. Apache Tomcat 9 を導入

1. [Tomcat 9公式サイト](https://tomcat.apache.org/download-90.cgi) へアクセス
2. 「32-bit/64-bit Windows Service Installer」を選んでインストール
3. インストール先例： `C:\Apache\Tomcat9`
4. ブラウザで起動確認：
   → [http://localhost:8080/](http://localhost:8080/)

---

## 🪛 Step 4. EclipseにTomcatを連携

1. Eclipse起動 → 下部の「Servers」タブを開く
   　（なければ `Window > Show View > Servers`）

2. 「No servers are available...」というリンクをクリック

3. `Apache > Tomcat v9.0` を選択し、「Next」

4. **Tomcatのインストール場所**を指定
   　（例：`C:\Apache\Tomcat9`）
