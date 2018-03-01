# unix-shell-script

shell script that searches through a directory tree looking for images of a specified
type (gif, png, tiff, etc), convert all the images into JPEG format in a specified output directory, and
create a web page called pic_name_xx.html that contains links to the converted images in the form of
small "thumbnail" images. In other words, the website would basically be a presentation of all the


thumbnails of the images processed. Here's what the command line for your script will look like:


create_images input_dir output_dir 'pattern_1' 'pattern_2' ... 'pattern_n'
