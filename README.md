# dd-safe - A safer interface to dd

This provides a script that you run in place of dd when flashing an image to a
device like an SD card. You provide a lower and upper limit as to the expected
size of the output device, and the script will check to make sure that the
destination device fits those criteria.

By default this has a range between 7GB and 32GB, which should cover SD cards of
the common sizes: 8GB, 16GB, and 32GB.
