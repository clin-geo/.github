# Clinical Geocoding (clin-geo) Organization

Organization created to support collaboration across people and groups working on HIPAA-compliant/privacy-senitive methods for geocoding for clinical and clinical research purposes.

## Inspired by
### DeGAUSS
If one has access to run containers, DeGAUSS can be relatively simple to get started.
- [DeGAUSS Web](https://degauss.org/)
- [DeGAUSS Github](https://github.com/degauss-org)

### PostGIS
PostGIS requires more configuration and technoligical knowledge for debugging, but uses a full-strength database (postgres) that might be more appropriate for production use.
- [PostGIS Documentation](https://postgis.net/)
- [PostGIS Github](https://github.com/postgis/postgis)
- [PostGIS Official source and tracker](https://trac.osgeo.org/postgis/)

## Future Goals
### Development
- [ ] tools to facilitate discovering and download of TIGER/Line data from www2.census.gov (WIP)
- [ ] Explore python-based workflow (containerized or not) taking advantage of duckdb geospatial support
- [ ] If performant, ideally minimize number of languages, Ruby and non-precompile C may no longer be necessary
- [ ] Release tools to support GUI workflows with hosted PostGIS configurations (these tools have been built in development, but are not yet ready for public release)
- [ ] provide support for geo-routing to estimate time and distance between locations (likely use open street map, but consider arbitrarily supporting any two addresses rather than just isocrons with known clinic locations)

### geo-data storage, versioning, and optimization
- [ ] expore www2.census.gov policies on redistribution
- [ ] explore cost of hosting and egress of geodata (raw and preformatted)

## Prior Code Dependencies and Potentially Useful Future Tools
### Existing Dependencies
#### DeGAUSS

#### PostGIS

### Potentially Useful Tools
#### statistical address parsers (rather than rule/regex based)
- [python - usaddress](https://github.com/datamade/usaddress)
- [python/C - pypostal - international](https://github.com/openvenues/pypostal)
