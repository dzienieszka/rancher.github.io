---
title: Rancher API - kubernetesStackUpgrade
layout: rancher-api-default
version: latest
lang: en
---

## KubernetesStackUpgrade



### Resource Fields

Field | Type | Create | Update | Default | Notes
---|---|---|---|---|---
environment | map[string] | Optional | - | - | 
externalId | string | Optional | - | - | 
templates | map[string] | Optional | - | - | 

<br>
Please read more about the [common resource fields]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/common/). These fields are read only and applicable to almost every resource. We have segregated them from the list above.

### Operations
{::options parse_block_html="true" /}
<a id="create"></a>
<div class="action"><span class="header">Create<span class="headerright">POST:  <code>/v1/kubernetesStackUpgrades</code></span></span>
<div class="action-contents">
{% highlight json %}
{
	"environment": {
		"key1": "value1",
		"key2": "value2",
		"keyN": "valueN"
	},
	"externalId": "string",
	"templates": {
		"key1": "value1",
		"key2": "value2",
		"keyN": "valueN"
	}
}
{% endhighlight %}
</div>
</div>

