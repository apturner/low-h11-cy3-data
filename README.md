# Calabi-Yau Intersection Number Data

This repository contains the intersection numbers and second Chern class for all Calabi–Yaus threefolds constructed as hypersurfaces in toric fourfolds with h^{1, 1} from 2 to 6 (see the Kreuzer–Skarke database, http://hep.itp.tuwien.ac.at/~kreuzer/CY/CYhome.html).

The file `cyDataUpTo5.py` contains four lists, named "TC`n`s" for h^{1, 1} = n, for n = 2, ..., 5. Each element in one of these lists corresponds to a Calabi–Yau, and is itself a list consisting of two elements:

-   A list of lists of lists (3-tensor), which is the intersection 3-tensor of the CY
-   A list (vector, which is the second Chern class

The file `TC6s.pickle` is a Python pickle file that contains data for h^{1, 1} = 6.

Included also is a paper by Rivin discussing how to properly choose a random integer matrix, which describes among other things how to choose a random SL(n, Z) matrix. The file `Random SLnZ Matrix.nb` is a Mathematica notebook that (approximately) implements this approach using the LLL algorithm.
