```
# docker pull paths 
http://ccts3.aws.chboston.org:5151/computationalradiology/dicom-tools # inc dcmdump... check if it has retreive script 
http://ccts3.aws.chboston.org:5151/computationalradiology/crkit:latest
anima docker - tbd 
adc docker - tbd 
ivim docker - tbd
scim docker - tbd
mwf tools - tbd
svr docker - tbd 
fsl docker - tbd 


# example of how to run
docker run --rm -it -v /fileserver:/fileserver ccts3.aws.chboston.org:5151/computationalradiology/dicom-tools /bin/bash 

# wrap with alias and add to .bashrc 
alias dcmdump="docker run --rm -it -v /fileserver:/fileserver ccts3.aws.chboston.org:5151/computationalradiology/dicom-tools /bin/bash"
alias crkit=""
alias fsl=""
alias svr=""
alias retrieve=""
alias adc=""
alias ivim=""
alias svr=""
alias mwf=""







```
