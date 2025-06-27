
<!-- README.md is generated from README.Rmd. Please edit that file -->

# much\_<span style="color:red;">f</span><span style="color:orange;">l</span><span style="color:gold;">u</span><span style="color:green;">o</span><span style="color:blue;">r</span><span style="color:indigo;">e</span><span style="color:violet;">s</span><span style="color:red;">c</span><span style="color:orange;">e</span><span style="color:green;">n</span><span style="color:blue;">t</span>

<!-- badges: start -->
<!-- badges: end -->

A small repository for spectral data of happy little fluorochromes.

![](README_files/figure-gfm/unnamed-chunk-2-1.png)<!-- -->

See plots of excitation and emission spectra in spectra_images.

All raw data for those are in spectra.tsv.gz and em_ex_maxima.tsv.

    #> 
    #> 
    #> |fluorochrome |  nm| ex| em|
    #> |:------------|---:|--:|--:|
    #> |PE-Dazzle594 | 300|  0|  0|
    #> |PE-Dazzle594 | 301|  0|  0|
    #> |PE-Dazzle594 | 302|  0|  0|
    #> |PE-Dazzle594 | 303|  0|  0|
    #> |PE-Dazzle594 | 304|  0|  0|
    #> |PE-Dazzle594 | 305|  0|  0|
    #> |PE-Dazzle594 | 306|  0|  0|
    #> |PE-Dazzle594 | 307|  0|  0|
    #> |PE-Dazzle594 | 308|  0|  0|
    #> |PE-Dazzle594 | 309|  0|  0|
    #> 
    #> 
    #> |fluorochrome |type |  nm| norm_intensity|
    #> |:------------|:----|---:|--------------:|
    #> |PE-Dazzle594 |em   | 501|            100|
    #> |PE-Dazzle594 |ex   | 412|            100|

Peaks were detected by algorithm. This may either be oversensitive and
detect too many of them or miss some. Plots were checked and only very
few minor peaks are not detected. In very few spectra lowest emission
peak is below lowest excitation which should not be according to [Stokes
shift](https://en.wikipedia.org/wiki/Stokes_shift). Some spectra include
negative values or values above 100 which is weird but data was left as
obtained in this case. However, leading and trailing zeros were removed
for instance.

fluos.tsv is a table of all fluorochromes and a note whether a dye is
used in flow cytometry.
