# mkvsetsubtitle

A quick and dirty Bash script to set the default subtitle language on all MKV files in the current directory.

## Requires

requires `mkvmerge` and `mkvpropedit` to be in your path from [MKVToolNix](https://mkvtoolnix.download)

### Install MKVToolNix via homebrew
`brew install mkvtoolnix`

# Getting Started
```
chmod +x mkvsetsubtitle
cp mkvsetsubtitle mkvfiles/

cd mkvfiles/
./mkvsetsubtitle eng

```