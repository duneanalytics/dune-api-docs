## ExecutionResult
Result of a Query Execution.

<ParamField path="metadata" type="text">
Metadata about the execution of the query, including details like column names,
row counts, and execution times.
</ParamField>
<ParamField path="rows" type="text">
A list of rows. A row is dictionary of key-value pairs returned by the query,
each pair corresponding to a column
</ParamField>