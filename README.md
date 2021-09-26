# Glitch.com WikiJs files for version 2.5.219

Usage: 

1) Open terminal on new private node project on glitch.com
2) Paste and Run the following command in glitch.com project console:


v1.0:
```rm -rf ../app/* && pnpm prune && wget https://github.com/callousrow/wikibackup/releases/download/1.0/wiki-js-2.5.219-lite.tar.gz && tar xzf wiki-js-2.5.219-lite.tar.gz --exclude node_modules && rm -rf wiki-js-2.5.219-lite.tar.gz && pnpm install -P && pnpm rebuild sqlite3 && rm config.sample.yml && wget https://github.com/callousrow/wikibackup/releases/download/1.0/config.yml && mkdir .data && refresh```
