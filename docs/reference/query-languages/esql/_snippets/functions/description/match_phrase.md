% This is generated by ESQL's AbstractFunctionTestCase. Do not edit it. See ../README.md for how to regenerate it.

**Description**

Use `MATCH_PHRASE` to perform a [`match_phrase`](/reference/query-languages/query-dsl/query-dsl-match-query-phrase.md) on the specified field. Using `MATCH_PHRASE` is equivalent to using the `match_phrase` query in the Elasticsearch Query DSL.  MatchPhrase can be used on [text](/reference/elasticsearch/mapping-reference/text.md) fields, as well as other field types like keyword, boolean, or date types. MatchPhrase is not supported for [semantic_text](/reference/elasticsearch/mapping-reference/semantic-text.md) or numeric types.  MatchPhrase can use [function named parameters](/reference/query-languages/esql/esql-syntax.md#esql-function-named-params) to specify additional options for the match_phrase query. All [`match_phrase`](/reference/query-languages/query-dsl/query-dsl-match-query-phrase.md) query parameters are supported.  `MATCH_PHRASE` returns true if the provided query matches the row.

