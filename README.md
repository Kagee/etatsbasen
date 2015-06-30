# Etatsbasen

Verktøy til å eksportere fra https://github.com/mimesbronn/etatsbasen-data
Lager import som er egnet for import til alaveteli.

## Installasjon

```sh
$ git clone https://github.com/mimesbronn/etatsbasen.git
$ cd etatsbasen
$ sudo npm install -g
$ git clone https://github.com/mimesbronn/etatsbasen-data.git
$ cd etatsbasen-data
$ etatsbasen
```

## Opsjoner

Opsjoner skal ikke være nødvendig. Den har default verdier som er egnet for Mimes brønn

```sh
$ etatsbasen -h
 Usage: etatsbasen [options]

  -c [all|[c1,c2,..]]   Categories to include (defaults: `12,14,17,18,27,33,38,66,68,76`)
  -f [file]             File to read from (defaults: `etatsbasen.csv`)
  -o h1[,h2,h3]         Include only these headers in output (id or name)
  -v                    Print version.
  -h                    Write this help.
```
