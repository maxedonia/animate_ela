# animate_ela
Error Level Analysis (ELA) helps identify areas in images that may have been altered by highlighting discrepancies that are present at various stages of compression that exist in the same source image. The ELA of an unedited image should maintain certain characteristics that are to be expected, even under extreme compression. By comparison, many popular image filters and warping effects leave behind traces of their use that aren't readily apparent at first glance. Manipulations become easier to observe with ELA on compressed instances of an image, as it shows where deviations from what is to be expected from an unaltered image that is being compressed. This makes ELA a particularly useful forensic tool for examining images of dubious origin, or those which might have undergone various edits and/or format changes. With the proper analysis, one can infer an image's authenticity, particular hotspots of digital distortion, and even deduce a possible chronology of when different manipulations occured by comparing these discrepancies at various instances of fidelity. In some cases, the insight from ELA can be easier to assess if the various stages of compression are consolidated in sequential order and outputed in .gif format using animate_ela.
