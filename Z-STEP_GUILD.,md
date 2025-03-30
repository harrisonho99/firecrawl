
docker compose build

docker compose up

curl -X POST http://localhost:3002/v0/scrape \
    -H 'Content-Type: application/json' \
    -d '{
          "url": "https://docs.firecrawl.dev"
        }'q


curl --location 'http://localhost:3002/v1/map' \
--header 'Content-Type: application/json' \
--header 'Authorization: Bearer YOUR_API_KEY' \
--data '{
   "url": "https://www.nhathuocankhang.com/",
   "limit":100
}'