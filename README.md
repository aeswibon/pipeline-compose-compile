# pipeline-compose-compile

Optional compile action for [pipeline-compose](https://github.com/aeswibon/pipeline-compose) — emit a static workflow YAML from pipeline YAML.

## Usage

```yaml
- uses: aeswibon/pipeline-compose-compile@v0.1.0
  with:
    pipeline_file: .github/pipelines/pipeline.yml
    output: .github/workflows/pipeline.generated.yml
```

Most users should use [pipeline-compose-run](https://github.com/aeswibon/pipeline-compose-run) instead.

## Development

```bash
pnpm install
pnpm test
pnpm run bundle
```

## License

MIT
