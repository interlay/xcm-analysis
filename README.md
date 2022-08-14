# XCM Data Analysis


Data fetched from https://polkaholic.io/ API using the "XCM search" endpoint. 

API docs: https://docs.polkaholic.io/#search-xcm-transfers

Example POST request - get all XCM transfers from Acala to Interlay. 
´´´
curl https://api.polkaholic.io/search/xcmtransfers \
-X POST \
-H "Content-Type: application/json" \
-d '{
    "chainID": "acala",
    "chainIDDest": "interlay"
}'
´´´