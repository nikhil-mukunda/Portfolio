
# Authentication
The APIs for SAP Health for Patient Engagement uses the OAuth 2.0 standard authentication. See  [https://oauth.net/2/](https://oauth.net/2/)  for any additional information.


## Procedure

1. Go to https://www.sap.com/hep and login with your user name and password. In the *Authentication* tab page, note down the *client_id* and *client_secret*. Do not divulge these credentials to any external party you do not trust.  
2. Make the following **API call** with the _client_id_ and _client_secret_.
3. Make a note of the response you receive. The response for the API call should look like this:
`
{
"access_token":" utTJFMrOKwlyB5rcBpCIP6Dtn0k4w8vtqR6TJtu-fvEIm9tXTZf6q4JSaRaxRc7eSgO4EAggELN5bqADCSGq4mDEQgM-k-VPUi7IVIkKrVAFdwyb9Yz1cXy9pU96tZSmxjNiNzMiLCJvcmciOiJTTFI6MTMyMjAzNiIsImF6cCI6IjMwODE4NWVhLTkyZTAtNGE0NS1iNzg2LWU5MzI1OTIyM2I3MyIsImNsaWVudG5hbWUiOiJDaGFubmFWFmYyRdvKZyB4PibGUiLCJpc3MiOiJsb2dpbi5ib2wuY29tIiwic2NvcGVzIjoiQ3VzdG9tU2NvcGU0IEN1c3RvbVNjb3BlMyIsImV4cCI6MTUzOTI0NDkwMSwiaWF0IjoxNTM5MjQ0NjAxLCJhaWQiOiJTTFI6MTMyMjAzNiIsImp0aSI6IjI1YzcxZDY2LTU0YzgtNDQ3ZS04NTk0LWEwMzFlZDNkNGUzOSJ9.Nkc90mTB-BLVJEnSDHx2o1bkJyJraWQiOiJyc2ExIiwiYWxnIjoiUlMyNTYifQ.eyJzdWIiOiIzMDgxODVlYS05MmUwLTRhNDUtYjc4Ni1lOTMyNTkyM7Dan9VaFQF1o8EvlGCV42n61KAjeEg8PrjVwqFvJ8y9QUzcpTFXQ5f4VFgIfZfYaqZyM2iJWFlpSpVl-jQAiGjOp0xSForKtGe2-FdyXmmQNpw_IltcPmvJIGABU3Xngx5O-13sG_zRoy7g1CBspU9dx5DLDuOa17PBmj52kQVEV8Q",
"token_type": "Bearer",
"expires_in": 299,
"scope": "{scopes}"
}
`

For every API call you make to the SAP Health for Patient Engagement system, you must request a new access token as shown in step 2.






Authentication
The APIs for SAP Health for Patient Engagement uses the OAuth 2.0 standard authentication. See https://oauth.net/2/ for any additional information.

Procedure
Go to https://www.sap.com/hep and login with your user name and password. In the Authentication tab page, note down the client_id and client_secret. Do not divulge these credentials to any external party you do not trust.
Make the following API call with the client_id and client_secret.
Make a note of the response you receive. The response for the API call should look like this:
{ "access_token":" utTJFMrOKwlyB5rcBpCIP6Dtn0k4w8vtqR6TJtu-fvEIm9tXTZf6q4JSaRaxRc7eSgO4EAggELN5bqADCSGq4mDEQgM-k-VPUi7IVIkKrVAFdwyb9Yz1cXy9pU96tZSmxjNiNzMiLCJvcmciOiJTTFI6MTMyMjAzNiIsImF6cCI6IjMwODE4NWVhLTkyZTAtNGE0NS1iNzg2LWU5MzI1OTIyM2I3MyIsImNsaWVudG5hbWUiOiJDaGFubmFWFmYyRdvKZyB4PibGUiLCJpc3MiOiJsb2dpbi5ib2wuY29tIiwic2NvcGVzIjoiQ3VzdG9tU2NvcGU0IEN1c3RvbVNjb3BlMyIsImV4cCI6MTUzOTI0NDkwMSwiaWF0IjoxNTM5MjQ0NjAxLCJhaWQiOiJTTFI6MTMyMjAzNiIsImp0aSI6IjI1YzcxZDY2LTU0YzgtNDQ3ZS04NTk0LWEwMzFlZDNkNGUzOSJ9.Nkc90mTB-BLVJEnSDHx2o1bkJyJraWQiOiJyc2ExIiwiYWxnIjoiUlMyNTYifQ.eyJzdWIiOiIzMDgxODVlYS05MmUwLTRhNDUtYjc4Ni1lOTMyNTkyM7Dan9VaFQF1o8EvlGCV42n61KAjeEg8PrjVwqFvJ8y9QUzcpTFXQ5f4VFgIfZfYaqZyM2iJWFlpSpVl-jQAiGjOp0xSForKtGe2-FdyXmmQNpw_IltcPmvJIGABU3Xngx5O-13sG_zRoy7g1CBspU9dx5DLDuOa17PBmj52kQVEV8Q", "token_type": "Bearer", "expires_in": 299, "scope": "{scopes}" }
For every API call you make to the SAP Health for Patient Engagement system, you must request a new access token as shown in step 2.

Markdown selection 1617 bytes 128 words 24 lines Ln 25, Col 0HTML 1427 characters 121 words 8 paragraphs