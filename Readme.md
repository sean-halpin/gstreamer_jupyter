# GStreamer Tutorials in a Jupyter Notebook

Building & Running this docker image will allow you to complete gstreamer notebooks with all gstreamer dependancies available using the Xeus C++ Kernel for Jupyter. 

The output of the container will reveal the notebook url.  
Navigate to the url in order to run through or edit the notebooks. 

---
### Build docker image

`docker build -t gst_jup .`

---

### Run Jupyter Server

`docker run --rm -v $(pwd)/notebooks:/notebooks --network host gst_jup`

---