# Description
Make a dockerfile to create an image that lets you run a binary executable in a container instead of installing it on your machine.

- The binary: https://wkhtmltopdf.org/

Things to consider:
* what base image should you use?
* the wkhtmltopdf generate some files, how will you make them available to the host?
* the wkhtmltopdf has various arguments, how will you provide them to the container in the run command?



