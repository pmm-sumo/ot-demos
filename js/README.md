# Overview

Simple demo based on opentelemetry-js example
<!-- TODO: This example needs an update. -->

## Installation

```shell script
# from this directory
npm install
```

1. Export environment variable with OTLP/HTTP endpoint url

   ```shell script
   export OTEL_EXPORTER_OTLP_ENDPOINT=...
   ```

2. Run tracing app

    ```shell script
    # from this directory
    npm run start:tracing
    ```

3. Run metrics app

    ```shell script
    # from this directory
    npm run start:metrics
    ```

## LICENSE

Apache License 2.0
