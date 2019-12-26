# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).


## [0.0.19] - 2019-12-23
### Added
- Triple Search function in ElasticUtil
- Triple Search query generator for Triple search function 

### Changed
- Function gt can now extract from a list with dicts values and added separator option for func parameters
- CommonModel doesn't update date_updated each time changes are made

## [0.0.20] - 2019-12-26
### Changed
- Function gt can now extract from a mongo engine Document
- Elasticsearch and mongoengine are not requirements now