# 0.2.0.1 (2023-03-12)

* Fix build on GHC 9.4 and 9.6 by adding `UndecidableInstances`.

# 0.2.0 (2021-10-11)

* Add a type role for `Fin`, which was formerly `Coercible` in unsafe ways.
* Fix the `Read` instance erroring on out-of-range values; it now merely fails.
* Add `Attenuable` instances for `attenuation-0.2.0`.

# 0.1.0.0 (2021-09-07)

Initial version.
