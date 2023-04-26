include(${CMAKE_SOURCE_DIR}/cmake/copy.cmake)
include(${CMAKE_SOURCE_DIR}/cmake/texture.cmake)

copy(assets_copy ${CMAKE_BINARY_DIR}/assets
  cube.obj
  plane.obj
  wolf.obj
  pirate.dae
  wolf.dae
  UbuntuMono-Regular.ttf
)

texture(assets_texture BC7
  basecolor.png
  metallic.png
  normal.png
  roughness.png
  negx.png
  negy.png
  negz.png
  posx.png
  posy.png
  posz.png
)
