```bash
# macOS apps I have installed. Output of `ls /Applications`
1Password 7.app
2Do.app
Ableton Live 10 Trial.app
Affinity Designer.app
Affinity Photo.app
Airtable.app
Alfred 4.app
Alfred Metadata Tool.app
Anaconda-Navigator.app
Android Studio.app
Anki.app
Annotate.app
App Store.app
Arq.app
Audio Hijack.app
Audiobook Wizard.app
Automator.app
Bartender 3.app
BeardedSpice.app
Bee.app
BetterTouchTool.app
Birthdays.app
Books.app
Brisk.app
Calculator.app
Calendar.app
Canopy.app
Caprine.app
Cascadea.app
Chess.app
CleanShot.app
Conferences.app
Contacts.app
Contexts.app
DaisyDisk.app
Dark Reader for Safari.app
Dash.app
Dashboard.app
Day One.app
Deckset.app
Deliveries.app
DevHub.app
Diagnostics.app
Dictionary.app
Discord.app
Docker.app
Dropbox.app
Dropzone 3.app
FaceTime.app
Fantastical.app
Figma.app
Final Cut Pro.app
Firefox Nightly.app
Fission.app
Flipper.app
Flume.app
Font Book.app
Forecast.app
Framer X.app
GPG Keychain.app
Gifski.app
Google Chrome Canary.app
Hammerspoon.app
Home.app
Hopper Disassembler v4.app
HoudahSpot.app
IINA.app
Image Capture.app
ImageOptim.app
JetBrains Toolbox.app
Just Press Record.app
Kap.app
Karabiner-Elements.app
Karabiner-EventViewer.app
Keka.app
KeyCastr.app
Keybase.app
Keyboard Lock.app
Keyboard Maestro.app
Keynote.app
KubeContext.app
Latest.app
LaunchControl.app
Launchpad.app
Little Snitch Configuration.app
Loom.app
Loopback.app
Lungo.app
MacUpdater.app
Magic Number 2.app
Mail.app
Maps.app
Marked 2.app
Messages.app
MindNode.app
Mission Control.app
Monodraw.app
Name Mangler.app
NativeConnect.app
News.app
Noizio.app
Notes.app
Notion.app
Numbers.app
OBS.app
Onivim2.App
PDF Expert.app
Pages.app
Paprika Recipe Manager 3.app
Paw.app
Photo Booth.app
Photos.app
Pixave.app
PixelSnap 2.app
Pixelmator Pro.app
Pocket.app
PopClip.app
Port Manager.app
Postgres.app
Postico 2.app
Preview.app
Private Internet Access.app
Proxyman.app
QuickTime Player.app
React Native Debugger.app
Reeder.app
Reminders.app
RetroClip.app
RunJS.app
Safari Technology Preview.app
Safari.app
ScreenFlow.app
Script Debugger.app
Sequel Pro.app
Shifty.app
Sidify Music Converter.app
Sip.app
Siri.app
Sketch.app
Slack.app
Sloth.app
SnippetsLab.app
Soulver 3.app
Spark.app
Spectrum.app
Spotify.app
Stickies.app
Stocks.app
Sublime Merge.app
Sublime Text.app
Superposition.app
SwiftPM Catalog.app
Syncalicious.app
SyphonInject.app
System Preferences.app
TablePlus.app
TaskPaper.app
TeamViewer.app
Telegram.app
TextEdit.app
Textual.app
Time Machine.app
Timing.app
TinkerTool.app
Tokens.app
ToothFairy.app
Tor Browser.app
Tower.app
Transmission.app
Transmit.app
Trello.app
Tweetbot.app
Typinator.app
UI Browser.app
UlyssesMac.app
Utilities
Vimac.app
Vimari.app
Visual Studio Code.app
VoiceMemos.app
WWDC.app
WhatsApp.app
WiFi Explorer.app
Wipr.app
WireGuard.app
Xcode.app
Zotero.app
apps
broxy.app
iStat Menus.app
iTerm.app
iTunes.app
nteract.app
zoom.us.app
```

```bash
# sVim settings
let scrollstep = 120

" Unmap defaults
unmap "z i"
unmap "z o"
unmap "z 0"
unmap "g i"
unmap "g r"

" Neat shortcuts
map "v" goToInput
" map "c" lastClosedTab
" map "q" zoomPageIn
" map "m" zoomPageOut
" map "o" zoomPageIn
map "e" quit
map "d" createHint
map "f" createTabbedHint
map "o" moveTabLeft
map "p" moveTabRight


" Shift mappings
map "shift+i" quit
map "shift+f" lastActiveTab
map "shift+a" firstTab
map "shift+s" lastTab
map "shift+n" scrollFullPageDown
map "shift+m" scrollFullPageUp
"map "shift+m" scrollPageUp
map "shift+r" closeTabsToRight
map "shift+z" lastClosedTabBackground
map "shift+w" closeTabLeft
map "shift+e" closeTabRight
map "shift+z" lastClosedTab
map "shift+d" parentDirectory
map "shift+g" topDirectory
map "shift+z" lastClosedTabBackground
map "shift+h" topDirectory
map "shift+j" goBack
map "shift+k" goForward

" G multi binds
map "g g" showsVimrc

" Amazing navigation
" map "w" moveTabRight
" map "q" moveTabLeft
map "s" nextTab
map "a" previousTab
map "b" scrollToBottom
map "n" scrollToTop

map ":" toggleReader
map "w" toggleReader

" Settings
let blacklists = ["*://codepen.io/*", "*://draw.io/*", "*://glitch.com/*", "*://*slack.com/*", "*://codesandbox.io/*", "*://codewars.com/*", "*://discordapp.com/*", "://gitter.im/*"]
```

```css
/* sVim CSS settings */
@-webkit-keyframes fadein {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}

#sVim-command {
  -webkit-animation: fadein 0.2s !important;
  -webkit-appearance: none !important;
  background-color: rgba(0, 0, 0, 0.8) !important;
  background-position: none !important;
  background-repeat: none !important;
  border-radius: 0 !important;
  border: 0 !important;
  box-shadow: none !important;
  box-sizing: content-box !important;
  color: #ffffff !important;
  display: none;
  font-family: "Helvetica Neue" !important;
  font-size: 13px !important;
  font-style: normal !important;
  left: 0 !important;
  letter-spacing: normal !important;
  line-height: 1 !important;
  margin: 0 !important;
  min-height: 0 !important;
  outline-style: none !important;
  outline: 0 !important;
  padding: 2px 0 0 10px !important;
  position: fixed !important;
  right: 0 !important;
  text-align: start !important;
  text-indent: 0px !important;
  text-shadow: none !important;
  text-transform: none !important;
  vertical-align: none !important;
  width: 100% !important;
  word-spacing: normal !important;
  z-index: 2147483647 !important;
}

/*
.sVim-hint {
  background-color: #FFFF01;
  color: #000000;
  font-size: 10pt;
  font-family: monospace;
  line-height: 10pt;
  padding: 0px;
  opacity: 0.7;
}
*/

sVim-hint {
   background-color: #df6f00;
   font-weight: bold;
   opacity: 1;
   padding: 1px;
   text-shadow: 0 0 2px black;
}

.sVim-hint.sVim-hint-form {
  background-color: #3efeff;
}

.sVim-hint.sVim-hint-focused {
  opacity: 1;
  font-weight: bold;
}
```

```bash
# CLI tools I use
# Brew (/usr/local/bin)
agda
antibody
aom
bash
bat
cabal-install
cairo
cloc
clojure
cmake
dhall
diff-so-fancy
direnv
dry
emacs
exa
ffmpeg
flac
fnm
fontconfig
freetype
frei0r
fribidi
fzf
gdbm
gettext
ghc
giflib
git
glib
gmp
gnutls
go
goku
graphite2
harfbuzz
httpie
hub
hugo
hyperfine
icu4c
idris
jemalloc
joker
jpeg
jq
kubernetes-cli
lame
leptonica
libass
libbluray
libevent
libffi
libidn2
libogg
libpng
libsamplerate
libsndfile
libsoxr
libtasn1
libtermkey
libtiff
libunistring
libuv
libvorbis
libvpx
libvterm
little-cms2
loc
lua
luajit
lzo
mitmproxy
msgpack
mysql
neovim
nettle
node
oniguruma
opencore-amr
openjpeg
openssl
opus
p11-kit
pcre
pcre2
perl
pixman
pkg-config
postgresql
protobuf
python
python@2
readline
ripgrep
rlwrap
rtmpdump
rubberband
rustup-init
screenfetch
sdl2
snappy
speex
sqlite
tesseract
theora
tree
unbound
unibilium
up
watchexec
webp
wget
wifi-password
x264
x265
xvid
xz
yarn

# Go (~/go/bin)
2048-ai
alfred
alfred-awesome-lists
alfred-gcal
aligncheck
asmfmt
bat
caddy
ccat
chroma
client
cobra
cowsay
cowthink
cowyo
croc
deadcode
dep
depth
devd
dlv
domaincoloring
dupl
ecsy
elvish
errcheck
fibutil
fillstruct
fuzzy-cached
fuzzy-simple
gas
gb
gb-vendor
gin
github-release
go-bindata
go-langserver
go-outline
Go-Package-Store
go-pry
go-search
go-symbols
goalfred
gocode
goconst
gocyclo
godef
godoc
gogetdoc
goimports
golang-restapi
golint
gometalinter
gomodifytags
gopkgs
goplay
gops
gore
gorename
goreturns
gorram
gosimple
gotags
gotests
gotop
gotype
gotype-live
gowebapp
guru
hey
httplab
httpstat
impl
ineffassign
interfacer
jump
lf
license-up
lll
markdown-parser
md-to-alfred
md-to-list-filter
megacheck
misspell
modd
motion
muffet
multic
ng
nikitavoloboev
pigeon
playgo
primitive
protoc-gen-go
pullkee
pxl
rayito
rclone
reflex
richgo
safesql
serve
server
shfmt
slicer
snake-game
static-docs
staticcheck
structcheck
task
Tasks
thyme
unconvert
unparam
unused
usql
varcheck
weather

# Rust (~/.cargo/bin)
cargo
cargo-fmt
karaconv
loc
rls
rust-gdb
rust-lldb
rustc
rustdoc
rustfmt
rustup

# Yarn Global (/usr/local/bin)
create-react-app
dnd
do-not-disturb
eslint
fkill
knex
node-gyp
nodemon
npm
npx
ts-node
tsc
tslint
tsserver
prettier
qnm
webpack
webpack-dev-server
```
