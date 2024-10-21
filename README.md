# RNA-seq

#check if the md5 number for the compressed file after download is the same as the one given by the company
#open terminal and go to the folder of interest
#if md5sum  is not available,  install md5sum following https://raamdev.com/2008/howto-install-md5sum-sha1sum-on-mac-os-x/.
md5sum filename.tar

#unzip filename.tar file
tar -xvf filename.tar

#do the same for all the compressed folder to make sure that the numbers are indeed matching (no file corruption)
md5sum filename.zip

#unzip filename.zip file
unzip filename.zip

#check if each sample (PE) has both read1 and read2
wc -l 
#my numbers are actually different from each other, not sure exactly what that means

#unzip .gz filwa
gzip -d *.gz
