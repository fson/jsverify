## Release History

- 0.4.0-alpha8 oneof &amp; record -dsl support
    - also `jsc.compile`
    - record is shrinkable!
- 0.4.0-alpha7 oneof &amp; record
    - *oneof* and *record* generator combinators ([@fson](https://github.com/fson))
    - Fixed uint\* generators
    - Default test size increased to 10
    - Numeric generators with size specified are independent of test size ([#20](https://github.com/phadej/jsverify/issues/20))
- 0.4.0-alpha6 more primitives
    - int8, int16, int32, uint8, uint16, uint32
    - char, asciichar and asciistring
    - value &rarr; json
    - use eslint
- 0.4.0-alpha5 move david to be devDependency
- 0.4.0-alpha4 more typify
    - `suchchat` supports typify dsl
    - `oneof` &rarr; `elements` to be in line with QuickCheck
    - Added versions of examples using typify dsl
- 0.4.0-alpha3 David, npm-freeze and jscs
- 0.4.0-alpha2 Fix typo in readme
- 0.4.0-alpha1 typify
   - DSL for `forall`
       ```js
       var bool_fn_applied_thrice = jsc.forall("bool -> bool", "bool", check);
       ```

   - generator arguments, which are functions are evaluated. One can now write:
       ```js
       jsc.forall(jsc.nat, check) // previously had to be jsc.nat()
       ```

- 0.3.6 map generator
- 0.3.5 Fix forgotten rngState in console output
- 0.3.4 Dependencies update
- 0.3.3 Dependencies update
- 0.3.2 `fun` &rarr; `fn`
- 0.3.1 Documentation typo fixes
- 0.3.0 Major changes
    - random generate state handling
    - `--jsverifyRngState` parameter value used when run on node
    - karma tests
    - use make
    - dependencies update
- 0.2.0 Use browserify
- 0.1.4 Mocha test suite
    - major cleanup
- 0.1.3 gen.show and exception catching
- 0.1.2 Added jsc.assert
- 0.1.1 Use grunt-literate
- 0.1.0 Usable library
- 0.0.2 Documented preview
- 0.0.1 Initial preview
