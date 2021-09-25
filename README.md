# infrachatjs

chatjs is a project that deploys a chat using the following stack:
- ReactJs (Frontend)
- NodeJs (Backend)
- MongoDB (DB)
- docker-compose (infra for deployment)
- rabbitmq (queue manager)

This is the orchestator of these repositories:

- https://github.com/carlosvalarezo/serverchatjs (Backend)
- https://github.com/carlosvalarezo/bffchatjs (Backend for frontend)
- https://github.com/carlosvalarezo/uichatjs (Frontend)

To run everything just execute `sh start.sh`

