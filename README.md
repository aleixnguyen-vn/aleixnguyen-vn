# 👋 Hey there, I'm Aleix Nguyen

🔧 **Production-focused Infrastructure Engineer** who debugs by reading logs, not rewriting scripts.

I specialize in building lean, reliable systems that survive real-world traffic — and more importantly, I know how to fix them when they break. My approach: understand the system from hardware up, trace every error to its root cause, and optimize for actual performance metrics, not synthetic benchmarks.

> *"I don't panic when error messages appear. I only worry when systems fail silently."*

---

## 🧠 What Makes Me Different

* **Debug-first mindset:** When scripts or systems fail, my first instinct is to read the actual error, trace the source from logs, and fix the root cause — not search for another ready-made script.
* **Hardware-to-Software Intuition:** My journey began from optimizing "ghẻ-láp" setups to building powerful PCs (e.g., R5 3600 + 1660 Super + 24GB RAM + 700GB SSD from mostly used components). This hands-on experience provides a deep understanding of performance characteristics at every hardware and software layer.
* **Production Troubleshooting & Extreme Optimization:** I excel at handling high-traffic loads (e.g., 52K+ weekly pageviews on AWS Free Tier t2.micro), achieving exceptional metrics like 99.91% Redis hit rate with minimal resources.
* **No-Panel Philosophy (AZDigi Inspired):** Every configuration is written by hand and understood from first principles. I favor manual, granular control over reliance on control panels for ultimate efficiency and troubleshooting clarity.

---

## 🔧 Core Competencies

* 🚀 **Build & Fortify Production Systems:** Design and optimize server architectures for maximum performance, stability, and cost-efficiency under real-world loads.
* 🤖 **Automate Everything (Almost):** Craft robust scripts and tooling to streamline deployments and infrastructure operations, ensuring reliability and speed.
* ☁️ **Cloud Resource Whisperer & Multi-Cloud Master:** Expertly deploy, configure, and fine-tune applications across AWS, Vultr, Azure, and other cloud providers. I excel at squeezing out optimal performance while slashing unnecessary cloud costs, even running personal web projects on AWS Free Tier with full manual setup.
* 📊 **Performance Demystifier:** Relentlessly benchmark live traffic, analyze bottlenecks, and engineer caching solutions (like LiteSpeed Free on 1GB RAM VPS) that deliver lightning-fast user experiences.
* 💡 **Master of Undocumented Issues & Persistence:** Fearlessly confront and relentlessly diagnose complex system/application errors, even when documentation is absent. I deep-dive into logs, filter keywords, and leverage sharp logical thinking to uncover root causes and implement solutions, gaining unique insights beyond standard tutorials.
* 🔌 **Hardware-Level Troubleshooting:** Diagnose and resolve issues at the physical server and component level, from component compatibility to thermal management, ensuring foundational system health and extracting maximum performance from any setup.

---

## 📂 Featured Case Studies

| 🎯 Project                                                 | Impact                                                                                                                        | Tech Stack                                                              |
| ---------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------- |
| **WordPress on AWS Free Tier: 52K Weekly Pageviews**       | 798MB RAM peak, 189ms avg response, 99.91% Redis hit rate, \~57,000 weekly pageviews with zero downtime on t2.micro instance. | LiteSpeed Enterprise, Redis, MariaDB, Cloudflare                        |
| **Coming Soon: Auto-Install Script for LiteSpeed**         | Bash script to deploy optimized LiteSpeed stack with 1-command setup in <5 mins, ensuring consistent performance.             | Bash Scripting, LiteSpeed, NGINX, Redis                                 |
| **Coming Soon: Hugo → WordPress Migration & Optimization** | Comprehensive migration of .md content + layout to optimized WordPress theme, focusing on performance parity and SEO.         | WordPress, Hugo, PHP, MySQL, Web Optimization                           |
| **Coming Soon: Production Incident Response Methodology**  | Systematic approach to debugging server failures and performance bottlenecks, documented through real-world scenarios.        | Log Analysis, System Monitoring, Root Cause Tracing, Bash               |
| **Coming Soon: Hardware-Optimized VPS Configuration**      | Memory and I/O optimization techniques for low-resource environments, proven on my own custom-built hardware.                 | Linux Tuning, Swap Management, Resource Monitoring, Kernel Optimization |

---

## 🛠️ Technical Philosophy

> **"No shortcuts. Just logic and logs."**

I don't rely on panels or one-click solutions. Every configuration is written by hand because understanding the system architecture is crucial when things go wrong at 3 AM. My approach extends beyond traditional troubleshooting:

**My Problem-Solving Process:**

1. Read the actual error message (90% of people skip this).
2. Trace from symptom to root cause using extensive log analysis and system monitoring tools.
3. Fix the source, not the symptom to prevent recurring issues and understand deeper system behaviors.
4. Document the solution for future reference and continuous learning, transforming errors into unique insights.

**Why This Matters:**

* Faster incident response times and higher system uptime.
* More reliable, long-term solutions built from ground-up understanding.
* Superior resource utilization and significant cost efficiency.
* Unwavering confidence to modify and adapt complex systems as business needs evolve.

---

## 🏎️ Beyond Tech: Endurance Racing

I compete in virtual endurance championships (6–24 hour races) driving Hypercar (like BMW M Hybrid V8, Porsche 963 on iRacing, LMU). This background in high-pressure, long-duration performance management directly translates to infrastructure reliability:

* Strategic resource management under sustained load (fuel, tire, battery management).
* Real-time performance optimization when every second counts (live telemetry, pit strategy).
* Team coordination during critical system deployments (multi-driver stints, quick pit stops).
* Maintaining focus during extended troubleshooting sessions (24-hour race concentration).

## 🛩️ Flight Simulation: Managing Complex Systems
Advanced flight simulation on X-Plane with wide-body airliner (B777-300ER, B747-400F, A330/A340 series) in challenging conditions. Specializing in manual approaches without ILS guidance, requiring:
- Real-time multi-system monitoring and management
- Precision control under high-stress scenarios
- Quick adaptation between different aircraft platforms (Airbus vs Boeing philosophies)
- Critical decision-making during adverse weather operations

Combined with endurance racing, this demonstrates comprehensive skills in sustained high-performance system management across different domains.
---

## 🎯 What I'm Looking For

**Remote Infrastructure Roles** where my troubleshooting skills and production experience add immediate value:

* TechOps / DevOps positions at growing companies
* Infrastructure optimization consulting
* Production support and incident response roles

**Ideal Environment:**

* Team that values deep system understanding over quick fixes.
* Production systems where reliability and performance matter.
* Opportunities to mentor others in debugging and troubleshooting methodologies.

---

## 💬 Let's Connect

* 💼 Available for remote infrastructure roles and consulting projects
* 📧 Email: `aleixnguyen@gmail.com`
* 💵 Rate: \$25–50/hour (depending on project complexity)
* 🚨 Emergency Response: Available for urgent production issues
* 🧠 Philosophy: **"Build small. Debug everything. Learn from every crash."**

---

## 🛠️ Technology Stack

**Core Infrastructure:**

* Web Servers: LiteSpeed Enterprise, NGINX
* Databases: MariaDB, MySQL with Redis object caching
* Cloud Platforms: AWS (EC2, S3, Route 53, CloudFront), Vultr, Azure, Cloudflare
* Operating Systems: Ubuntu Server, CentOS, Linux (General)
* Monitoring: System logs (`journalctl`, `nginx.log`), custom bash scripts, `htop`, `uptime`, `iotop`, `vmstat`, `free -m`

**Languages & Tools:**

* Scripting: Bash, Python (for automation)
* CMS: WordPress optimization and custom configurations, Hugo
* Version Control: Git, GitHub Actions (for basic CI/CD)
* Security: UFW, fail2ban, SSL/TLS configuration
* Networking: DNS, Subdomains, A Record, CNAME
* Other Tools: `crontab`, WP-CLI

---

🧠 All case studies are built, tested, and documented from real production deployments. No theoretical examples or copy-paste tutorials.
