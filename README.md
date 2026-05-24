# Aleix Nguyen — DevOps Engineer

📍 Vietnam &nbsp;·&nbsp; 🌐 Remote-ready &nbsp;·&nbsp; 📧 aleixnguyen@gmail.com

DevOps engineer with hands-on experience in Linux administration, container infrastructure, and CI/CD automation since 2021. Currently operating a live production platform serving 4,000–5,000 daily sessions on self-managed infrastructure.

## 🛠 Tech Stack

| Skills | |
|---|---|
| **Cloud & Infra** | AWS (EC2, S3) · Vultr · DigitalOcean · Azure/GCP (basic) |
| **Containers** | Docker · Docker Compose |
| **IaC & CI/CD** | Terraform · GitHub Actions · GitLab CI/CD |
| **Web & Proxy** | NGINX · Caddy (HTTP/3) · PHP-FPM · LiteSpeed |
| **DB & Cache** | MariaDB · Redis |
| **Security** | UFW · SSH hardening · SSL/TLS · Docker network isolation |
| **Tools** | Git · Bash · Cloudflare (DNS, CDN, Edge Cache) |

---

## 🚀 Projects

### 🔹 [Content Distribution Platform](https://github.com/aleixnguyen-vn/simracing-community-platform-stack)
> Self-managed production platform on €5.78/month infrastructure

- 4,000–5,000 daily sessions · 8.2M requests/month
- ~$350 USD MRR · 62K impressions / 12K clicks/month organic
- Layered cache stack: Cloudflare Edge + Redis Object Cache + WP Super Cache

---

### 🔹 [High-Performance WordPress Stack](https://github.com/aleixnguyen-vn/docker-wordpress-performance)
> Benchmark lab: extreme load on minimal resources

- 5,000 concurrent users · 187ms avg response · 0% errors
- 99.93% Redis hit rate (241,595 hits / 179 misses)
- 431MB peak RAM on 1 vCPU / 1GB VPS

---

### 🔹 [Automated WordPress Infrastructure — IaC + CI/CD Lab](https://github.com/aleixnguyen-vn/wpfpm-project-1d-pipeline)
> From manual SSH/ClickOps to fully automated provisioning

- Terraform provisioning across Vultr and DigitalOcean environments
- Two-stage DAG pipeline with idempotent bootstrapping · zero-downtime deployment via `--build`
- Secrets injected at runtime via GitHub Repository Secrets — zero credentials in version control

---

## 📚 Currently Learning

Kubernetes · Prometheus · Grafana