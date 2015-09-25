# docker-mga

To build a Docker image:

* Download binary from "http://metagene.nig.ac.jp/metagene/download_mga.html"
* Put it into the "bin" directory as "mga"
* docker build -t mga .

To run:

    $ docker run --rm -v ~/data:/data -w /data mga contigs.fa
