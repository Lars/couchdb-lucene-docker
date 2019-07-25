# About
## Purpose
The purpose of this repository is to create a Dockerized version of couchdb-lucene which can communicate with Dockerized
 OR plain versions of Couchdb 

### Versions
At the time of this writing I'm using couchdb 2.3.1, and I'm basing this docker image in debian:stretch-slim, the same 
the official Docker container for couchdb 2.3.1 uses as to share a layer with couchdb's image to expedite builds.