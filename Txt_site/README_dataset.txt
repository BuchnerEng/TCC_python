WOOD IMAGE DATABASE

IMAGES directory contains 839 images of spruce wood.
The images are in ppm format (see PPM.TXT).
They are RBG color images with 8 bits per channel.
The size of images is 488 (H) by 512 (V) pixels.
The images are gzip-compressed.
The total amount of data in the directory is about 360 Mbytes,
uncomressed about 630 Mbytes.

Each of the images has been divided to rectangular regions, which 
have been manually labelled. The labels are stores in file
manlabel.txt (1 Mb). One row corresponds to one rectangular sample.
The format of the file is:

	image min_y min_x max_y max_x label
e.g.
	st1015  273  305  333  365 dry_knot

where min_y and min_x define the upper left corner of a rectangular 
region and mix_y and max_x define the lowar right corner.
One rectangle corresponds to about 2.5 x 2.5 cm2 area of wood surface.

The number appearing in each of the images refers to a numbered board
stored in our laboratory. If you need any verifying of the defects,
do not hesitate to contact us.

The imaging has been done under controlled halogen illumination under
color temperature of 3200 K. The error caused by the illumination
changes is less than 1%. Color reference images have been taken regularly
during the imaging.

NOTE!
If you use these images, please remember to refer to the 
origin of the database.

Good references are:

"Kauppinen H. and Silven O.: A Color Vision Approach for Grading Lumber. In Theory & Applications of Image Processing II - Selected papers from the 9th Scandinavian Conference on Image Analysis (ed. G. Borgefors), World Scientific, pp. 367-379 1995."

"Silven O. and Kauppinen H.: Recent Developments in Wood Inspection. International Journal on Pattern Recognition and Artificial Intelligence, IJPRAI, pp. 83-95, 1996."


Olli Silven       olli@ee.oulu.fi
Hannu Kauppinen    hsk@ee.oulu.fi

University of Oulu
Department of Electrical Engineering
Computer Laboratory
FIN-90570 OULU
Finland
