#### State

Value description:

The status of a particular translation in a \<target> or \<bin-target> element.\
In addition, user-defined values can be used with this attribute. A user-defined value must start with an "x-" prefix.\
The pre-defined values are defined in the table below.

|Value|Description|
|-----|-----------|
|final|Indicates the terminating state.|
|needs-adaptation|Indicates only non-textual information needs adaptation.|
|needs-l10n|Indicates both text and non-textual information needs adaptation.|
|needs-review-adaptation|Indicates only non-textual information needs review.|
|needs-review-l10n|Indicates both text and non-textual information needs review.|
|needs-review-translation|Indicates that only the text of the item needs to be reviewed.|
|needs-translation|Indicates that the item needs to be translated.|
|new|Indicates that the item is new. For example, translation units that were not in a previous version of the document.|
|signed-off|Indicates that changes are reviewed and approved.|
|translated|Indicates that the item has been translated.|

#### State-qualifier

Value description:

Describes the state of a particular translation in a \<target> or \<bin-target> element.\
In addition, user-defined values can be used with this attribute. A user-defined value must start with an "x-" prefix.\
The pre-defined values are defined in the table below.

|Value|Description|
|-----|-----------|
|exact-match|Indicates an exact match. An exact match occurs when a source text of a segment is exactly the same as the source text of a segment that was translated previously.|
|fuzzy-match|Indicates a fuzzy match. A fuzzy match occurs when a source text of a segment is very similar to the source text of a segment that was translated previously (e.g. when the difference is casing, a few changed words, white-space discripancy, etc.).|
|id-match|Indicates a match based on matching IDs (in addition to matching text).|
|leveraged-glossary|Indicates a translation derived from a glossary.|
|leveraged-inherited|Indicates a translation derived from existing translation.|
|leveraged-mt|Indicates a translation derived from machine translation.|
|leveraged-repository|Indicates a translation derived from a translation repository.|
|leveraged-tm|Indicates a translation derived from a translation memory.|
|mt-suggestion|Indicates the translation is suggested by machine translation.|
|rejected-grammar|Indicates that the item has been rejected because of incorrect grammar.|
|rejected-inaccurate|Indicates that the item has been rejected because it is incorrect.|
|rejected-length|Indicates that the item has been rejected because it is too long or too short.|
|rejected-spelling|Indicates that the item has been rejected because of incorrect spelling.|
|tm-suggestion|Indicates the translation is suggested by translation memory.|

- https://docs.oasis-open.org/xliff/v1.2/os/xliff-core.html#state