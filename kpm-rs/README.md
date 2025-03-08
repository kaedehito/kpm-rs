# ビルド方法

## 必要な環境

このプログラムをビルドするには、**Rust** がインストールされている必要があります。  
Rust をインストールしていない場合は、[公式サイト](https://www.rust-lang.org/ja/learn/get-started) を参考にしてください。

## 必要な依存関係

以下のパッケージが必要です：

- `pkg-config`
- `base-devel`
- `msgfmt`

これらは通常、**Arch Linux** のインストール時に含まれていますが、未インストールの場合は以下のコマンドでインストールできます：

```sh
sudo pacman -S pkg-config base-devel gettext
```

## デバッグモードでの実行

開発時にデバッグモードで kpm-rs を実行するには、以下のコマンドを実行します：
```sh
cargo run
```

## 最適化されたビルド

配布用に最適化されたバイナリをビルドするには、以下のコマンドを実行してください：
```sh
cargo build --release
```

ビルドが完了すると、最適化された kpm-rs バイナリが target/release/ に生成されます：
```rs
ls target/release/kpm
```