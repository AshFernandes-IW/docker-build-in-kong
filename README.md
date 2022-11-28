## Installation Instructions

- Ensure the latest version of Docker is installed: https://www.docker.com/products/docker-desktop/
- Clone the repository from GitHub
- Open a terminal in the repository directory and type `docker-compose up`
- The docker container with Kong installed should now be running

### How to access Kong Manager
- Open up your web browser and type ``localhost:8002``
- Scroll down and access the **default workspace**
- Create a new service and edit the parameters **host** and **path** to ``en.wikipedia.org`` and ``/wiki/Electric_fish`` respectively
- Create a new route and edit the parameters **Name**, **Protocols**, and **Paths** to ``electric-fish``, ``http``, and ``/electric-fish`` respectively

- Open a new tab and enter ``http://localhost:8000/electric-fish`` in the address bar
- This should be your final outcome ![outcome](https://github.com/AshFernandes-IW/docker-build-in-kong/blob/main/fish.png)
