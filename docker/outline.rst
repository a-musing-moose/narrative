Notes
=====

I could explain each technology in sequence and then present the *solution* or I could write it more like a story, with each hurdle and discovery in turn? Perhaps even set up a git repo with tags for each chapter? I would likely still need a brief introduction to Docker.

1. Introductions
2. Containers
	- What are containers
	- Why use them locally
		- Backing services (parity)
		- Isolation
		- Targetted (parity)
		- Repeatability
	- Docker
		- Compose
3. A Project Starter
	- General project structure
	- Dockerfiles
	- Volumes
	- Running it using just Docker
	- Docker Compose

4. Development processes in Docker
   	- one off tasks (management commands, migrations, tests, linting etc)
	- docker exec
	- rind

5. Volumes and Permissions
	- users in Docker
	- uid/gid mapping
	- entry points

6. Testing
	- Tests as one off tasks
	- Continuous Integration (testing)
	- Other kinds of testing (linting, type checking etc.)

7. Continuous Integration
	- Beyond testing
	- Docker registries

8. Taking it to Production
	- Simple single container deployment
	- Docker swarm
		- an aside on Kubernetes

Other topics
------------

- Secrets and configuration

