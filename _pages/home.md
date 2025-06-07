---
layout: splash
permalink: /
hidden: false
header:
  overlay_color: "#ff6b35"
  overlay_filter: "0.5"
  overlay_image: /assets/images/dioptra-home.jpg
  actions:
    - label: "<i class='fas fa-database'></i> Access Data"
      url: "/data/"
      class: "btn--primary btn--large"
    - label: "<i class='fas fa-info-circle'></i> Learn More"
      url: "/about/"
      class: "btn--inverse btn--large"
excerpt: >
  Sorbonne IPRS provides continuous monitoring of IP-level routing across the internet through 
  regular collection of traceroute-style measurements from multiple vantage points towards a 
  significant portion of the internet's routable address blocks.
feature_row:
  - image_path: /assets/images/ipv4-icon.png
    alt: "IPv4 Coverage"
    title: "Daily IPv4 Snapshots"
    excerpt: "Four daily IPv4 snapshots featuring multipath route traces from ten vantage points, covering all routable IPv4 /24 prefixes"
    url: "/data/#ipv4"
    btn_class: "btn--primary"
    btn_label: "IPv4 Data"
  - image_path: /assets/images/ipv6-icon.png
    alt: "IPv6 Coverage"
    title: "IPv6 Monitoring"
    excerpt: "Daily IPv6 snapshots with single-path route traces covering a substantial number of prefixes"
    url: "/data/#ipv6"
    btn_class: "btn--primary"
    btn_label: "IPv6 Data"
  - image_path: /assets/images/research-icon.png
    alt: "Research Quality"
    title: "Research Excellence"
    excerpt: "Snapshots collected at higher frequency than comparable initiatives, providing detailed routing insights"
    url: "/about/"
    btn_class: "btn--primary"
    btn_label: "About IPRS"
feature_row2:
  - image_path: /assets/images/mlab-logo.png
    title: "Measurement Lab Access"
    excerpt: 'IPv4 snapshots accessible via **Measurement Lab''s Google BigQuery tables**, compatible with existing traceroute data formats.'
    url: "https://www.measurementlab.net"
    btn_label: "Visit M-Lab"
    btn_class: "btn--primary"
  - image_path: /assets/images/dioptra-logo.png
    title: "Direct from Dioptra"
    excerpt: 'Contact **Dioptra** directly for detailed IPv4 data, IPv6 datasets, and custom formats including ClickHouse tables.'
    url: "mailto:iprs@dioptra.io"
    btn_label: "Contact Us"
    btn_class: "btn--primary"
---

<div style="text-align: center; margin: 2rem 0;">
  <p style="font-size: 1.2rem; color: #666;">
    Conducted by the <strong>Dioptra research group</strong> at 
    <a href="https://sorbonne-universite.fr/en">Sorbonne University</a>'s 
    <a href="https://www.lip6.fr/?LANG=en">LIP6</a> computer science laboratory
  </p>
</div>

{% include feature_row %}

## Data Access Methods

{% include feature_row id="feature_row2" %}

<div style="background: #0f172a; color: white; padding: 3rem 2rem; border-radius: 16px; margin: 3rem 0; text-align: center;">
  <h2 style="color: white; margin-bottom: 2rem;">Current Coverage</h2>
  <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 2rem;">
    <div style="text-align: center;">
      <div style="font-size: 3rem; font-weight: 700; color: #ff6b35; display: block;">4×</div>
      <div style="font-size: 1.1rem; opacity: 0.9; margin-top: 0.5rem;">Daily IPv4 Snapshots</div>
    </div>
    <div style="text-align: center;">
      <div style="font-size: 3rem; font-weight: 700; color: #ff6b35; display: block;">10</div>
      <div style="font-size: 1.1rem; opacity: 0.9; margin-top: 0.5rem;">Vantage Points</div>
    </div>
    <div style="text-align: center;">
      <div style="font-size: 3rem; font-weight: 700; color: #ff6b35; display: block;">All</div>
      <div style="font-size: 1.1rem; opacity: 0.9; margin-top: 0.5rem;">Routable IPv4 /24 Prefixes</div>
    </div>
    <div style="text-align: center;">
      <div style="font-size: 3rem; font-weight: 700; color: #ff6b35; display: block;">1×</div>
      <div style="font-size: 1.1rem; opacity: 0.9; margin-top: 0.5rem;">Daily IPv6 Snapshot</div>
    </div>
  </div>
</div>

---

## Recent Updates

**December 2023**: IPRS provides comprehensive coverage with four daily IPv4 snapshots and one daily IPv6 snapshot, maintaining our commitment to high-frequency internet routing monitoring.

**Partnership**: IPv4 snapshots are now accessible via Measurement Lab's infrastructure, making our data more accessible to the global research community.

---

<div class="notice--info">
  <h3>Citation Guidelines</h3>
  <p>When using IPRS data in your research, please cite appropriately:</p>
  <ul>
    <li><strong>M-Lab Data</strong>: "M-Lab's Sorbonne IPRS Data Set, &lt;date range used&gt;"</li>
    <li><strong>Direct Data</strong>: "The Sorbonne IPRS Data Set, &lt;date range used&gt;"</li>
  </ul>
</div>
