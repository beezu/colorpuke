# colorpuke

You *need* a terminal with 24bit/truecolor support for this script to output anything!

Run `sh colorpuke.sh` after cloninng

Alternatively, run it in docker! I configured a dockerhub page for this container, and it is a very small container (Alpine base image, no extra packages needed to be installed). You don't even need to clone this repo, simply run `docker run --rm --log-driver none -it beezu/colorpuke`. Use ctrl+c to quit it.

I highly recommend setting the log-driver to none because this will generate logs endlessly and quickly, and fill your hard drive over time.
