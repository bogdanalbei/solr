solr
====

Pecl solr patched for Solr 4.0

Without the patch this error is returned:
	 ERROR: "SolrClientException" with message "Unsuccessful update request. Response Code 400. <?xml version="1.0" encoding="UTF-8"?>
	<response>
	
	<lst name="responseHeader">
	  <int name="status">400</int>
	  <int name="QTime">4</int>
	</lst>
	<lst name="error">
	  <str name="msg">Unknown commit parameter 'waitFlush'</str>
	  <int name="code">400</int>
	</lst>
	</response>
