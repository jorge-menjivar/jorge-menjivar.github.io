# jorge-menjivar.github.io

Super Voice's repo is [super-libre/super-voice](https://github.com/super-libre/super-voice), and its Pages site is [super-libre.github.io/super-voice](https://super-libre.github.io/super-voice/). The repo was jorge-menjivar/super-stt, then jorge-menjivar/super-voice, and its site was under `/super-stt/` and then `/super-voice/` here. GitHub doesn't redirect a renamed or moved repo's Pages site, so this site keeps the old links working:

1. `super-stt/index.json` and `super-voice/index.json` are copies of Super Voice's backend registry, for installs that still read it from an old URL. Super STT reads `super-stt/`. Super Voice betas from before the move read `super-voice/`. The two schemas beside each are copies too. Super Voice's index workflow pushes fresh copies after each build, so don't edit them here.
2. Any other page under `/super-stt/` or `/super-voice/` sends you to the same page on super-libre.github.io/super-voice. `404.html` does that.

Don't create a repo named `super-stt` or `super-voice` under this account. Its Pages site would take over that folder here, and GitHub would stop redirecting the old repo URLs.
