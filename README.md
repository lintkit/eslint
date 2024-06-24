# LintKit: ESLint

An opinionated configuration of [ESLint](https://eslint.org/).

## Usage

### GitLab

```yaml
# Lint the PHP
.js:eslint:
  image: ghcr.io/lintkit/eslint-kit:1
  script:
    - /lintkit
```

### GitHub

```yaml
- name: Lint PHP
  uses: lintkit/eslint-kit@v1
```

### Local

```bash
docker pull ghcr.io/lintkit/eslint-kit:1
docker run -it --rm -v $(pwd):/app ghcr.io/lintkit/eslint-kit
```
