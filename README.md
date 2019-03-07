# Empty new tab page

> Makes the new tab page empty for non-distracting purposes

## What is this?

Maybe you have ADHD and you feel the Chrome new tab page is too distracting for
you. So you use
[an extension](https://chrome.google.com/webstore/detail/empty-new-tab-page/dpjamkmjmigaoobjbekmfgabipmfilij)
to make it blank, like the old days. But lately, you've been getting a bit
security paranoid. So you don't want others having access to your webpages.
Others, as in Chrome extensions.

## But it's open source! I'm safe.

Maybe you are. But maybe the open sourced code on GitHub isn't the one actually
running under your Chrome extension.

## Yes, but mother Google has purged evil extensions for me.

That is a good point. But just in case it isn't, this thing is for you.

## So, why should I trust your extension over all the others?

Don't do it. This is the purpose of this little guide. Download the source 
code for this extension, read it (it's 5 LOC) and install it locally for yourself. 

## How to install

1. Download or clone the repo. Actually, two files are needed, [`manifest.json`](manifest.json) and [`newtab.html`](newtab.html).
1. Go to Chrome extensions and enable `Developer Mode` on the top right of the blue bar.
1. Click `Load unpacked` and choose the directory of the extension.
1. Done.

## License

MIT
