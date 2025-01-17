## [0.1.4+3] - Improve library health.
- [Bug] Solved few health suggestion, to improve the health of the code.

## [0.1.4+2] - Added few advance query references and solved bugs.
- [Bug] `.setFacetFilter(dynamic value)` can now accept String or List<String> value.
- [Added] AttributeForDistinct (Advance)
- [Added] Distinct (Advance)
- [Added] GetRankingInfo (Advance)
- [Added] ClickAnalytics (Advance)

## [0.1.4+1] - Added support facets.
- Added `facets` to ``AlgoliaQuerySnapshot`` to list facets name with hits count.

## [0.1.3+2] - Implementation & bug solved.
- highlightResult [Bug] (commit ref: 0d76d24fe8aa347a0933920afe5ded43bdcbd68b)
- snippetResult [Implementation] (commit ref: 0d76d24fe8aa347a0933920afe5ded43bdcbd68b)

## [0.1.3+1] - Added support to manage index settings.
- Updated `example.dart`: Added index settings example.
- Updated index `.setSettings()` response to `AlgoliaTask`.

## [0.1.3] - Added support to manage index settings.
- Added support to manage index settings (Get & Set), limited to 24 settings parameters, more to be added in newer releases.

## [0.1.2] - Added new query params.
- OptionalFilter (Filtering)
- NumericFilter (Filtering)
- TagFilter (Filtering)
- SumOrFiltersScore (Filtering)
- AroundLatLng (Geo Search)
- AroundLatLngViaIP (Geo Search)
- AroundRadius (Geo Search)
- AroundPrecision (Geo Search)
- MinimumAroundRadius (Geo Search)
- InsideBoundingBox (Geo Search)
- InsidePolygon (Geo Search)
- MinWordSizefor1Typo (Typo)
- MinWordSizefor2Typos (Typo)
- TypoTolerance (Typo)
- AllowTyposOnNumericTokens (Typo)
- DisableTypoToleranceOnAttributes (Typo)
- DisableTypoToleranceOnWords (Typo)
- SeparatorsToIndex (Typo)

## [0.1.1] - Added example.
* Bug fixes.
* Removed Flutter direct dependency to support universal dart projects.

## [0.1.0] - Initial Release.
* Initial release.
