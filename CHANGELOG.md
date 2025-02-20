0.5.5 / 2019-09-14
==================
 * fix: use mongodb driver 3.3.x for MongoDB 4.2 support

0.5.4 / 2019-09-14
==================
 * fix: correct download path #38 #37 [ProtonGustave](https://github.com/ProtonGustave)

0.5.3 / 2019-09-11
==================
 * fix: make --help check more robust #32 [jordonbiondo](https://github.com/jordonbiondo)

0.5.2 / 2019-03-14
==================
 * fix: correct dbPath on windows #26

0.5.1 / 2019-03-14
==================
 * fix: support absolute paths as args to --dbpath #26 [fiorillo](https://github.com/fiorillo)

0.5.0 / 2019-03-13
==================
 * BREAKING CHANGE: use MongoDB 4.0.6 by default
 * fix: clean error message when address is already in use #21
 * fix: print readable error if --mongod not found #25
 * fix: use custom --help to avoid limitations in commanders help output #24
 * docs: from `--dbPath` to `--dbpath` #23 [isghe](https://github.com/isghe)

0.4.0 / 2018-11-26
==================
 * feat: add --host option to override default mongodb ip binding #18 #16 [chaiwa-berian](https://github.com/chaiwa-berian)

0.3.3 / 2018-11-22
==================
 * docs: notes on connection string to support Windows users #16 [chaiwa-berian](https://github.com/chaiwa-berian)

0.3.2 / 2018-11-19
==================
 * fix: correct dbpaths and hostname on Windows #15 #8 [chaiwa-berian](https://github.com/chaiwa-berian)

0.3.1 / 2018-11-17
==================
 * fix: correct default dbpath on Windows #14 #13 [chaiwa-berian](https://github.com/chaiwa-berian)

0.3.0 / 2018-11-04
==================
 * feat: add --dbPath option to specify a path for run-rs to use as a data director #12 [fruschitaly](https://github.com/fruschitaly)
 * feat: add the ability to specify the starting port #11 [lineus](https://github.com/lineus)

0.2.2 / 2018-10-04
==================
 * feat: add -n, --number option to specify number of mongods to start #9

0.2.1 / 2018-09-08
==================
 * fix: add --mongod option to support using a pre-installed version of mongodb #6

0.2.0 / 2018-09-03
==================
 * feat: add windows 10 support #5 #2 [Fonger](https://github.com/Fonger)
