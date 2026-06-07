# Changelog praMath

## [2.0.0] - 2026-06-07
### Changed
- Update `buildModelMatrix` function to use pivot point

## [1.0.0] - 2026-06-06
### Added
- Move tests/ from `praHangine` repo to `praMath` repo.

## [0.1.0] - 2026-06-05
### Added
- Simple math structures with methods
  - **struct:**
    - `Vec3`,
    - `Vec4`,
    - `Matrix4x4`,
    - `Transform`.
  - **Methods:**
    - add, sub, mul, div,
    - dot, cross, norm,
    - `multiply` two 4x4 matrices,
    - `multiplyQuaternions` - multiply two quaternions (Vec4),
    - `buildModelMatrix` - builds a model matrix from a transform,
    - `buildTranslationMatrix` - builds a translation matrix from a vector,
    - `buildRotationMatrix` - builds a rotation matrix from a vector,
    - `buildScaleMatrix` - builds a scale matrix from a vector.


[Unreleased]: https://github.com/praHand3D/praMath/compare/v2.0.0...HEAD
[2.0.0]: https://github.com/praHand3D/praMath/releases/tag/v2.0.0
[1.0.0]: https://github.com/praHand3D/praMath/releases/tag/v1.0.0
[0.1.0]: https://github.com/praHand3D/praMath/releases/tag/v0.1.0