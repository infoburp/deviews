D.E.V.I.E.W.S
=======
Distributed Evolutionary Vectorisation of Images as a Web Service

user tasks:

upload a new static image to be vectorised

upload a new animated image to be vectorised

upload a new video to be vectorised

view gallery


client webworker:

while (client connected) 
{
  download work unit

  process work

  upload work unit results
}

work unit types:

  vectorise image 

  split animated image into frames

  split video into frames
