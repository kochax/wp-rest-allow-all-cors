# WP-REST-Allow-All-CORS

The plugin will overide `handle_preflight` request, and will handle OPTIONS request.


Response headers are set to :

    - Access-Control-Allow-Origin: \*"  
    - Access-Control-Allow-Methods: POST, GET, OPTIONS, PUT, DELETE"
    - Access-Control-Allow-Credentials: true"
    - Access-Control-Allow-Headers: Origin, X-Requested-With, Content-Type, Accept, Authorization'
