# The Smart Data Specification for Semantically Describing Streams

A `sds:Stream` is a stream of objects that have undergone transformations which can be described in RDF. It is able to describe:
 * the `sds:records` it carries,
 * what the previous transformations were through `p-plan:wasGeneratedBy`, and
 * the `dcat:Dataset` is published

The HTML specification can soon be found at https://w3id.org/sds/specification.

This specification uses the [P-Plan specification](http://vocab.linkeddata.es/p-plan/) to describe previous steps taking that result in the current stream.

## Build the spec

Install bikeshed (pip3), then run `bikeshed watch sds.bs` or use the Github action in the repository.

## Contributions

Edit `sds.bs` or the vocabulary in Turtle, and open a [pull requests](https://github.com/TREEcg/SmartDataStreams-Spec/compare).

## Acknowledgements

This work is financed by the SEMIC programme of the European Commission and the Flemish Smart Data Space project. It is authored by Arthur Vercruysse, Sitt Min Oo and Pieter Colpaert.

