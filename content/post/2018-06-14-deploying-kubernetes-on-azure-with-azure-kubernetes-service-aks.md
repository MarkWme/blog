---
title: "Deploying Kubernetes on Azure with Azure Kubernetes Service (AKS)"
date: 2018-06-14T12:02:43+01:00
draft: false
description: "Kubernetes the **easy** way"
tags:
- azure
- kubernetes
- k8s
- aks
---
![Kubernetes Logo](/images/Kubernetes.png)

With the ever increasing popularity of Kubernetes, cloud providers are now going out of their way to get you running Kubernetes on their platform.

Installation is simple:

{{< highlight bash >}}
az aks create --name wibble
az aks create --name thisisaratherlongname --group reallycouldthisbeanylonger --someotheroption wowthisisreallygettingquitelongnow
{{< /highlight >}}

And also

{{< highlight html >}}
<section id="main">
  <div>
    <h1 id="title">{{ .Title }}</h1>
    {{ range .Data.Pages }}
      {{ .Render "summary"}}
    {{ end }}
  </div>
</section>
{{< /highlight >}}
---
