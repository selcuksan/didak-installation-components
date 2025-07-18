# Didak Installation Components Structure

```markdown
├── Chart.yaml
├── values.yaml
├── charts/
├── environments/
│   ├── dev/
│   └── test/
│       ├── alloy/
│       │   └── alloy-values.yaml
│       ├── cilium/
│       │   └── cilium-values.yaml
│       ├── grafana/
│       │   └── grafana-values.yaml
│       ├── logging-stack/
│       │   └── loki-values.yaml
│       ├── monitoring-stack/
│       │   ├── kube-prometheus-stack-values.yaml
│       │   └── mimir-values.yaml
│       └── tracing-stack/
│           ├── tempo-operator.yaml
│           └── tempostack-instance.yaml
├── templates/
│   ├── alloy/
│   │   ├── alloy-applicationset.yaml
│   │   └── alloy-appProject.yaml
│   ├── cilium/
│   │   ├── cilium-applicationset.yaml
│   │   └── cilium-appProject.yaml
│   ├── grafana/
│   │   ├── grafana-applicationset.yaml
│   │   └── grafana-appProject.yaml
│   ├── logging-stack/
│   │   ├── logging-appProject.yaml
│   │   └── loki-applicationset.yaml
│   ├── monitoring-stack/
│   │   ├── kube-prometheus-applicationset.yaml
│   │   ├── mimir-applicationset.yaml
│   │   └── monitoring-appProject.yaml
│   └── tracing-stack/
│       ├── tempo-applicationset.yaml
│       └── tracing-appProject.yaml
