# mobile-dev-flutter

Flutter Stack Pack for [mobile-dev](https://github.com/Bolsar/mobileDev), the senior mobile engineer agent. mobile-dev holds the shared knowledge (mindset, skills, core references); this repo adds the Flutter specifics: greenfield defaults, idioms, tooling and a `verify` script.

Needs mobile-dev. Install both.

## Install
Install mobile-dev and this pack together. Full notes per tool: [mobile-dev README](https://github.com/Bolsar/mobileDev#install).

**Claude Code**
```sh
claude plugin marketplace add Bolsar/mobileDev
claude plugin install mobile-dev@bolsar
claude plugin install mobile-dev-flutter@bolsar
```

**GitHub Copilot CLI**
```sh
copilot plugin marketplace add Bolsar/mobileDev
copilot plugin install mobile-dev@bolsar
copilot plugin install mobile-dev-flutter@bolsar
```

**Codex**
```sh
codex plugin marketplace add Bolsar/mobileDev
```
Then install `mobile-dev` and `mobile-dev-flutter` from `/plugins`.

**Gemini CLI**
```sh
gemini extensions install https://github.com/Bolsar/mobileDev
gemini extensions install https://github.com/Bolsar/mobile-dev-flutter
```

**Cursor**: Settings → Plugins → Install from Repository, once with `https://github.com/Bolsar/mobileDev` and once with `https://github.com/Bolsar/mobile-dev-flutter`.

**Other tools** (Antigravity, Copilot coding agent, ...): copy mobile-dev into your app as `.mobile-agent/` (see its README), then add this pack inside it:
```sh
git clone https://github.com/Bolsar/mobile-dev-flutter .mobile-agent/stacks/flutter
rm -rf .mobile-agent/stacks/flutter/.git
```

## Verify
From the app project's root: `<this pack>/verify [--flow .maestro/<flow>.yaml]`. Proof lands in `.mobile-agent-proof/<timestamp>/`.

## License
MIT
