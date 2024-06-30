<!-- LTeX: enabled=false -->
# nvim-eol-lsp-hints 🪧
<!-- LTeX: enabled=true -->
<!-- TODO uncomment shields when available in dotfyle.com 
<a href="https://dotfyle.com/plugins/chrisgrieser/nvim-eol-lsp-hints">
<img alt="badge" src="https://dotfyle.com/plugins/chrisgrieser/nvim-eol-lsp-hints/shield"/></a>
-->

A minimal plugin that displays LSP inlay-hints at the end of line, out of your
way.

<img alt="Showcase" width=70% src="https://github.com/chrisgrieser/nvim-eol-lsp-hints/assets/73286100/acd538a7-f2ee-4b8e-9c07-bd7c0c4ad20e">

## Installation

```lua
-- lazy.nvim
{
	"chrisgrieser/nvim-eol-lsp-hints",
	event = "LspAttach",
	opts = {},
},

-- packer
use {
	"chrisgrieser/nvim-eol-lsp-hints",
}
```

## Configuration

```lua
-- default settings
require("eol-lsp-hints").setup {
	icons = {
		type = "󰜁 ",
		parameter = "󰏪 ",
	},
	label = {
		padding = 1,
		marginLeft = 0,
	},
}
```

## Usage
Just load the plugin.

## Limitations
Disabling/toggling LSP hints is not implemented yet.

<!-- vale Google.FirstPerson = NO -->
## About the author
In my day job, I am a sociologist studying the social mechanisms underlying the
digital economy. For my PhD project, I investigate the governance of the app
economy and how software ecosystems manage the tension between innovation and
compatibility. If you are interested in this subject, feel free to get in touch.

I also occasionally blog about vim: [Nano Tips for Vim](https://nanotipsforvim.prose.sh)

- [Academic Website](https://chris-grieser.de/)
- [Mastodon](https://pkm.social/@pseudometa)
- [ResearchGate](https://www.researchgate.net/profile/Christopher-Grieser)
- [LinkedIn](https://www.linkedin.com/in/christopher-grieser-ba693b17a/)

<a href='https://ko-fi.com/Y8Y86SQ91' target='_blank'><img
	height='36'
	style='border:0px;height:36px;'
	src='https://cdn.ko-fi.com/cdn/kofi1.png?v=3'
	border='0'
	alt='Buy Me a Coffee at ko-fi.com'
/></a>
