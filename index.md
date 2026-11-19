---
layout: default
title: Home
---

<section class="hero">
  <p class="eyebrow">Welcome</p>
  <h1>{{ site.title }}</h1>
  <p class="lead">{{ site.tagline }}. This site collects my code samples, working demos and notes I find worth keeping.</p>
  <a class="btn" href="{{ '/demos/' | relative_url }}">Browse demos</a>
  <a class="btn secondary" href="https://github.com/{{ site.github_username }}">GitHub profile</a>
</section>

## Explore

<div class="cards">
  <a class="card" href="{{ '/code/' | relative_url }}">
    <h3>Code</h3>
    <p>Sample projects, utilities and configuration examples.</p>
  </a>
  <a class="card" href="{{ '/demos/' | relative_url }}">
    <h3>Demos</h3>
    <p>End-to-end walkthroughs you can run yourself.</p>
  </a>
  <a class="card" href="{{ '/kb/' | relative_url }}">
    <h3>KB</h3>
    <p>Knowledge base: how-tos, troubleshooting and quick references.</p>
  </a>
</div>

## About

Dynamic and accomplished Data Streaming Architect specializing in the design, implementation, and optimization of highly available, low-latency streaming solutions with Confluent Cloud, Kafka Connect, and Apache Flink across AWS, GCP, and Azure. Builds robust, scalable pipelines that support operational and analytical workloads in public and hybrid cloud environments, delivering governed streaming-to-table ingestion into enterprise data lakes, Databricks, and Snowflake lakehouses.
