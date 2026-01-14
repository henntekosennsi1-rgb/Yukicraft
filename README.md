# Yukicraft - 雪掘りサバイバル

> ⚠️ **α版（アルファ版）** - このプラグインは現在開発中です。バグが存在する可能性があります。

雪ブロックを掘って相手を落とすサバイバルミニゲームプラグインです。

## 概要

複数の雪の層の上で戦うサバイバルゲーム。シャベルで雪を掘り、相手を最下層に落とせば勝利！クリーパーも出現してカオスな展開に！

## ⚠️ α版について

- 機能が不完全な場合があります
- バグが存在する可能性があります
- 問題を発見した場合は [Discord](https://discord.gg/zYY55dzhjd) でご報告ください

## ダウンロード

[Releases](https://github.com/henntekosennsi1-rgb/Yukicraft/releases)

## 主な機能

- 多層雪フィールドアリーナ
- 雪を掘って相手を落とす
- 最下層に落ちたら脱落
- クリーパー定期出現（設定可能）
- 自動マップリセット
- スコアボード表示
- 看板での参加/退出
- 最大16人対応

## ゲームルール

- プレイヤーは雪の層の上にスポーン
- ダイヤモンドシャベルで雪ブロックを掘る
- 相手を最下層に落とす
- クリーパーが定期的に出現して地形を破壊
- 最後まで生き残った人が勝利！

## コマンド

| コマンド | 説明 |
|---------|------|
| `/yukicraft join` | 参加 |
| `/yukicraft leave` | 退出 |
| `/yukicraft start` | ゲーム開始 |
| `/yukicraft stop` | ゲーム停止 |
| `/yukicraft setup spawn` | 退出スポーン設定 |
| `/yukicraft setup lobby` | ロビー設定 |
| `/yukicraft setup gamespawn` | ゲームスポーン設定 |
| `/yukicraft setup area pos1/pos2` | エリア設定 |
| `/yukicraft reload` | 設定再読み込み |

## 設定
```yaml
game:
  max-players: 16
  end-delay: 10

creeper:
  enabled: true
  interval: 30      # 出現間隔（秒）
  count: 5          # 1回の出現数
  block-damage: true
```

## 動作環境

- Spigot/Paper 1.21.x
- Java 17以上

## コミュニティ

**Discord:** https://discord.gg/zYY55dzhjd

## ライセンス

All Rights Reserved
