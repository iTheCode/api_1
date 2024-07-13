FROM mongo

COPY client.json /client.json

CMD mongoimport mongodb://client:27017 --db=client_database --collection=client_collection --jsonArray --file=/client.json --port 27017