Hi, I'm an engineer [working on OpenShift 4, Fedora/RHEL CoreOS](https://blog.verbum.org/2021/03/05/why-i-work-on-openshift-and-fedora-rhel/)
and as of recently focused on [bootc](https://github.com/containers/bootc/).

I'm a big fan of Rust.

Other things I currently maintain include:

- https://github.com/coreos/cargo-vendor-filterer/
- https://github.com/alexcrichton/tar-rs/

## Online/social media

- [@walters:fedora.im](@walters:fedora.im) on Matrix
- [@cgwalters@fosstodon.org](https://fosstodon.org/@cgwalters) on Mastodon
- `colinwalters` on Discord
- [blog](https://blog.verbum.org)

## LLMs

See [this blog](https://blog.verbum.org/2026/03/18/llms-and-core-software-human-driven/). 

I largely agree with [this post by Graydon Hoare](https://graydon2.dreamwidth.org/322732.html) (the inventor of Rust).
I had been looking forward to ending my career writing Rust, but...I am not typing it
much anymore.

However, my record of maintaining FOSS for over 20+ years still stands. I commit to ensuring
that all "core" software I write (i.e. software that may run on your computer,
and I attach my name to it) and maintain will be reviewed by me.  Further, I think it
remains a baseline to have two humans involved, one author and one distinct reviewer
(but now both may be assisted by LLMs).

I maintain software that is important, and I'm on the receiving end of often large LLM generated
commits. I will treat *your* project with as much (or more) care as I do for my own.

However, if you get a PR from me, it is very likely that it is *mostly* LLM generated now,
because as Graydon says:

> I still write some code, but less and less, and more of it is around the margins: touchups, sketches of APIs and data structures, subtle stuff it's easy to be subtly-wrong about, or perhaps LLM-supervisory bits. Because the LLM really does often write the main logic as well as I would at this point, and faster, and more persistently.

My current experience is for deep, nontrivial work, I need to fix up somewhere between 10-15% of obvious LLM garbage (like reimplementing base64 encoding for no obvious reason) that still makes it pass subagent reviews etc. But, who knows what the future will be like.

An advantage for software engineers whose career in FOSS long predates LLMs like mine: you can
easily see that I have the ability to write e.g. systems level Rust/Go/C etc. If I push
a PR for a language/framework I don't know well, I will be crystal clear about that in
the PR description.

### Assisted-by/Generated-by

You may see this in my commit messages. Typically, I use [OpenCode](https://opencode.ai)
with a mixture of foundation models (Gemini and Claude). You can see my AGENTS.md
and opencode config in my [dotfiles repo](https://github.com/cgwalters/homegit).

I also operate [@cgwalters-bot](https://github.com/cgwalters-bot), a semi-autonomous
agent account that helps with my upstream work; its [README](https://github.com/cgwalters-bot/cgwalters-bot#readme)
explains what it does. I'm responsible for it, so if it causes you a problem, mention me.
