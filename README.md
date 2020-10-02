# oracle-cloud

Populate env.sh with a value for compartment ocid and a value for region to use as default
values for when those values are not included as command line arguments.

Then execute the script. The options for command line arguments are as follows:
<pre>
Flag                          Description                                       Usage

-n          Specify the name of the image whose OCID you want to get.           ./get_image_ocid -n "Oracle Linux 7 - HPC Cluster Networking Image"
-h          Show options.                                                       ./get_image_ocid -h
-l          Show names of listings for images.                                  ./get_image_ocid -l
-m          Set visibility to marketplace catalog listings.                     ./get_image_ocid -m
                 If unspecified, visibility is set to standard image listings.
</pre>