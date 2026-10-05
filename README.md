<!-- tyhp-readme:start -->
# tyhpdef/symfony-monolog-bridge

Tyhp type definitions for `symfony/monolog-bridge` `7.4.18`.

```bash
composer require --dev tyhpdef/symfony-monolog-bridge:7.4.18
```

This is a metapackage. Composer also installs `tyhpdef/symfony-monolog-bridge-impl` (type files).
Require **this** name, not `tyhpdef/symfony-monolog-bridge-impl`.

See https://tyhplang.com.

## Maintain `symfony/monolog-bridge`? Ship the types yourself

If you are a Packagist maintainer of `symfony/monolog-bridge`, you can take over these
types.

Copy `_tyhpdef/` from **`tyhpdef/symfony-monolog-bridge-impl`** (Apache-2.0; keep the `NOTICE`).
Then either:

1. **Bundle** the files in `symfony/monolog-bridge` and set `extra.tyhp.package` on
   that `composer.json`, plus
   `"replace": { "tyhpdef/symfony-monolog-bridge": "self.version" }`, or
2. **Publish a sibling** types package under your vendor, versioned with
   `symfony/monolog-bridge` (same `X.Y.Z`). Set `extra.tyhp.package` there,
   `require` `symfony/monolog-bridge` with a real constraint,
   `"replace": { "tyhpdef/symfony-monolog-bridge": "self.version" }`, and set
   `extra.tyhp.tyhpdef` on `symfony/monolog-bridge` to your sibling’s Composer name.

Ship that to Packagist first, then open an issue:

https://github.com/tyhpproject/tyhp-runtime-src/issues/new?template=tyhpdef-ownership.yml

We verify Packagist ownership and that the types parse and cover the PHP
API, then stop publishing community tags for those versions. We do not
transfer the `tyhpdef/symfony-monolog-bridge` Packagist name.

Full process: `TYHPDEF_OWNERSHIP.md` in
https://github.com/tyhpproject/tyhp-runtime-src
<!-- tyhp-readme:end -->
