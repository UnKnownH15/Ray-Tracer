cmake_minimum_required(VERSION 4.0)
project(RIOW)

set(CMAKE_CXX_STANDARD 20)

add_executable(RIOW main.cpp
        vec3.h
        stb_image_write.h
        color.h
        ray.h
        hittable.h
        sphere.h
        hittable_list.h
        cp.cpp
        rtweekend.h
        interval.h
        camera.h
)
