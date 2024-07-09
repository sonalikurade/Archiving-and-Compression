# Archiving and compression
## Archiving
Archiving is the process of combining multiple files into a single package called an archive.
## tar Command(Tape Archive) is used for archiving
### Syntax
tar [option] [name of the file ] path( where you want to archive the file)

### Options:
* c create & archive(create tar file)
* -f filename
* -v view/verbose
* -t list contents from the archive
* -x extract from archive
* -C copy content from the archive to another directory
## Compression tools
If you already have a tar file or archive file then use separate tools

gzip (z) .gz
to zip the file — → gzip file.tar

to unzip the file — →gunzip file.tar.gz

2. bzip2 (j) .bz2

to zip the file — → bzip2 file.tar

to unzip the file — →bunzip file.tar.bz2

3. xzip (J) .xz

to zip the file — → xz file.tar

to unzip the file — →unxz file.tar.xz