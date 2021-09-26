# Glitch.com WikiJs files for version 2.5.219

Usage: 

1) Open terminal on new private node project on glitch.com
2) Paste and Run the following command in glitch.com project console:


v3.0:

```rm -rf ../app/* && rm -rf ../app/.* || echo no hidden folders && pnpm prune || echo skipping prune && wget https://github.com/callousrow/wikibackup/releases/download/3.0/wiki-js-2.5.219-lite.tar.gz && tar xzf wiki-js-2.5.219-lite.tar.gz && rm -rf wiki-js-2.5.219-lite.tar.gz && pnpm install -P || echo packages will complete on server start && wget https://github.com/callousrow/wikibackup/releases/download/3.0/config.yml && pnpm install nanoid luxon custom-error-instance || echo stray packages already installed && pnpm rebuild sqlite3  && mkdir .data && refresh```

Sometimes the pnpm install won't work right so you might have to rebuild: ```pnpm rebuild``` or install any missing packages manually... If this is the case then just copy and run the last part of the command to finish the wikijs setup:

```pnpm rebuild sqlite3  && mkdir .data && refresh```

Big thanks to ihack2712: https://support.glitch.com/t/wiki-js-org-on-glitch/23521
