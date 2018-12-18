# Homework_3_1
Homework 3.1

Els paràmetres del fitxer *usb_cam-test.launch* són privats per a cada node:

En el node *usb_cam*, trobem els paràmetres:

- *video_device*, amb el valor assignat /dev/video0
- *image_width*, amb un valor de 640
- *image_height*, amb un valor de 480
- *pixel_format*, amb el valor assignat de yuyv
- *camera_frame_id*, amb el valor usb_cam
- *io_method*, amb el valor mmap

En el node *image_view* trobem els paràmetres següents:

- *autosize*, amb un valor de true
