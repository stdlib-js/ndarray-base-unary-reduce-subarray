# CHANGELOG

> Package changelog.

<section class="release" id="unreleased">

## Unreleased (2025-08-15)

<section class="features">

### Features

-   [`998b3ba`](https://github.com/stdlib-js/stdlib/commit/998b3ba4e628e6d8564c6b33fe41925da2046b41) - add missing kernels to `ndarray/base/unary-reduce-subarray` [(#6421)](https://github.com/stdlib-js/stdlib/pull/6421)
-   [`935f698`](https://github.com/stdlib-js/stdlib/commit/935f698bd565928d3fc862dfdff14ab0e56aa478) - add initial implementation for `ndarray/base/unary-reduce-subarray`

</section>

<!-- /.features -->

<section class="bug-fixes">

### Bug Fixes

-   [`5efa5d7`](https://github.com/stdlib-js/stdlib/commit/5efa5d79b4e9348e431e35cbd2657982a78455cc) - address assignment bug
-   [`a300862`](https://github.com/stdlib-js/stdlib/commit/a300862d4f05d4d8bd85f1e235db93ad5d35a767) - address increment bugs
-   [`fab9873`](https://github.com/stdlib-js/stdlib/commit/fab9873a907807195f2f6673b5b97f09e383bd69) - address index bug
-   [`9bc10d4`](https://github.com/stdlib-js/stdlib/commit/9bc10d4dc2b9afe6b55ca2b6e17c165e9dd2a88d) - use resolved order when computing loop variables
-   [`8722299`](https://github.com/stdlib-js/stdlib/commit/8722299df603836eaf1aba2404e833f77db4ed0b) - use computed order
-   [`f3e3561`](https://github.com/stdlib-js/stdlib/commit/f3e3561a46cca1fbb13c0a1b5eb5f5475ef9b032) - address off-by-one error
-   [`cdc66ce`](https://github.com/stdlib-js/stdlib/commit/cdc66ce1876b95dd8c23aa2f869aebe9b842e86e) - remove unused parameters
-   [`0ede0da`](https://github.com/stdlib-js/stdlib/commit/0ede0dafa46ddea7dfce7be63250ca9ae0c1c546) - add missing imports in `ndarray/base/unary-reduce-subarray` [(#6642)](https://github.com/stdlib-js/stdlib/pull/6642)
-   [`f0d205d`](https://github.com/stdlib-js/stdlib/commit/f0d205d7073055c7a69f1ba7ccee95671ab762ba) - address indexing error
-   [`5768926`](https://github.com/stdlib-js/stdlib/commit/5768926be4fb253947f5d44bcf6b9d8bb5c75274) - update error message
-   [`7378f4d`](https://github.com/stdlib-js/stdlib/commit/7378f4db96fc059523a6f181388aa8f4fa202675) - ensure support when providing no dimensions to reduce
-   [`91778b7`](https://github.com/stdlib-js/stdlib/commit/91778b7ca6ae2c6ee0c6017687426c3952d90098) - handle scenario where a core dimension is zero

</section>

<!-- /.bug-fixes -->

<section class="commits">

### Commits

<details>

-   [`5efa5d7`](https://github.com/stdlib-js/stdlib/commit/5efa5d79b4e9348e431e35cbd2657982a78455cc) - **fix:** address assignment bug _(by Athan Reines)_
-   [`19385a6`](https://github.com/stdlib-js/stdlib/commit/19385a661da9d3460d7328e456b5b59347c908f7) - **docs:** fix example _(by Athan Reines)_
-   [`a300862`](https://github.com/stdlib-js/stdlib/commit/a300862d4f05d4d8bd85f1e235db93ad5d35a767) - **fix:** address increment bugs _(by Athan Reines)_
-   [`fab9873`](https://github.com/stdlib-js/stdlib/commit/fab9873a907807195f2f6673b5b97f09e383bd69) - **fix:** address index bug _(by Athan Reines)_
-   [`c8ed1f9`](https://github.com/stdlib-js/stdlib/commit/c8ed1f99772d36d99cf0d836a506c3c83f58c02c) - **docs:** fix description _(by Athan Reines)_
-   [`30e17f4`](https://github.com/stdlib-js/stdlib/commit/30e17f4a8ea63e7cad77946fc946a7c587781bb9) - **docs:** update descriptions _(by Athan Reines)_
-   [`9bc10d4`](https://github.com/stdlib-js/stdlib/commit/9bc10d4dc2b9afe6b55ca2b6e17c165e9dd2a88d) - **fix:** use resolved order when computing loop variables _(by Athan Reines)_
-   [`8722299`](https://github.com/stdlib-js/stdlib/commit/8722299df603836eaf1aba2404e833f77db4ed0b) - **fix:** use computed order _(by Athan Reines)_
-   [`f3e3561`](https://github.com/stdlib-js/stdlib/commit/f3e3561a46cca1fbb13c0a1b5eb5f5475ef9b032) - **fix:** address off-by-one error _(by Athan Reines)_
-   [`9d6cd84`](https://github.com/stdlib-js/stdlib/commit/9d6cd84404f09e09f22721d4e3bd1d083b8f83b1) - **chore:** add TODO _(by Athan Reines)_
-   [`999b4d7`](https://github.com/stdlib-js/stdlib/commit/999b4d7f258e8c9c20ef474b1839f62a9481c652) - **docs:** update note _(by Athan Reines)_
-   [`a032199`](https://github.com/stdlib-js/stdlib/commit/a03219903da3dce11a6a290890078a969841e582) - **docs:** update description _(by Athan Reines)_
-   [`29a39e8`](https://github.com/stdlib-js/stdlib/commit/29a39e8cb6562c29d96a91b3969ef35ae85b661a) - **chore:** update copyright year _(by Athan Reines)_
-   [`cdc66ce`](https://github.com/stdlib-js/stdlib/commit/cdc66ce1876b95dd8c23aa2f869aebe9b842e86e) - **fix:** remove unused parameters _(by Athan Reines)_
-   [`0ede0da`](https://github.com/stdlib-js/stdlib/commit/0ede0dafa46ddea7dfce7be63250ca9ae0c1c546) - **fix:** add missing imports in `ndarray/base/unary-reduce-subarray` [(#6642)](https://github.com/stdlib-js/stdlib/pull/6642) _(by Muhammad Haris)_
-   [`f0d205d`](https://github.com/stdlib-js/stdlib/commit/f0d205d7073055c7a69f1ba7ccee95671ab762ba) - **fix:** address indexing error _(by Athan Reines)_
-   [`998b3ba`](https://github.com/stdlib-js/stdlib/commit/998b3ba4e628e6d8564c6b33fe41925da2046b41) - **feat:** add missing kernels to `ndarray/base/unary-reduce-subarray` [(#6421)](https://github.com/stdlib-js/stdlib/pull/6421) _(by Muhammad Haris)_
-   [`5768926`](https://github.com/stdlib-js/stdlib/commit/5768926be4fb253947f5d44bcf6b9d8bb5c75274) - **fix:** update error message _(by Athan Reines)_
-   [`bdf4246`](https://github.com/stdlib-js/stdlib/commit/bdf4246934e957faced935c2cda4b1f30b7ac9e9) - **refactor:** update error messages _(by Athan Reines)_
-   [`9934f2c`](https://github.com/stdlib-js/stdlib/commit/9934f2ceb44cbcdc02c27d9a1a5fc231e24b10ff) - **refactor:** only branch when `y` is backed by an accessor array _(by Athan Reines)_
-   [`7378f4d`](https://github.com/stdlib-js/stdlib/commit/7378f4db96fc059523a6f181388aa8f4fa202675) - **fix:** ensure support when providing no dimensions to reduce _(by Athan Reines)_
-   [`abbc923`](https://github.com/stdlib-js/stdlib/commit/abbc923faa3036bb6b2bce8446a56926ef26163d) - **docs:** add example _(by Athan Reines)_
-   [`91778b7`](https://github.com/stdlib-js/stdlib/commit/91778b7ca6ae2c6ee0c6017687426c3952d90098) - **fix:** handle scenario where a core dimension is zero _(by Athan Reines)_
-   [`9cb2473`](https://github.com/stdlib-js/stdlib/commit/9cb247321b8b2285713404fc4e43d43630163097) - **chore:** update directory list _(by Athan Reines)_
-   [`0fc4015`](https://github.com/stdlib-js/stdlib/commit/0fc401573e94e99adbd3c31d7067c28ee2d270a1) - **docs:** add README and repl help _(by Athan Reines)_
-   [`a331234`](https://github.com/stdlib-js/stdlib/commit/a33123481db5e24d5f0550b837b81bd0574d748e) - **test:** add initial test file _(by Athan Reines)_
-   [`6d21670`](https://github.com/stdlib-js/stdlib/commit/6d21670d117320f7bc77b2b3ad4ce2fc51dbdd75) - **chore:** update directory list _(by Athan Reines)_
-   [`935f698`](https://github.com/stdlib-js/stdlib/commit/935f698bd565928d3fc862dfdff14ab0e56aa478) - **feat:** add initial implementation for `ndarray/base/unary-reduce-subarray` _(by Athan Reines)_

</details>

</section>

<!-- /.commits -->

<section class="contributors">

### Contributors

A total of 2 people contributed to this release. Thank you to the following contributors:

-   Athan Reines
-   Muhammad Haris

</section>

<!-- /.contributors -->

</section>

<!-- /.release -->

