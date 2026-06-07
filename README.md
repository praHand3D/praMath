# praMath

Math library for the [praHand3D](https://github.com/praHand3D) engine. Used as a git submodule.

## Structures

- `Vec3` — 3D vector (x, y, z)
- `Vec4` — 4D vector / quaternion (x, y, z, w)
- `Transform` — position (Vec3) + rotation (Vec4) + scale (Vec3)
- `Matrix4x4` — 4×4 float matrix

## API

**Vec3**
```cpp
Vec3::normalize(v)
Vec3::cross(v1, v2)
Vec3::dot(v1, v2)
// operators: +, -, * float, / float
```

**Vec4**
```cpp
Vec4::multiplyQuaternions(q1, q2)
```

**Matrix4x4**
```cpp
multiply(m1, m2)
buildModelMatrix(transform, pivot)
buildTranslationMatrix(position)
buildRotationMatrix(rotation)
buildScaleMatrix(scale)
```

## Usage (as submodule)

```bash
git submodule add git@github.com:praHand3D/praMath.git external/praMath
```

```cmake
add_subdirectory(external/praMath)
target_link_libraries(your_target math)
```

```cpp
#include "math/Vec.h"
#include "math/Matrix.h"
#include "math/Transform.h"
```

## License

[MIT](LICENSE)