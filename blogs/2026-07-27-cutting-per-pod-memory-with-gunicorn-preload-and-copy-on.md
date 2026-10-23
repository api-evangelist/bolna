---
title: "Cutting per-pod memory with gunicorn preload and copy-on-write"
url: "https://www.bolna.ai/blog/cutting-per-pod-memory-gunicorn-preload"
date: "2026-07-27"
feed_url: "https://www.bolna.ai/blog/rss.xml"
---
Our real-time voice service containers were using too much memory and restarting mid-call. Two fixes: preloading workers and copy-on-write sharing.
