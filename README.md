
## Psyop Extentions

## Scatter

Scatter is an extension that does even point scattering on meshes and dart throwing. 

Dart throwing is an iterative process that places points, checking for overlap and removing htem. Parts of the system are replacable. For instance, there is a sizer that starts with large darts, and ends with small darts, and a weight map filter to use a weight map to define a maximum sized point in an area. 

Please see /examples for canvas examples, and /scatter/test/test.kl for some code examples. 

## PsyopUtil

Some utility stuff Scatter relies on. There's some other goodies in there too, undocumented for now...
