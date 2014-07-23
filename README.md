Gzip-spec
=========

A quick GZip spec depenedent on streams likely:

Questions needed to answer:

- Which methods do we support, for reference the node zlip package these classes that create streams:
    - Gzip
    - Gunzip
    - Deflate
    - Inflate
    - DeflateRaw
    - InflateRaw
    - Unzip
- Streams are a really good fit for this, so do we wait for [whatwg/streams](https://github.com/whatwg/streams) or are non stream versions helpful