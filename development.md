# CHaser Clients Development Documentation

> [!NOTE]
> 開発者向けのドキュメントです。  
> このドキュメントは、CHaserクライアントの開発に関する情報を提供します。  
> ラッパーの開発に参加に興味がある方は、[CONTRIBUTING.md](./contribute.md)を参照してください。

## プロジェクトの種類

CHaserクライアントラッパーは、以下の3つのプロジェクトに分類されます。

- CHaser{lang-name} : CHaserクライアントラッパーの本体です。
- CHaser{lang-name}-DevKit : CHaserクライアントラッパーを使用して、CHaserのクライアントを開発するための開発キットです。
- CHaser{lang-name}-Doc : CHaserクライアントラッパーのドキュメントです。

## 種類別に含まれるものと含まれないもの

CUIサーバーは、yugu0202氏が開発したものを使用しています。  
repository: [yugu0202/compactCHaserServer](https://github.com/yugu0202/compactCHaserServer)

### CHaser{lang-name}

#### 含まれているもの

- CHaserクライアントラッパーの本体
- サンプルコード
- 基本ドキュメント

#### 含まれていないもの

- 追加ドキュメント
- CUIサーバー
- GUIサーバー
- デバッガー
- VSCode用の開発環境
- セットアップドキュメント

### CHaser{lang-name}-DevKit

#### 含まれているもの

- CHaserクライアントラッパーの本体
- サンプルコード
- 基本ドキュメント
- CUIサーバー
- デバッガー
- VSCode用の開発環境
- セットアップドキュメント

#### 含まれていないもの

- 追加ドキュメント
- GUIサーバー

### CHaser{lang-name}-Doc

#### 含まれているもの

- 基本ドキュメント
- 追加ドキュメント
- セットアップドキュメント

#### 含まれていないもの

- CHaserクライアントラッパーの本体
- サンプルコード
- CUIサーバー
- GUIサーバー
- デバッガー
- VSCode用の開発環境


## ラッパーを使用する

CHaserクライアントラッパーを使用して、CHaserのクライアントを開発するためには、以下の手順を実行してください。

1. [こちら](../development/README.md)を参照して、開発キットを選択する。
2. 開発キットのリポジトリをクローンする。
3. 開発キットのセットアップ手順に従って、開発環境をセットアップする。
4. 開発キットのサンプルコードを実行して、動作確認を行う。
5. 開発キットのドキュメントを参照して、開発を進める。

詳細は、各開発キットのREADME.mdを参照してください。

