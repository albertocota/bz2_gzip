###GZIP & BZ2 reader###
------
To generate zip files using the reader.compressed modules

Change directory into reader module

`cd reader`

Create gzip & bz2 compressed files

`python -m reader.compressed.bzipped test.bz2 'data bz2'`

`python -m reader.compressed.gzipped test.gzip 'data gzip'`

Change directory to project's root

`cd ..`

Read files using the reader module

`python reader reader/data.bz2`

`python reader reader/data.gzip`

