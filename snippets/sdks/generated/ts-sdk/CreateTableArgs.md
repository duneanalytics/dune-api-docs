## CreateTableArgs


<ParamField path="description" type="text">
A description of the table.
</ParamField>
<ParamField path="is_private" type="text">
If true, the table will be private.
If private it is only visible to the team or user that your API key is associated with.
</ParamField>
<ParamField path="namespace" type="text">
The namespace of the table to create.
Must be the name of your associated API key, i.e. either 
</ParamField>
<ParamField path="schema" type="text">
An ordered list of columns that define the table schema. Cannot be empty.
</ParamField>
<ParamField path="table_name" type="text">
The name of the table to create.
Must begin with a lowercase letter and contain only lowercase letters,
digits, and underscores.
</ParamField>