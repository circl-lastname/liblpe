# LPE
Local Palette Encoding (LPE) is a lossy image compression format that provides a compression ratio of 6.4:1 in most cases <sup>1</sup> and acceptable image quality using only simple integer math.

![Lenna](images/lenna.png)

The Lenna test image, as passed through LPE. The LPE file is 122.8 kB in size.

<sup>1</sup> As long as both the height and width of the original bitmap are divisible by 8, this compression ratio is guaranteed. As an example, a 9x9 image will take up the same amount of space as a 16x16 one.

## In this repository
* [liblpe](liblpe) - The reference implementation of LPE
