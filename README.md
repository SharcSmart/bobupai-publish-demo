# bobupai-publish-demo

A throwaway website used as a test fixture for [BobupAI](https://www.bobupai.com).

**This site is not affiliated with, endorsed by, or operated by BMW AG.** It is an
independently written reference about a publicly sold vehicle, used to exercise
BobupAI's crawl → analyse → recommend → publish loop against a real website that we
control. Figures are illustrative. Every page carries `noindex,nofollow`.

Source of truth for this site lives in the BobupAI repo at
`.agents/skills/demo_environment/site/`. Do not edit here — edit there and push.

Pages published by BobupAI land in `content/blog/`. The `demo-baseline` tag marks the
clean state; teardown resets `main` back to it.
