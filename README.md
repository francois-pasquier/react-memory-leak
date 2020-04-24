This is a POC to show that the CRA jest tests have a memory leak somewhere

* Pull project
* rune `yarn` or `npm install`
* `yarn test:w1`

You should get this output :
```
 PASS  src/App20.test.js (56 MB heap size)
 PASS  src/App19.test.js (55 MB heap size)
 PASS  src/App12.test.js (67 MB heap size)
 PASS  src/App41.test.js (68 MB heap size)
 PASS  src/App2.test.js (79 MB heap size)
 PASS  src/App38.test.js (80 MB heap size)
 PASS  src/App44.test.js (91 MB heap size)
 PASS  src/App39.test.js (92 MB heap size)
 PASS  src/App.test.js (103 MB heap size)
 PASS  src/App6.test.js (104 MB heap size)
 PASS  src/App9.test.js (115 MB heap size)
 PASS  src/App49.test.js (116 MB heap size)
 PASS  src/App22.test.js (126 MB heap size)
 PASS  src/App16.test.js (127 MB heap size)
 PASS  src/App28.test.js (138 MB heap size)
 PASS  src/App37.test.js (149 MB heap size)
 PASS  src/App40.test.js (150 MB heap size)
 PASS  src/App7.test.js (161 MB heap size)
 PASS  src/App48.test.js (162 MB heap size)
 PASS  src/App21.test.js (173 MB heap size)
 PASS  src/App33.test.js (174 MB heap size)
 PASS  src/App18.test.js (185 MB heap size)
 PASS  src/App14.test.js (186 MB heap size)
 PASS  src/App45.test.js (197 MB heap size)
 PASS  src/App31.test.js (184 MB heap size)
 PASS  src/App50.test.js (183 MB heap size)
 PASS  src/App3.test.js (194 MB heap size)
 PASS  src/App24.test.js (195 MB heap size)
 PASS  src/App23.test.js (206 MB heap size)
 PASS  src/App13.test.js (207 MB heap size)
 PASS  src/App8.test.js (218 MB heap size)
 PASS  src/App25.test.js (218 MB heap size)
 PASS  src/App43.test.js (229 MB heap size)
 PASS  src/App4.test.js (230 MB heap size)
 PASS  src/App30.test.js (241 MB heap size)
 PASS  src/App5.test.js (252 MB heap size)
 PASS  src/App27.test.js (253 MB heap size)
 PASS  src/App34.test.js (263 MB heap size)
 PASS  src/App46.test.js (265 MB heap size)
 PASS  src/App11.test.js (275 MB heap size)
 PASS  src/App10.test.js (277 MB heap size)
 PASS  src/App36.test.js (287 MB heap size)
 PASS  src/App17.test.js (288 MB heap size)
 PASS  src/App35.test.js (299 MB heap size)
 PASS  src/App47.test.js (300 MB heap size)
 PASS  src/App29.test.js (310 MB heap size)
 PASS  src/App15.test.js (311 MB heap size)
 PASS  src/App32.test.js (322 MB heap size)
 PASS  src/App26.test.js (333 MB heap size)
 PASS  src/App42.test.js (334 MB heap size)

Test Suites: 50 passed, 50 total
Tests:       50 passed, 50 total
Snapshots:   0 total
Time:        3.484s, estimated 18s
Ran all test suites.

```
