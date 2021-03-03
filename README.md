# RcppRDKit
(Incomplete) R bindings to the C++ API of RDkit

I'd really like to make use of RDKit in R. It's likely the most feature rich open-source chemoinformatics toolkit and certainly has a number of features missing from other libraries present in R at current time.

I genuinely believe that the thing holding back greater use of R in chemoinformatics is the access to familiar libraries. With a little Rcpp, we should be able to right this.

I envisage this package being a link to the RDkit code via some [Rcppmodules](https://github.com/r-pkg-examples/rcpp-modules-student) - easy to install across platform, but relatively low level. Then more focused packages can be builts from it (e.g. a kinase-inhibitor specific modelling package).
