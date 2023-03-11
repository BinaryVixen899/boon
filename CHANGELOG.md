# Changelog

## [Unreleased]

### Added
- add example_custom_content_encoding

### Performance
- contentEncoding: use IgnoredAny instead of Value
- compiler: avoid escape calls to keywords
- validator: compute keywordLocation without heap allocs

## [0.3.1] - 2023-03-07

### Added
- add example_from_yaml_files
- cli: support yaml files

### Fixed
- ensure fragment decoded before use
- $dynamicRef w/o anchor is same as $ref