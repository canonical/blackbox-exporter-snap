<h1 align="center">
  <img src="prometheus_software_logo.svg?raw=true" alt="Prometheus Blackbox Exporter">
  <br />
  Prometheus Blackbox Exporter
</h1>

<!-- UPDATE WHEN WE HAVE RELEASE CI FOR THIS SNAP
<p align="center"><a href="https://github.com/canonical/grafana-agent-snap/actions/workflows/release-snap.yaml"><img src="https://github.com/canonical/grafana-agent-snap/actions/workflows/release-snap.yaml/badge.svg"></a></p> 
-->

<p align="center"><b>This is the snap for Prometheus Blackbox Exporter</b>, <p>The blackbox exporter allows blackbox probing of endpoints over HTTP, HTTPS, DNS, TCP, ICMP and gRPC.</p> This snap works on Ubuntu, Fedora, Debian, and any Linux distribution that supports <i>snapd</i>.</p>

<p align="center"><a href="https://snapcraft.io/prometheus-blackbox-exporter"><img src="https://snapcraft.io/prometheus-blackbox-exporter/badge.svg" alt="blackbox-exporter badge"/><a/></p>

<p align="center">Published for <img src="https://raw.githubusercontent.com/anythingcodes/slack-emoji-for-techies/gh-pages/emoji/tux.png" align="top" width="24" /> with 💝 by Snapcrafters</p>

## Install

```
sudo snap install prometheus-blackbox-exporter
```

<!-- Uncomment and modify this when your snap is available on the store
[![Get it from the Snap Store](https://snapcraft.io/static/images/badges/en/snap-store-white.svg)](https://snapcraft.io/grafana-agent)
-->

([Don't have snapd installed?](https://snapcraft.io/docs/core/install))

## Configuration

Once installed, a default configuration file will be created at `/var/snap/prometheus-blackbox-exporter/current/blackbox.yml`. Before starting the agent, make sure to update this configuration file to suit you needs, consulting the [official documentation](https://github.com/prometheus/blackbox_exporter/blob/master/CONFIGURATION.md). 
