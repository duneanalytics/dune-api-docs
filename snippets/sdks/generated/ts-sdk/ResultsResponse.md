## ResultsResponse
Response of reqeust for results of a query execution.

<ParamField path="cancelled_at" type="text">
Timestamp of when the query execution was cancelled, if applicable.
</ParamField>
<ParamField path="execution_ended_at" type="text">
Timestamp of when the query execution ended.
</ParamField>
<ParamField path="execution_id" type="text">
Unique identifier for the execution of the query.
</ParamField>
<ParamField path="execution_started_at" type="text">
Timestamp of when the query execution started.
</ParamField>
<ParamField path="expires_at" type="text">
Timestamp of when the query result expires.
</ParamField>
<ParamField path="is_execution_finished" type="text">
Whether the state of the query execution is terminal. This can be used for polling purposes.
</ParamField>
<ParamField path="next_offset" type="text">
Offset that can be used to retrieve the next page of results.
</ParamField>
<ParamField path="next_uri" type="text">
URI that can be used to fetch the next page of results.
</ParamField>
<ParamField path="query_id" type="text">
Unique identifier of the query.
</ParamField>
<ParamField path="result" type="text">
only present when state is COMPLETE
</ParamField>
<ParamField path="state" type="text">
The state of the query execution.
</ParamField>
<ParamField path="submitted_at" type="">

</ParamField>