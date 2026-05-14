# Sashank Silwal

CS grad from NYU Abu Dhabi, currently doing a master's in CS at Purdue.

Most of my work right now sits in two places:

- **Fraud detection at scale.** Model pipelines and rule-generation engines for catching bad actors in large transaction streams. A lot of the interesting problems here are about latency and explainability, not just accuracy. There's a [public write-up](https://www.binance.com/en/blog/tech/4582519158590222265) of the system if you want the details.
- **GPU-accelerated simulation + physics-informed ML for urban microclimates** at Purdue. Most of the actual work has been backend: a Redis/Celery job queue dispatching simulation runs across multiple servers and worker pools, with the ML layer sitting on top of that. The science question is how trees and built surfaces shift local temperatures, but I've spent more time on distributed systems than I expected when I signed up.

I write Python day-to-day (PyTorch, pandas, the usual), SQL when the data is big enough to warrant it, and JavaScript when I'm building something with a UI. I'm comfortable in the AWS/GCP toolchain. BigQuery and Airflow are what I reach for most often.

Outside of that, I'm slowly working through deep learning papers on recommendation systems and trying to get better at writing backend services that don't fall over (gRPC, async pipelines, the usual sharp edges).

Reach me on [LinkedIn](https://www.linkedin.com/in/sashank-silwal/) if you want to talk.
