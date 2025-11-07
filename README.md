
Hi there,

I'm Simon, currently building [Shelv](https://shelv.app): Hackable, Local, AI-enabled notes. It is source available [here](https://github.com/twop/shelv). 

There are a few ideas behind it:
 - Either tools are barebones and don't cover my needs, or are too flexible and complex (I'm looking at you Obsidian), so you know you can customize them just right... eventually. My thesis is that the alternative to both is **hackable**, that is, you can **create** what you want rather than expecting the tool to magically fit your needs.
- *Renting my own data* economy is kind of unexciting. When Notion did not open up without internet access, I realized that I'm renting *my* own notes. So I want **data ownership** with *cloud utility*. Hence, CRDT seems to be very appealing to me.
- I have somewhat mixed feelings about LLMs, but I do like these use cases in Shelv:
	* Ask assistant "What are my current keybindings?" -> **discovery**
	* Or "Add a shortcut that outputs the current date in yyyy/mm/dd" -> **automating bespoke one-off UI**

### About me
I have been fascinated with software since I was a kid, as it usually happens, it started with a game: Baldur's Gate. But what happens less frequently is I became a game developer and worked on two big titles for 7 years.

That affected me in several ways:
- At that time, you needed to build everything from scratch (this was before Unity), hence it was just normal to build a brand new physics engine or UI framework or network stack based on UDP => there are no impossible tasks, just hard ones.
- Performance is arguably the second most important thing in games (after gameplay) => I built a passion and appreciation for squeezing CPU and GPU cycles.
- I really enjoyed working on dev tools, virtual machines, and languages. Long story, but we slapped a VM into the game engine to run Flash on the GPU (I believe we were the first to run it on the GPU).
- 7 years of C++ leave scars on your soul.

Since then, I've worked in many different domains and different tech stacks, but performance and tools always called to me. Thus, I developed a fascination with programming languages, type systems, and virtual machines. So when Rust came out, it was obvious to me that it could represent a qualitative shift in how we build software, and I have been a user and enthusiast since Rust Analyzer came out (I need my autocomplete).

The past 6 years I spent at various early-stage startups, none of which worked out well for me, so there is that. One of the biggest eye-openers for me was the realization that seemingly innocent decisions early on might disproportionately affect the company later on, two examples come to mind:
- Drew (CEO and founder of Dropbox) knew Python, so naturally the first version was in Python. Fast forward 10 years and it was the largest Python codebase (at least as far as I know), with a desperate need for performance and type safety
- Which CSS approaches/technology to use: Sourcegraph adopted the BEM convention, which later on they replaced with CSS modules (with effort, as far as I know). It is surprisingly hard to replace CSS.

###  Some cool (at least for me) work I did in my past free time:
- Implemented the JavaScript promise spec in an interpreter written in C# https://github.com/sebastienros/jint
- Co-started an optimizing JS compiler for Elm output https://github.com/mdgriffith/elm-optimize-level-2
- Implemented a pull-based virtual DOM reconciler in F# for a mobile UI framework with primarily stack allocations https://github.com/fabulous-dev/Fabulous


### Tools I'm using
- DIY split keyboard -> [Forager](https://github.com/carrefinho/forager)
- Editor -> [Helix](https://helix-editor.com/)
- Terminal -> [Alacritty](https://alacritty.org/)
- Terminal stuff (multiplexer?) -> [Zellij](https://zellij.dev/), I even wrote a plugin
- MacOS stuff:
	* [Raycast](https://www.raycast.com/)
	* Launcher: [Leaderkey](https://github.com/mikker/LeaderKey.app) -> this one is kinda great
	* Keyboard navigation: [Homerow](https://www.homerow.app/)
	* Another one: [mouseless](https://mouseless.click/)
