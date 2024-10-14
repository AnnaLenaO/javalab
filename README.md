Two different solutions to test the GET method "getProductById".
Please see comments in "ProductResourceTest.

jboss.resteasy.mock & MockHttpResponse do not seem to support LocalDate in "Product". 
Therefore, JSONArray & JSONObject cannot be used in this case for comparing actual
with expected. Please see comments for the "getJsonRepresentProductList()" test in 
"ProductResourceTest. 
Only several years old solutions to this problem could be found, along with dependencies 
that have not been updated for some years. There is also a lot of documentation on how 
to handle date formats with for instance Spring & REST. Thus, it is reasonable to 
assume that this issue no longer exists when using for example Spring, Docker, etc. 
