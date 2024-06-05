# About

The unofficial JSON Schema for Docker Stack files. A modification of the [compose-spec/schema/compose-spec.json](https://github.com/compose-spec/compose-spec/blob/master/schema/compose-spec.json)

## Usage

Add the following line to your `docker-stack.yml` or `docker-compose.yml` file:

```yaml
# yaml-language-server: $schema=https://raw.githubusercontent.com/swarmlibs/dockerstack-schema/main/schema/dockerstack-spec.json

services:
  my-service:
    image: my-image
```
