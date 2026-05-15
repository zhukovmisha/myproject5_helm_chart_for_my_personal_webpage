# myproject5_helm_chart_for_my_personal_webpage

Helm chart for personal webpage  

## Prerequisites

- Kubernetes 1.16+
- Helm 3.0+

## Installation

### Install the chart directly
```bash
git clone https://github.com/zhukovmisha/myproject5_helm_chart_for_my_personal_webpage.git
helm install my-release ./myproject5_helm_chart_for_my_personal_webpage

```

## Architecture
Internet  
   ↓  
Ingress  
   ↓  
Service  
   ↓  
Pods (Deployment)  