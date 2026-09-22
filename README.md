# fizz-conversation-history

**Fizz** (AITuber system in [Almide](https://github.com/almide/almide)) — §3 brain 部品。

直近 N ターンの窓つき会話履歴 (前の話題を引きずらせない方針)。`push_user/push_assistant/clear`。長期記憶は別部品。

責務は一行で、入力 → 出力が型で言い切れる単位 (openaituber `docs/almide-component-breakdown.md` §3)。

## Install

```toml
[dependencies]
fizz_conversation_history = { git = "https://github.com/aiviecast/fizz-conversation-history", tag = "v0.1.0" }
```

## Tests

```bash
almide test
```

純ロジックなのでネットワーク・API キー不要でテストできる。
