---
type: independent-topic-example
subject: DevOps & Cloud
aliases:
  - Docker example
---
# EXAMPLE — Docker Images and Containers (Independent Topic)

> [!info] Original, short example
> This illustrates how a mixed-resource independent-learning note can include sources near claims, a small shell experiment, and troubleshooting. It is not intended to replace Docker's documentation.

**Research question:** What's the difference between an image and a container?

## Explanation — in my own words
A **Docker image** is a packaged template used to create containers. A **container** is a runnable instance created from an image. You can create more than one container from the same image.

**Source:** [Docker's overview](https://docs.docker.com/get-started/docker-overview/). **My status:** Explanation read; commands below not yet tested in this example.

## Vocabulary and key ideas
- **Image:** A packaged filesystem and configuration used to create a container.
- **Container:** An instance with its own runtime state.

## Implementation — original example
```bash
docker pull hello-world
docker run --rm hello-world
```

`docker pull` downloads the image; `docker run` creates and starts a container. `--rm` requests removal of the container after it exits. Check current official usage for versions and platform-specific details.

**Command source:** [Docker CLI reference](https://docs.docker.com/reference/cli/docker/container/run/). **My verification:** Not yet; replace this line after running the commands yourself.

## Common errors
| Symptom | Possible cause | What to check |
| --- | --- | --- |
| Command not found | CLI not installed or not in PATH | Installation and terminal environment |
| Cannot connect to Docker daemon | Docker service/engine may not be running or accessible | Service status and permissions |

## Practical experiment
- **Prediction:** Running the example will produce a message from the container and exit.
- **My output:** [Run it and record the result]
- **Working program:** [Your own short public-safe example or workspace label]

## Manual review
- [ ] Explain the difference between an image and a container without looking.
- [ ] Run a small container independently.
