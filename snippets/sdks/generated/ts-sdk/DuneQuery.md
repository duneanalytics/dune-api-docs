## DuneQuery
Enriched structure representing all data constituting a DuneQuery.
Modeling the CRUD operation response for &#x27;get_query&#x27;
https://docs.dune.com/api-reference/queries/endpoint/read#example-return

<ParamField path="description" type="text">
Description of the query.
</ParamField>
<ParamField path="is_archived" type="text">
Indicates if the query is archived.
Note: This is as close as a user can get to deleting a query.
</ParamField>
<ParamField path="is_private" type="text">
Indicates if the query is private.
</ParamField>
<ParamField path="is_unsaved" type="text">
Indicates if the query is unsaved.
</ParamField>
<ParamField path="name" type="text">
Name of the query.
</ParamField>
<ParamField path="owner" type="text">
Dune user who owns the query.
</ParamField>
<ParamField path="parameters" type="text">
Parameters with their names and default values.
</ParamField>
<ParamField path="query_engine" type="text">
The query engine used to execute the query.
</ParamField>
<ParamField path="query_id" type="text">
Unique identifier of the query.
</ParamField>
<ParamField path="query_sql" type="text">
Raw SQL of the query.
</ParamField>
<ParamField path="tags" type="text">
Tags associated with the query.
</ParamField>
<ParamField path="version" type="text">
Version of the query.
</ParamField>