add_library(lgncopenapi SHARED 
    src/lgnc_directaudio.c
    src/lgnc_directvideo.c
    src/lgnc_egl.c
    src/lgnc_gamepad.c
    src/lgnc_system.c
)
set_target_properties(lgncopenapi PROPERTIES SOVERSION 2)
target_include_directories(lgncopenapi PUBLIC include)