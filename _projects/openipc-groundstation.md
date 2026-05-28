---
title: OpenIPC RubyFPV groundstation
category: Personal build
order: 4
hero: /assets/images/openipc-groundstation-hero.jpg
thumbnail: /assets/images/project-details/openipc-case.jpg
hero_alt: OpenIPC RubyFPV groundstation CAD enclosure, component layout, and assembled electronics build.
summary: Compact OpenIPC/RubyFPV groundstation packaging around a Radxa SBC, Wi-Fi radios, power regulation, cooling, antennas, and controls.
role: Personal design, component selection, enclosure design, and build
tools: CAD assembly design, 3D printing, electronics packaging, OpenIPC, RubyFPV
source: Summarised from personal project write-up
facts:
  - OpenIPC / RubyFPV
  - Electronics packaging
  - 3D printed enclosure
  - RF + thermal layout
---

## Context

Open-source digital FPV avoids the lock-in of closed video systems while keeping low latency and high image quality. This build packages the receiver hardware into something usable, not just a bench setup.

<figure>
  <img src="/assets/images/project-details/openipc-components.jpg" alt="Annotated OpenIPC groundstation component layout with radios, regulators, USB hub, capacitors, fan, and connectors">
  <figcaption>Core packaging problem: radios, power, cooling, antennas, and controls all need external access or airflow.</figcaption>
</figure>

## Build

Radxa Zero 3W, Wi-Fi radio cards, USB hub, 5V regulation, capacitors, SMA pigtails, fan, XT-30 power, and navigation controls in a printed enclosure.

<figure>
  <img src="/assets/images/project-details/openipc-case.jpg" alt="Transparent CAD enclosure showing the OpenIPC groundstation electronics packed inside">
  <figcaption>Designed in assembly context so the enclosure followed the electronics, not the other way round.</figcaption>
</figure>

## Iteration

- First layout was too large and weak on mounting.
- Smaller regulators enabled a tighter internal arrangement.
- External SMA, fan intake, buttons, USB, and power had to remain usable after assembly.

<figure>
  <img src="/assets/images/project-details/openipc-build.jpg" alt="Partially assembled OpenIPC groundstation electronics in a black 3D printed case">
  <figcaption>Physical build check: wiring, connectors, and board heights are the real constraints.</figcaption>
</figure>
