_sources = [
  'landscape.cc',
  'sphere.cc',
  'floor.cc',
  'floor-edge.cc',
  'jpeg-texture.cc',
  'main.cc',

  shaders['landscape']['vert'],
  shaders['landscape']['frag'],
  shaders['color']['frag'],
  shaders['sky']['frag'],
  shaders['texture']['frag'],
  shaders['default']['vert'],
  shaders['floor']['vert'],
  shaders['floor']['frag'],
]

_dependencies = [
  zukou_dep,
  jpeg_dep,
]

executable(
  'zennist',
  _sources,
  install: true,
  cpp_args: ['-include', 'constants.h'],
  dependencies: _dependencies,
)
