
#### what is it

This is {quote}fixed{unquote} version of "Video DownloadHelper" extention.
For Chrome/Chromium only for now.

disables:
* download limits
* updates
* popups

#### how to install in Chrome/Chromium
1. open "chrome://extensions/"
2. click on "Load unpacked"
3. select "unpacked" folder from this repo

#### how to see specific changes
##### in case you want to audit this fix

`git -c core.pager="less -RFX" show --color-words {COMMIT}`
or
`git --no-pager show --color-words {COMMIT}`


#### how to make patch from specific commit
###### in case you want to apply patch to own repo or another version

create:
`git format-patch -1 {COMMIT}`

apply:
`git am {FILE.PATCH}`
or
`git apply --directory={UNPACKED_DIR} {FILE.PATCH}`


