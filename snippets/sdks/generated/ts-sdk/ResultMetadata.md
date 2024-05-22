## ResultMetadata
Metadata contained within a quer 

<ParamField path="column_names" type="text">
Names of the columns contained in the query results.
</ParamField>
<ParamField path="datapoint_count" type="text">
Total number of data points in result.
Used as part of the API credits computation.
</ParamField>
<ParamField path="execution_time_millis" type="text">
Time in milliseconds that the query took to execute.
</ParamField>
<ParamField path="pending_time_millis" type="text">
How long they query was pending (in the queue) before execution began.
</ParamField>
<ParamField path="result_set_bytes" type="text">
Number of bytes in the result set for the current page of results.
</ParamField>
<ParamField path="row_count" type="text">
Number of rows in the result set for the current page of results.
</ParamField>
<ParamField path="total_result_set_bytes" type="text">
Total number of bytes in the result set. This doesn&#x27;t include the json representation overhead.
</ParamField>
<ParamField path="total_row_count" type="text">
Total number of rows in the result set.
</ParamField>