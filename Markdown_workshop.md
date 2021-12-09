Data sets are the mainframe equivalent of files and folders on a PC. There are several types of mainframe data set, which are described in this article.

 ## Sequential file
The most basic type of mainframe data set is the sequential file, also known as the physical sequential file. It consists of a set of records of a fixed length (i.e. a number of characters). Each record occupies a new line on the file.
If you have a layout file, you can view the records in a formatted view.

## Partitioned Data Set
A partitioned data set (PDS) is like a folder which contains individual files called members. These members are essentially the same as physical sequential files, except their parameters, such as record length, are defined in the PDS. All members of a PDS therefore have the same parameters.

##VSAM file

A VSAM file (Virtual Storage Access Method) is a database consisting of two parts, a "data" file, consisting of records, and an "index" file. Several types of VSAM file exist and they differ in how the records are ordered and accessed. The most common are:

- ESDS (Entry-sequenced data set)  
In an ESDS the records are ordered in the order they are inserted to the database.
-KSDS (Key-sequenced data set)  
In a KSDS, each record is assigned a key, usually a number. The records are ordered by this key.
- RRDS (Relative record data set)
In an RRDS records can be inserted and accessed by their relative position to another record.
