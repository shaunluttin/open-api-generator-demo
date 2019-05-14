
# Usage

Install the JDK (Java Development Kit) and then run:

    npm install
    npm run openapi-generator -- generate -i specs/petstore.yaml -g typescript-fetch -o ./petstore
    npm run openapi-generator -- generate -i specs/avoidInlineObject.yaml -g typescript-fetch -o ./avoidInlineObject

The resultant client will be in the `client/` directory.