# Day072 Story — Travel Socket Map

## Why
毎日使う小さな課題を、1ページで即解決できる形にしたかったため。

## Requirements
- Webブラウザだけで完結すること
- 1画面で主要操作が終わること
- GitHub Pagesで公開できること

## Design highlights
- Day072専用にテーマをseed固定して再生成時の見た目を安定化
- utility用途に寄せた単機能UIで迷いを減らす
- 出力をそのまま再利用できるテキスト構造
- Family: travel_socket_layout
- Mechanic: plug_match
- Input/Output: device_slots -> device_bundle
- Audience Promise: 充電まわりの不足を荷造り前に潰せる。
- Publish Hook: 機器と必要口数を入れると、足りない口数と持つべきケーブル束が一画面で見える。
- Complexity Tier: small
- Selected components: none
- Complexity hint: Implement the locked brief with one clear hero interaction and keep the main screenshot readable.

## Trade-offs / Known issues
- ローカル保存機能は未実装
- 複雑な入力バリデーションは最小限

## Next ideas
- 履歴保存
- プリセット追加
- エクスポート形式拡張

## Social copy
Day072｜旅先コンセント地図
旅先の充電セットを決めるためのツールです。
