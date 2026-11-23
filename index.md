---
layout: default
title: Home
---

<section class="hero">
  <div class="hero-text">
    <p class="eyebrow">Welcome</p>
    <p class="lead">{{ site.tagline }}. This site collects my code samples, working demos and notes I find worth keeping.</p>
    <a class="btn" href="{{ '/demos/' | relative_url }}">Browse demos</a>
    <a class="btn secondary" href="https://github.com/{{ site.github_username }}">GitHub profile</a>
  </div>
  <div class="hero-logos">
    <a href="https://www.confluent.io" aria-label="Confluent"><img src="{{ '/assets/img/confluent.png' | relative_url }}" alt="Confluent"></a>
    <a href="https://www.ibm.com" aria-label="IBM"><img src="{{ '/assets/img/ibm.svg' | relative_url }}" alt="IBM"></a>
  </div>
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

## About Me

I am a dynamic and accomplished Data Streaming Architect specializing in the design, implementation, and optimization of highly available, low-latency streaming solutions with Confluent Cloud, Kafka Connect, and Apache Flink across AWS, GCP, and Azure.

I build robust, scalable pipelines that support operational and analytical workloads in public and hybrid cloud environments, delivering governed streaming-to-table ingestion into enterprise data lakes, Databricks, and Snowflake lakehouses.
