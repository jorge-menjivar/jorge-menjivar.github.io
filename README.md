# jorge-menjivar.github.io

Super STT's repo is now [super-voice](https://github.com/jorge-menjivar/super-voice), and its Pages site moved from `/super-stt/` to `/super-voice/`. GitHub doesn't redirect a renamed repo's Pages site, so this site keeps the old links working:

1. `super-stt/index.json` is a copy of Super Voice's backend registry, for Super STT installs that still read it from the old URL. The two schemas beside it are copies too. Super Voice's index workflow pushes fresh copies after each build, so don't edit them here.
2. Any other page under `/super-stt/` sends you to the same page under `/super-voice/`. `404.html` does that.

Don't create a repo named `super-stt` under this account. Its Pages site would take over `/super-stt/`, and GitHub would stop redirecting the old repo URLs to super-voice.
