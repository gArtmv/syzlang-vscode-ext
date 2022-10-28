Basic syntax highlighter for syzkaller descriptions. It intends to ease reading and writing syz-lang descriptions by coloring key terms. See [here](https://github.com/google/syzkaller/blob/master/docs/syscall_descriptions_syntax.md) a complete guide on syz-lang syntax.

## Features

Basic syntax highlighting for [syz-lang](https://github.com/google/syzkaller/blob/master/docs/syscall_descriptions_syntax.md)

![](/images/syzlang_highlighted.png)

> Tip: Many popular extensions utilize animations. This is an excellent way to show off your extension! We recommend short, focused animations that are easy to follow.

## Requirements

You need to download and setup syzkaller as described either on [github](https://github.com/google/syzkaller)
## Known Issues

The tool is in perma-beta state and doesn't highlight all terms correctly. It was design to provide basic assistance when reviewing syz-lang descriptions. In the future we may provide auto-complete and validation.

## Release Notes

The first release with basic functionality