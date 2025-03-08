# kpm-rs

kpm-rs は、Krypton Linux のパッケージマネージャー **kpm** を Rust で再実装したバージョンです。

## 特徴

- **alpm** を使用して実装されています。  
- **日本語と英語の両方に対応** することを目指しています。  
## 注意事項 
公式 kpm の更新が反映されるまで時間がかかる場合があります。  

**常に最新の kpm を使用したい場合は、[Krypton Linux 公式の kpm](https://github.com/Krypton-Linux/kpm) を利用してください。**

## 依存関係

以下のパッケージが必要です：

- `pkg-config`
- `base-devel`
- `msgfmt`

## ライセンス

このプロジェクトは **GPL-3** ライセンスのもとで提供されています。  
詳細は [LICENSE](./LICENSE) をご覧ください。