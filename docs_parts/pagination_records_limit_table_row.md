| pagination_records_limit | NO | int | None | The numbers of records to scan before paginating the query. If None, the query will execute until all records matching the key_value have been scanned, or when the retrieved fields from the records exceed 1MB.