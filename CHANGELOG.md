- 0.1.5
    - Add `discreteBool :: Dec (a :~: b)` (GHC-7.8+)
    - Add `Show`, `Eq`, `Ord` `SBool b` instances.

- 0.1.4
    - Add `fromSBool` and `withSomeSBool`.

- 0.1.3.0
    - Add `reifyBool` and `reflectBool`.
    - Drop GHC-7.4 support (broken `PolyKinds`)

- 0.1.2.0
    - Enable `PolyKinds` on GHC >= 7.6
    - Add `sboolEqRefl :: SBoolI (a == b) => Maybe (a :~: b)`

- 0.1.1.0
    - Add `eqToRefl`, `eqCast`, `trivialRefl`
