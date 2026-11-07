# Mount Olympus

Mount Olympus is a private homelab dashboard for monitoring Ubuntu, Docker workloads, Mneme, and Pi-hole. It also lets you manage selected workloads and use Ollama on a gaming PC.

See the [dashboard guide](dashboard/README.md) to set it up on Ubuntu, open it on an iPhone with Tailscale, or follow a metric from the collector to the browser.

To try it with sample data from the repository root, run:

```sh
PYTHONPATH=. python3 dashboard/server.py --demo --port 8791
```

Then open [the local demo](http://127.0.0.1:8791/).
