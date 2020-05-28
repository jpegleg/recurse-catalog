# recurse-catalog
recata: Cataloging data sets in csv format as date,hash,url,uri,dataset recursively for a given directory.
source-data: Recording the URL and the URI where the data came from
recurse-catalog: clones the git repos and is a wrapper for recata and source-data 

Usage of recurse-catalog:

# call program # target the local code repo # repo url # repo uri context # realm keyword
recurse-catalog /mnt/repo/jpegleg/ https://github.com /jpegleg/fe-html-template jpegleg-github-dev

There will be several .dat and .csv files output and the recurse-catalog. 
The load.csv is truncated each time while the others are cataloged by timestamp.
The load.csv is indended to be shipped off to a database for tracking etc,
while the timestamped data files are packed up into a local copy.
