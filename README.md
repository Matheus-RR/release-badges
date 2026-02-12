# Release Badges

**Live release health, EOL countdowns, and CVE badges for 300+ software products.**

These badges pull real-time data from [ReleaseRun](https://releaserun.com/badges/) and update automatically â no API keys, no maintenance. Add them to your README, docs, or dashboard.

## Badge Types

| Type | What it shows | Example |
|------|--------------|---------|
| **Health** | Overall release health grade (AâF) | ![Python Health](https://img.releaserun.com/badge/health/python.svg) |
| **EOL** | End-of-life countdown | ![Node.js 20 EOL](https://img.releaserun.com/badge/eol/nodejs/20.svg) |
| **CVE** | Known vulnerability count | ![K8s 1.35 CVEs](https://img.releaserun.com/badge/cve/kubernetes/1.35.svg) |

Health grades combine freshness (35%), security (35%), and support status (30%). [How scoring works â](https://releaserun.com/badges/)

## How to Use

**Markdown (GitHub READMEs, GitLab, docs):**
```markdown
[![Python Health](https://img.releaserun.com/badge/health/python.svg)](https://releaserun.com/badges/python/)
[![Python 3.12 EOL](https://img.releaserun.com/badge/eol/python/3.12.svg)](https://releaserun.com/badges/python/)
```

**HTML:**
```html
<a href="https://releaserun.com/badges/python/">
  <img src="https://img.releaserun.com/badge/health/python.svg" alt="Python release health">
</a>
```

**URL pattern:**
```
https://img.releaserun.com/badge/{type}/{product}.svg           # latest version
https://img.releaserun.com/badge/{type}/{product}/{version}.svg  # specific version
```

---

## Languages

### Python
[![Health](https://img.releaserun.com/badge/health/python.svg)](https://releaserun.com/badges/python/)

EOL status per version:
[![Python 3.14](https://img.releaserun.com/badge/eol/python/3.14.svg)](https://releaserun.com/badges/python/)
[![Python 3.13](https://img.releaserun.com/badge/eol/python/3.13.svg)](https://releaserun.com/badges/python/)
[![Python 3.12](https://img.releaserun.com/badge/eol/python/3.12.svg)](https://releaserun.com/badges/python/)
[![Python 3.11](https://img.releaserun.com/badge/eol/python/3.11.svg)](https://releaserun.com/badges/python/)
[![Python 3.10](https://img.releaserun.com/badge/eol/python/3.10.svg)](https://releaserun.com/badges/python/)

### Node.js
[![Health](https://img.releaserun.com/badge/health/nodejs.svg)](https://releaserun.com/badges/nodejs/)

LTS support windows:
[![Node 24](https://img.releaserun.com/badge/eol/nodejs/24.svg)](https://releaserun.com/badges/nodejs/)
[![Node 22](https://img.releaserun.com/badge/eol/nodejs/22.svg)](https://releaserun.com/badges/nodejs/)
[![Node 20](https://img.releaserun.com/badge/eol/nodejs/20.svg)](https://releaserun.com/badges/nodejs/)

### Go
[![Health](https://img.releaserun.com/badge/health/go.svg)](https://releaserun.com/badges/go/)

[![Go 1.24](https://img.releaserun.com/badge/eol/go/1.24.svg)](https://releaserun.com/badges/go/)
[![Go 1.23](https://img.releaserun.com/badge/eol/go/1.23.svg)](https://releaserun.com/badges/go/)

### Rust
[![Health](https://img.releaserun.com/badge/health/rust.svg)](https://releaserun.com/badges/rust/)

### Ruby
[![Health](https://img.releaserun.com/badge/health/ruby.svg)](https://releaserun.com/badges/ruby/)

[![Ruby 3.3](https://img.releaserun.com/badge/eol/ruby/3.3.svg)](https://releaserun.com/badges/ruby/)
[![Ruby 3.2](https://img.releaserun.com/badge/eol/ruby/3.2.svg)](https://releaserun.com/badges/ruby/)

### PHP
[![Health](https://img.releaserun.com/badge/health/php.svg)](https://releaserun.com/badges/php/)

[![PHP 8.4](https://img.releaserun.com/badge/eol/php/8.4.svg)](https://releaserun.com/badges/php/)
[![PHP 8.3](https://img.releaserun.com/badge/eol/php/8.3.svg)](https://releaserun.com/badges/php/)
[![PHP 8.2](https://img.releaserun.com/badge/eol/php/8.2.svg)](https://releaserun.com/badges/php/)

### Java
[![Health](https://img.releaserun.com/badge/health/java.svg)](https://releaserun.com/badges/java/)

[![Java 25](https://img.releaserun.com/badge/eol/java/25.svg)](https://releaserun.com/badges/java/)
[![Java 21](https://img.releaserun.com/badge/eol/java/21.svg)](https://releaserun.com/badges/java/)
[![Java 17](https://img.releaserun.com/badge/eol/java/17.svg)](https://releaserun.com/badges/java/)

### .NET
[![Health](https://img.releaserun.com/badge/health/dotnet.svg)](https://releaserun.com/badges/dotnet/)

[![.NET 10](https://img.releaserun.com/badge/eol/dotnet/10.svg)](https://releaserun.com/badges/dotnet/)
[![.NET 9](https://img.releaserun.com/badge/eol/dotnet/9.svg)](https://releaserun.com/badges/dotnet/)
[![.NET 8](https://img.releaserun.com/badge/eol/dotnet/8.svg)](https://releaserun.com/badges/dotnet/)

---

## Infrastructure

### Kubernetes
[![Health](https://img.releaserun.com/badge/health/kubernetes.svg)](https://releaserun.com/badges/kubernetes/)

Support window + CVE status:
[![K8s 1.35 EOL](https://img.releaserun.com/badge/eol/kubernetes/1.35.svg)](https://releaserun.com/badges/kubernetes/)
[![K8s 1.34 EOL](https://img.releaserun.com/badge/eol/kubernetes/1.34.svg)](https://releaserun.com/badges/kubernetes/)
[![K8s 1.33 EOL](https://img.releaserun.com/badge/eol/kubernetes/1.33.svg)](https://releaserun.com/badges/kubernetes/)
[![K8s 1.35 CVEs](https://img.releaserun.com/badge/cve/kubernetes/1.35.svg)](https://releaserun.com/badges/kubernetes/)
[![K8s 1.34 CVEs](https://img.releaserun.com/badge/cve/kubernetes/1.34.svg)](https://releaserun.com/badges/kubernetes/)

### Docker
[![Health](https://img.releaserun.com/badge/health/docker-engine.svg)](https://releaserun.com/badges/docker/)

[![Docker 28](https://img.releaserun.com/badge/eol/docker-engine/28.svg)](https://releaserun.com/badges/docker/)
[![Docker 27](https://img.releaserun.com/badge/eol/docker-engine/27.svg)](https://releaserun.com/badges/docker/)

### PostgreSQL
[![Health](https://img.releaserun.com/badge/health/postgresql.svg)](https://releaserun.com/badges/postgresql/)

[![PG 17](https://img.releaserun.com/badge/eol/postgresql/17.svg)](https://releaserun.com/badges/postgresql/)
[![PG 16](https://img.releaserun.com/badge/eol/postgresql/16.svg)](https://releaserun.com/badges/postgresql/)
[![PG 15](https://img.releaserun.com/badge/eol/postgresql/15.svg)](https://releaserun.com/badges/postgresql/)

### Redis
[![Health](https://img.releaserun.com/badge/health/redis.svg)](https://releaserun.com/badges/redis/)

[![Redis 8.0](https://img.releaserun.com/badge/eol/redis/8.0.svg)](https://releaserun.com/badges/redis/)
[![Redis 7.4](https://img.releaserun.com/badge/eol/redis/7.4.svg)](https://releaserun.com/badges/redis/)

### Nginx
[![Health](https://img.releaserun.com/badge/health/nginx.svg)](https://releaserun.com/badges/nginx/)

[![Nginx 1.28](https://img.releaserun.com/badge/eol/nginx/1.28.svg)](https://releaserun.com/badges/nginx/)
[![Nginx 1.27](https://img.releaserun.com/badge/eol/nginx/1.27.svg)](https://releaserun.com/badges/nginx/)

### Terraform
[![Health](https://img.releaserun.com/badge/health/terraform.svg)](https://releaserun.com/badges/terraform/)

[![Terraform 1.14](https://img.releaserun.com/badge/eol/terraform/1.14.svg)](https://releaserun.com/badges/terraform/)
[![Terraform 1.13](https://img.releaserun.com/badge/eol/terraform/1.13.svg)](https://releaserun.com/badges/terraform/)

---

## Supported Products

Any product tracked by [endoflife.date](https://endoflife.date) works â currently **300+** products. Just use the product's slug:

```
https://img.releaserun.com/badge/health/{slug}.svg
```

Popular slugs: `python`, `nodejs`, `kubernetes`, `docker-engine`, `go`, `rust`, `ruby`, `php`, `java`, `dotnet`, `postgresql`, `nginx`, `terraform`, `redis`, `mysql`, `mongodb`, `elasticsearch`, `angular`, `react`, `vue`, `django`, `rails`, `spring-boot`, `laravel`

## How It Compares to Shields.io

| Feature | Shields.io | ReleaseRun |
|---------|-----------|------------|
| Version number | â | â |
| Custom labels/colours | â | â |
| CVE count per version | â | â |
| EOL countdown | â | â |
| Composite health grade | â | â |
| Support window dates | â | â |

Use both. Shields.io for build status, coverage, license. ReleaseRun for version health, EOL warnings, CVE visibility.

## Links

- [All available badges](https://releaserun.com/badges/)
- [How to embed badges in your project](https://releaserun.com/how-to-add-version-health-badges-to-your-project/)
- [Badge API docs](https://releaserun.com/badges/)

