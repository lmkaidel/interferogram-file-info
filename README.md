# interferogram-file-info
table of interferogram files and observations 
this table includes all information needed to order identical interferograms from Alaska Satellite Facility (https://search.asf.alaska.edu/#/)
column names: order_of_process	date_i	date_f	year	location	lat	lon	coherence_avg	coherence_med	coherence_std	lvangle	phase wraps	dist	fringe_spacing	file_name
column descriptions: [order in which the interferogram was processed] [initial date of SAR image aquisition] [final date of SAR image aquisition] [year of aquisition] [geographic location name] [center latitude] [center longitude] [average coherence value of measurment area] [median coherence value of measurment area] [standard deviation of coherence value of measurment area] [elevation angle] [number of phase wraps] [lenght of measurement area] [fringe spacing] [default name of file]
column units: [integer] [datetime] [datetime] [year integer] [text] [decimal degrees] [decimal degrees] [float number range 0-1] [float number range 0-1] [float number] [radians] [integer] [meters] [fraction fringe per meter] [text]
