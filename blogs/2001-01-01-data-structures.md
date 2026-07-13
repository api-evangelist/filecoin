---
title: "Data Structures"
url: "/appendix/data_structures/"
date: "2001-01-01"
feed_url: "https://spec.filecoin.io/index.xml"
---
Data Structures State reliable Theory Audit n/a Edit this section section-appendix.data_structures RLE+ Bitset Encoding State reliable Theory Audit n/a Edit this section section-appendix.data_structures.rle-bitset-encoding RLE+ is a lossless compression format based on RLE. Its primary goal is to reduce the size in the case of many individual bits, where RLE breaks down quickly, while keeping the same level of compression for large sets of contiugous bits. In tests it has shown to be more compact than RLE itself, as well as Concise and Roaring.
