## GetResultParams


<ParamField path="columns" type="text">
Specified columns to be returned. If omitted, all columns are included.
Tip: use this to limit the result to specific columns, reducing datapoints cost of the call.
</ParamField>
<ParamField path="filters" type="text">
Expression to filter out rows from the results to return.
This expression is similar to a SQL WHERE clause.
More details about it in the [Filtering](https://docs.dune.com/api-reference/executions/filtering) section of the doc.
This parameter is incompatible with 
</ParamField>
<ParamField path="limit" type="text">
Limit number of rows to return.
This together with &#x27;offset&#x27; allows easy pagination through results in an incremental and efficient way.
This parameter is incompatible with sampling (
</ParamField>
<ParamField path="offset" type="text">
Offset row number to start (inclusive, first row means offset&#x3D;0) returning results from.
This together with &#x27;limit&#x27; allows easy pagination through results.
This parameter is incompatible with sampling (
</ParamField>
<ParamField path="query_parameters" type="">

</ParamField>
<ParamField path="sample_count" type="text">
Number of rows to return from the result by sampling the data.
This is useful when you want to get a uniform sample instead of the entire result.
If the result has less than the sample count, the entire result is returned.
Note that this will return a randomized sample, so not every call will return the same result.
This parameter is incompatible with 
</ParamField>
<ParamField path="sort_by" type="text">
Expression to define the order in which the results should be returned.
This expression is similar to a SQL ORDER BY clause.
More details about it in the [Sorting](https://docs.dune.com/api-reference/executions/sorting) section of the doc.
</ParamField>