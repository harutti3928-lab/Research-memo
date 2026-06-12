# 研究メモ — Computational Physics Reference

計算物理・第一原理計算に関する個人研究メモサイト。静的HTMLで構成されており、`index.html` をブラウザで開くだけで閲覧できる。

## 収録トピック

| カテゴリ | 内容 |
|---|---|
| **VASP** | DFT計算の基本・INCARタグ・計算ワークフロー・トラブルシューティング |
| **FLEX計算** | Fluctuation Exchange Approximation（多体摂動論）・自己エネルギー・感受率・実装メモ |
| **Wannier90** | 最局在Wannier関数・VASP連携・バンド補間・ディスエンタングルメント |
| **Eliashberg方程式** | 強結合超伝導理論・α²F(ω)の計算・Tcの見積もり |

## ディレクトリ構成

```
Research-memo/
├── index.html          # トップページ（目次）
├── vasp/               # VASP関連メモ
├── flex/               # FLEX計算関連メモ
├── wannier/            # Wannier90関連メモ
└── eliashberg/         # Eliashberg方程式関連メモ
```

## 閲覧方法

`index.html` をブラウザで直接開く。サーバー不要。

```
# ローカルサーバーを立てる場合
python -m http.server 8000
# → http://localhost:8000
```

## AIエージェントへの注意

このリポジトリで作業するAIエージェントは [AGENTS.md](AGENTS.md) を参照すること。
