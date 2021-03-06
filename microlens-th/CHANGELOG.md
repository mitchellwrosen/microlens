# 0.4.1.1

* Bumped the upper bound of template-haskell, as requested by @ocharles.

# 0.4.1.0

* Added `abbreviatedFields`.

# 0.4.0.1

* Ported a lens commit that (probably) makes lens generation deterministic. See [this issue](https://github.com/aelve/microlens/issues/83).

# 0.4.0.0

* Added `makeClassy` (and `createClass`).

# 0.3.0.2

* Added forgotten copyright/authorship information.

# 0.3.0.1

* The library is now compatible with GHC 8.

# 0.3.0.0

* `SimpleGetter` and `SimpleFold` are no longer reexported.

# 0.2.2.0

* Moved `Getter` and `Fold` from this package to microlens (they're in `Lens.Micro.Extras`).

# 0.2.1.3

* Bumped template-haskell (so that the package would compile with GHC HEAD).

# 0.2.1.2

* Bumped microlens version to be able to use `phantom`.

# 0.2.1.1

* Bumped microlens version again.

# 0.2.1.0

* Bumped base version.
* Bumped microlens version.

# 0.2.0.0

* `createClass` was removed because it doesn't seem to be useful without `lensClass`.
* `defaultFieldRules` isn't exported anymore – use `camelCaseFields`.

# 0.1.2.0

* Package now compiles with `-O2` and other optimisations by default.

# 0.1.1.0

* Added `makeLensesFor` (and `lensRulesFor`).

# 0.1.0.1

* Wrote a bit of documentation.

# 0.1.0.0

Initial release.
