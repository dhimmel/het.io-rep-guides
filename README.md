# Neo4j Guides for Project Rephetio Predictions

This repository creates HTML guides which can be played in the Neo4j Browser. Each guide details a prediction of whether a compound will treat a disease. The guides are based on [Hetionet v1.0](https://github.com/dhimmel/hetionet) and are hosted at https://neo4j.het.io. For more details on our public Neo4j instance, see [this discussion](https://thinklab.com/discussion/hosting-hetionet-in-the-cloud-creating-a-public-neo4j-instance/216 "Hosting Hetionet in the cloud: creating a public Neo4j instance. Thinklab")

## Files

`neo4j-guides` contains a program to convert asciidoc guides to HTML guides.

`template-full.txt` and `template-mini.txt` are templates for creating asciidoc guides, which are designed to be formatted using Python's string formatting. `template-full.txt` is for compound–disease pairs without any metapaths that [provide support](https://thinklab.com/discussion/decomposing-predictions-into-their-network-support/229#2 "Calculating metapath and path contributions. Thinklab Discussion"). `template-full.txt` is for compound–disease pairs with supportive metapaths and hence supportive paths.

The HTML guides are exported to `guides`, which is ignored due to the large number of files. The compressed version of this directory is available in `guides.tar.bz2`.

## License

All original work in this repository is released as [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/ "CC0 1.0 Universal Public Domain Dedication").
