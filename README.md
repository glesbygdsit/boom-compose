# boom-compose
1. Clone repo
2. docker-compose.exe -d -f .\boom.yml up
5. Rebuild images with: docker-compose.exe -f .\boom.yml build
4. Update running services with: docker-compose.exe -f .\boom.yml up
5. To kill: docker-compose.exe -f .\boom.yml down

To view logs from a service (for instance the hit-miss-target-service):
docker-compose.exe -f .\boom.yml logs -f boom-hit-miss-target-service