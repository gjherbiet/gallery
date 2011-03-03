	gallery [-h] [-V] [-d] [-v]
	    [-t <Gallery title>] [-o <output_dir>]
	    [-p <PAGINATE_NUMBER>] [-c <COLUMNS_NUMBER>] [-l]
	    [-s <THUMBNAILS_MAX_SIZE>] [-S <PICTURES_MAX_SIZE>]
	    [<pictures_dir>]

	  Generates a static HTML gallery of photos based on the JPG files contained
	  in the given directory.

	  Note: If your system has the non-enhanced version of 'getopt' (which is the
	  case by default on BSD systems, including Mac OS), only the short version
	  of the following options are available.

	     -h          : Print this help, then exit.
	     -V          : Print the software version, then exit.
	     -d          : Extended information about the script function.
	     -v          : Display a summary of the executed operations.

	     -t          : Galery title. Defaults to the name of the inut directory.
	     -o          : Name of the ouput direcory, created under the current
	                   working directory. Defaults to a path-safe version of
	                   the gallery title or to "gallery" if no title is specified.

	    -p           : Paginate the gallery index by displaying a maximum of
	                   PAGINATE_NUMBER pictures per index page.
	                   Defaults to 30 pictures per page.
	    -c           : Display COLUMNS_NUMBER columns of pictures in the index file.
	                   Defaults to 3 pictures per row.
	    -l           : Use a light theme instead of the default dark theme.

	    -s           : Set the longest dimension of thumbnails to THUMBNAILS_MAX_SIZE.
	                   Default is 200px.
	    -S           : Set the longest dimension of pcitures to PICTURES_MAX_SIZE
	                   Default is 800px.

	   pictures_dir  : The directory containing the JPG files that will be
	                   used in the gallery generation. Defaults to the current
	                   working directory.

