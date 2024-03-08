# Finding opengl, glfw, glew, glut, and possibly freetype and even freeglut
find_package(glfw3 REQUIRED)
find_package(OpenGL REQUIRED)
# find_package(GLEW REQUIRED)
# find_package(GLUT REQUIRED)
find_package(glm REQUIRED)
find_package(Vulkan REQUIRED)


add_executable(${PROJECT_NAME} main.cpp)

target_link_libraries(
    ${PROJECT_NAME}
    glfw
    ${OPENGL_gl_LIBRARY}
    Vulkan::Vulkan
)
