Today I am creating a Interface i.e. Flagger
It lowers the risk of deploying a new software version into production by gradually transitioning traffic to the new version while monitoring metrics and executing conformance tests. 

Flagger uses a service mesh (App Mesh, Istio, Linkerd, Kuma, Open Service Mesh) or an ingress controller (Contour, Gloo, NGINX, Skipper, Traefik) to implement multiple deployment techniques (Canary releases, A/B testing, Blue/Green mirroring).
Flagger may query Prometheus, InfluxDB, Datadog, New Relic, CloudWatch, Stackdriver, or Graphite for release analysis, and Slack, MS Teams, Discord, and Rocket for alerting. 
