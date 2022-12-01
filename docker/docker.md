# load docker image from zip file
`docker load < myfile.tar.gz`

# open terminal within docker image
run in powershell or local terminal:

`docker run -it <image id> /bin/bash`

if you have an image loaded, run the image and open a new bash instance within the docker image.