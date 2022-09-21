# wowtoc pygments syntax highlighting

temporary repo my [PR](https://github.com/pygments/pygments/pull/2244) gets accepted? and then
mkdocs material upgrades their pygments version.

while waiting on that, it's kinda weird: this lexer needs to be packaged in its own repo and then
installed into the project you want it to be in. something with entry points... i dunno. See
<https://pygments.org/docs/plugins/>,
<https://github.com/pygments/pygments/issues/1603#issuecomment-1140501125>.

add this to a poetry project with `poetry add -D git+https://github.com/t-mart/wowtoc.git`.
