# 需剥离的函数

1. camera::Camera *cam = new camera::Camera(320, 240, image::FMT_RGB888);
    1. hmirror
    2. vflip
    3. restart
    4. set_resolution
    5. image::Image *img = cam->read();
    6. img->to_jpeg
2. mmf_invert_format_to_mmf
3. mmf_del_venc_channel
4. mmf_add_venc_channel
5. mmf_venc_push
6. mmf_venc_pop
7. mmf_venc_free
8. mmf_deinit