# python-image-mask-filter
Filtering images with mask and python3 (Pillow)

Usage: imageToProcess imageResult maskFile


Really slow implementation based on Pillow, but still usable in some cases

Better to use GO implementation:

https://github.com/Razikus/go-image-mask-filter

For comparision, 2 values with the same mask and same image process:

Time in python - real    1m57,666s

Time in go - real    0m4,617s
