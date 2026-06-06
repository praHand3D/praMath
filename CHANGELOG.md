# Changelog praMath

## [Unreleased]
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
