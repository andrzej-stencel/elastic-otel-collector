# Elastic OTel Collector

[EDOT Collector], but without Elastic Agent.

```console
go install go.opentelemetry.io/collector/cmd/builder@v0.123.0
builder --config ./manifest.yaml
./bin/elastic-otel-collector --version
```

[EDOT Collector]: https://github.com/elastic/elastic-agent/blob/main/internal/pkg/otel/README.md
