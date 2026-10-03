# mobile-dev-flutter

Flutter Stack Pack for [mobile-dev](https://github.com/Bolsar/mobileDev), the senior mobile engineer agent. mobile-dev holds the shared knowledge (mindset, skills, core references); this repo adds the Flutter specifics: greenfield defaults, idioms, tooling and a `verify` script.

Needs mobile-dev. Install both.

## Claude Code
```sh
claude plugin marketplace add Bolsar/mobileDev
claude plugin install mobile-dev@bolsar
claude plugin install mobile-dev-flutter@bolsar
```

## Other tools (Codex, Cursor, Gemini CLI, ...)
Copy mobile-dev into your app as `.mobile-agent/` (see its README), then add this pack inside it:
```sh
git clone https://github.com/Bolsar/mobile-dev-flutter .mobile-agent/stacks/flutter
rm -rf .mobile-agent/stacks/flutter/.git
```

## Verify
From the app project's root: `<this pack>/verify [--flow .maestro/<flow>.yaml]`. Proof lands in `.mobile-agent-proof/<timestamp>/`.

## License
MIT
