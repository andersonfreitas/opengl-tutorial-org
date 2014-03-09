# OpenGL Tutorial - Examples files

These are the example files from [www.opengl-tutorial.org](http://www.opengl-tutorial.org) adapted to work on Mac OS 10.9.

I've first downloaded **OpenGL-tutorial_v0014_33.zip** from [source](http://www.opengl-tutorial.org/wp-content/uploads/2011/05/OpenGL-tutorial_v0014_33.zip)

It compiles and links OK with cmake, but when you try to run any of examples get a message saying that your MBP doesn't support OpenGL 3.3 and you should use the 2.1 version instead.

So I've updated some files in order to compile on a recent system, since most MBPs [**are**](http://support.apple.com/kb/HT5942) [**compatible**](https://developer.apple.com/graphicsimaging/opengl/capabilities/index.html) with at least OpenGL 3.3.

## Building

    mkdir build && cd build
    cmake ..
    make
    chmod +x *.sh
    ./launch-XXXX

## Status

 * [PASS] launch-playground.sh
 * [PASS] launch-tutorial01_first_window.sh
 * [PASS] launch-tutorial02_red_triangle.sh
 * [PASS] launch-tutorial03_matrices.sh
 * [PASS] launch-tutorial04_colored_cube.sh
 * [PASS] launch-tutorial05_textured_cube.sh
 * [FAIL] launch-tutorial06_keyboard_and_mouse.sh
 * [FAIL] launch-tutorial07_model_loading.sh
 * [FAIL] launch-tutorial08_basic_shading.sh
 * [FAIL] launch-tutorial09_AssImp.sh
 * [FAIL] launch-tutorial09_several_objects.sh
 * [FAIL] launch-tutorial09_vbo_indexing.sh
 * [FAIL] launch-tutorial10_transparency.sh
 * [FAIL] launch-tutorial11_2d_fonts.sh
 * [FAIL] launch-tutorial12_extensions.sh
 * [FAIL] launch-tutorial13_normal_mapping.sh
 * [FAIL] launch-tutorial14_render_to_texture.sh
 * [FAIL] launch-tutorial15_lightmaps.sh
 * [FAIL] launch-tutorial16_shadowmaps.sh
 * [FAIL] launch-tutorial16_shadowmaps_simple.sh
 * [FAIL] launch-tutorial17_rotations.sh
 * [FAIL] launch-tutorial18_billboards.sh
 * [FAIL] launch-tutorial18_particles.sh
 * [FAIL] launch-misc05_picking_BulletPhysics.sh
 * [FAIL] launch-misc05_picking_custom.sh
 * [FAIL] launch-misc05_picking_slow_easy.sh
