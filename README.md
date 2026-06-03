# AI Detox Prompts

Japanese prompt collection for rewriting AI-generated text into natural, human-feeling prose.

AIが生成した日本語の下書きから、テンプレ感、説明書感、記号過多、過剰な丁寧さを取り除き、人が書いたように整えるためのプロンプト集です。

## Why This Exists

生成AIの文章は便利ですが、そのままだと次のような癖が出やすくなります。

- 結論や前置きが毎回同じ
- 箇条書き、太字、見出しで整理しすぎる
- 「重要です」「効果的です」など抽象語が多い
- 丁寧すぎて、人の体温が消える
- 安全な言い回しが多く、文章がぼやける

このリポジトリは、そうしたAIっぽさを削り、意味や事実関係を保ったまま自然な日本語へ近づけるための実用プロンプトを集めます。

## Prompts

| Prompt | Description |
| --- | --- |
| [ai-detox-writer-ja](./prompts/ai-detox-writer-ja.md) | AIが生成した日本語文章を、人が書いたような自然な文体に全面リライトするためのプロンプト |

## Quick Start

1. [prompts/ai-detox-writer-ja.md](./prompts/ai-detox-writer-ja.md) を開く
2. 中身をChatGPT、Claude、Codexなどのカスタム指示やスキルに貼り付ける
3. AIが生成した文章を渡して、自然な文章に書き換える

## Example

Before:

> 結論から言うと、AIを活用することで業務効率を大幅に向上させることが可能です。本記事では、その具体的なメリットについて解説します。

After:

> AIを使うと、毎回手でやっていた確認や整理の時間を減らせます。空いた時間を、判断や企画のような人が考えるべき仕事に回せるのが大きいところです。

More examples are in [examples/before-after-ja.md](./examples/before-after-ja.md).

## Principles

- Keep the original meaning and facts.
- Do not add unsupported examples, numbers, or proper nouns.
- Remove template-like openings and endings.
- Reduce excessive Markdown, symbols, and labels.
- Prefer concrete verbs over vague abstract nouns.
- Match the original tone instead of forcing a new one.

## Contributing

Pull requests are welcome. Useful contributions include:

- New Japanese rewrite prompts
- Before/after examples
- Prompt variants for note, essay, SNS, business email, or documentation
- Reports of phrases that still feel too AI-generated

Please keep examples free of private or confidential information.

## License

MIT License. See [LICENSE](./LICENSE).
