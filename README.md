<p align="center">
  <img src="./icon.png" width="96" alt="Unfold icon">
</p>

<h1 align="center">Unfold Releases</h1>

<p align="center">
  Distribution repository for <b>Unfold - AI Code Tutor</b><br>
  <b>Unfold - AI Code Tutor</b> の配布用リポジトリです
</p>

---

## English

This repository is for distributing release packages of **Unfold - AI Code Tutor**.

It is mainly used to provide `.vsix` files for users who cannot install the extension directly from their IDE marketplace.

### Download

Please download the latest `.vsix` file from the **Releases** page.

### How to install

#### Visual Studio Code
If Unfold is available in your marketplace, installing from the marketplace is recommended.

#### VS Code fork IDEs
Some VS Code-compatible IDEs use a different default marketplace, so the extension may not be installable directly from the marketplace.

In that case:

1. Open the **Releases** page of this repository
2. Download the latest `.vsix` file from **Assets**
3. In your IDE, open the Extensions view
4. Open the menu (`...`)
5. Choose **Install from VSIX...**
6. Select the downloaded `.vsix` file

### Notes

- Unfold is mainly tested on **Visual Studio Code**
- Behavior may differ in some VS Code fork IDEs
- In some fork IDEs, features such as block splitting may not work as expected because of differences in symbol support

---

## 日本語

このリポジトリは **Unfold - AI Code Tutor** の配布用リポジトリです。

主に、IDEのマーケットプレイスから直接インストールできないユーザー向けに、`.vsix` ファイルを配布するために使用します。

### ダウンロード

最新版の `.vsix` ファイルは **Releases** ページからダウンロードしてください。

### インストール方法

#### Visual Studio Code
Unfold が Marketplace からインストールできる場合は、Marketplace からのインストールをおすすめします。

#### VS Code フォークIDE
一部の VS Code 互換IDEでは、既定のマーケットプレイスが異なるため、Marketplace から直接インストールできない場合があります。

その場合は、次の手順でインストールしてください。

1. このリポジトリの **Releases** ページを開く
2. **Assets** から最新の `.vsix` ファイルをダウンロードする
3. IDEで拡張機能ビューを開く
4. メニュー（`...`）を開く
5. **Install from VSIX...** を選ぶ
6. ダウンロードした `.vsix` ファイルを選ぶ

### 注意

- Unfold は主に **Visual Studio Code 本体** で動作確認しています
- 一部の VS Code フォークIDEでは挙動が異なる場合があります
- 特にブロック分割などの機能は、IDE側のシンボル対応の違いにより期待どおり動かない場合があります
