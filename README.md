<h1 align="center">
<img src="https://raw.githubusercontent.com/maxbachmann/rapidfuzz/dev/.github/RapidFuzz.png" alt="RapidFuzz" width="400">
</h1>
<h4 align="center">rapid string matching library</h4>

<p align="center">
  <a href="#how-to-use">How To Use</a> •
  <a href="#license">License</a>
</p>

# Roadmap
- [ ] add string matching for strings with a big length difference
- [ ] add Unit tests
- [ ] add Benchmarks
- [ ] make all algorithms more generic so they can at least be used with iterables of any kind (e.g. string or vector of integers) and with iterables of iterables like e.g. vector of strings or vector of strings views with a custom delimiter that can be both an iterable or a single element of the same kind. e.g. char as single element or string as multiple elements
- [ ] make removing the affix optional, since the user might know that he does not want this behaviour. The complete String processing is only build for strings right now and it does not really seem like it can be directly mapped (e.g. string splitting into words makes not much sence with integers)
- [ ] add Python wrapper
- [ ] add Rust version of the code

## How To Use

## License
RapidFuzz is licensed under the MIT license since we believe that everyone should be able to use it without being forced to adopt our license. Thats why the library is based on an older version of fuzzywuzzy that was MIT licensed aswell.
A Fork of this old version of fuzzywuzzy can be found [here](https://github.com/rhasspy/fuzzywuzzy).
