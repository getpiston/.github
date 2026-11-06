<a href="https://piston.sh">
  <picture>
    <source media="(prefers-reduced-motion: reduce)" srcset="https://github.com/getpiston/.github/raw/main/profile/assets/hero.png">
    <img src="https://github.com/getpiston/.github/raw/main/profile/assets/hero.gif" width="100%" alt="Piston, the fastest way to run GitHub Actions at a fraction of the cost. One line in a workflow moves a job to Piston, and the build goes from 13m 04s on GitHub-hosted runners to 1m 38s.">
  </picture>
</a>

### The fastest way to run GitHub Actions at a fraction of the cost.

| Reduced cost | Faster builds | Faster cache |
| :---: | :---: | :---: |
| up to 70% | up to 3× | up to 4× |

### Move your CI to Piston

One line in your workflow. Everything else stays the same.

```diff
 jobs:
   build:
-    runs-on: ubuntu-latest
+    runs-on: piston-8cpu-ubuntu-2402
     steps:
       - uses: actions/checkout@v4
```

[Get started](https://app.piston.sh), or read the [docs](https://piston.sh/docs/).

### Best-in-class tracing

An unmatched UX. The same GitHub job logs but with far more performance and machine metrics visibility, correlating each log line with metrics.

### The Secure way to do CI

No more complex VPNs, Bastion hosts, or insecure static IP allowlists. Install Piston Connector in your internal network, and give jobs a direct, secure tunnel to your internal network. Add [getpiston/tunnel-action](https://github.com/getpiston/tunnel-action) to any job to open its tunnel.

### Fine-grained access by identity

Jobs in your GitHub should never have full unrestricted network access. Piston Connector uses GitHub job identities to power strong, rule-based access control to every resource in your network.

### Deep network observability

Access logs of every internal network access made by your jobs with their identity, giving you visibility and audit of what your CI accessed in your network.

### Bare-metal hardware on steroids

For performance we threw in the kitchen sink: the highest-frequency CPUs, hyper-performant NVMe disks, a 4× faster colocated GitHub cache and up to 10 Gbps network download speed.

### The right size for the job

Deep observability into resource percentiles during execution lets Piston suggest or auto-tune the right size for your job.

---

[piston.sh](https://piston.sh) &nbsp;&nbsp; [Docs](https://piston.sh/docs/) &nbsp;&nbsp; [Log in](https://app.piston.sh) &nbsp;&nbsp; [info@polyform.io](mailto:info@polyform.io)
