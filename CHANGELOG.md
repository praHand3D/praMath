# Changelog praMath

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


[0.1.0]: https://github.com/praHand3D/praMath/releases/tag/v0.1.0
[Unreleased]: https://github.com/praHand3D/praMath/compare/v0.1.0...HEAD