
---
title: "getTlsPlatformCertificateIds"
title_tag: "fastly.getTlsPlatformCertificateIds"
meta_desc: "Documentation for the fastly.getTlsPlatformCertificateIds function with examples, input properties, output properties, and supporting types."
---



<!-- WARNING: this file was generated by Pulumi Docs Generator. -->
<!-- Do not edit by hand unless you're certain you know what you are doing! -->

Use this data source to get the IDs of available Platform TLS Certificates for use with other resources.


{{% examples %}}

## Example Usage

{{< chooser language "typescript,python,go,csharp" / >}}





{{< example csharp >}}

```csharp
using Pulumi;
using Fastly = Pulumi.Fastly;

class MyStack : Stack
{
    public MyStack()
    {
        var exampleTlsPlatformCertificateIds = Output.Create(Fastly.GetTlsPlatformCertificateIds.InvokeAsync());
        var exampleTlsPlatformCertificate = exampleTlsPlatformCertificateIds.Apply(exampleTlsPlatformCertificateIds => Output.Create(Fastly.GetTlsPlatformCertificate.InvokeAsync(new Fastly.GetTlsPlatformCertificateArgs
        {
            Id = exampleTlsPlatformCertificateIds.Ids[0],
        })));
    }

}
```


{{< /example >}}


{{< example go >}}

```go
package main

import (
	"github.com/pulumi/pulumi-fastly/sdk/v3/go/fastly"
	"github.com/pulumi/pulumi/sdk/v3/go/pulumi"
)

func main() {
	pulumi.Run(func(ctx *pulumi.Context) error {
		exampleTlsPlatformCertificateIds, err := fastly.GetTlsPlatformCertificateIds(ctx, nil, nil)
		if err != nil {
			return err
		}
		opt0 := exampleTlsPlatformCertificateIds.Ids[0]
		_, err = fastly.LookupTlsPlatformCertificate(ctx, &fastly.LookupTlsPlatformCertificateArgs{
			Id: &opt0,
		}, nil)
		if err != nil {
			return err
		}
		return nil
	})
}
```


{{< /example >}}


{{< example python >}}

```python
import pulumi
import pulumi_fastly as fastly

example_tls_platform_certificate_ids = fastly.get_tls_platform_certificate_ids()
example_tls_platform_certificate = fastly.get_tls_platform_certificate(id=example_tls_platform_certificate_ids.ids[0])
```


{{< /example >}}


{{< example typescript >}}


```typescript
import * as pulumi from "@pulumi/pulumi";
import * as fastly from "@pulumi/fastly";

const exampleTlsPlatformCertificateIds = fastly.getTlsPlatformCertificateIds({});
const exampleTlsPlatformCertificate = exampleTlsPlatformCertificateIds.then(exampleTlsPlatformCertificateIds => fastly.getTlsPlatformCertificate({
    id: exampleTlsPlatformCertificateIds.ids[0],
}));
```


{{< /example >}}





{{% /examples %}}




## Using getTlsPlatformCertificateIds {#using}

{{< chooser language "typescript,python,go,csharp" / >}}


{{% choosable language nodejs %}}
<div class="highlight"><pre class="chroma"><code class="language-typescript" data-lang="typescript"><span class="k">function </span>getTlsPlatformCertificateIds<span class="p">(</span><span class="nx">opts</span><span class="p">?:</span> <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/pulumi/#InvokeOptions">InvokeOptions</a></span><span class="p">): Promise&lt;<span class="nx"><a href="#result">GetTlsPlatformCertificateIdsResult</a></span>></span></code></pre></div>
{{% /choosable %}}


{{% choosable language python %}}
<div class="highlight"><pre class="chroma"><code class="language-python" data-lang="python"><span class="k">def </span>get_tls_platform_certificate_ids(</span><span class="nx">opts</span><span class="p">:</span> <span class="nx"><a href="/docs/reference/pkg/python/pulumi/#pulumi.InvokeOptions">Optional[InvokeOptions]</a></span> = None<span class="p">) -&gt;</span> GetTlsPlatformCertificateIdsResult</code></pre></div>
{{% /choosable %}}


{{% choosable language go %}}
<div class="highlight"><pre class="chroma"><code class="language-go" data-lang="go"><span class="k">func </span>GetTlsPlatformCertificateIds<span class="p">(</span><span class="nx">ctx</span><span class="p"> *</span><span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/v3/go/pulumi?tab=doc#Context">Context</a></span><span class="p">,</span> <span class="nx">opts</span><span class="p"> ...</span><span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/v3/go/pulumi?tab=doc#InvokeOption">InvokeOption</a></span><span class="p">) (*<span class="nx"><a href="#result">GetTlsPlatformCertificateIdsResult</a></span>, error)</span></code></pre></div>

> Note: This function is named `GetTlsPlatformCertificateIds` in the Go SDK.

{{% /choosable %}}


{{% choosable language csharp %}}
<div class="highlight"><pre class="chroma"><code class="language-csharp" data-lang="csharp"><span class="k">public static class </span><span class="nx">GetTlsPlatformCertificateIds </span><span class="p">{</span><span class="k">
    public static </span>Task&lt;<span class="nx"><a href="#result">GetTlsPlatformCertificateIdsResult</a></span>> <span class="p">InvokeAsync(</span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi/Pulumi.InvokeOptions.html">InvokeOptions</a></span><span class="p">? </span><span class="nx">opts = null<span class="p">)</span><span class="p">
}</span></code></pre></div>
{{% /choosable %}}




## getTlsPlatformCertificateIds Result {#result}

The following output properties are available:



{{% choosable language csharp %}}
<dl class="resources-properties"><dt class="property-"
            title="">
        <span id="id_csharp">
<a href="#id_csharp" style="color: inherit; text-decoration: inherit;">Id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The provider-assigned unique ID for this managed resource.
{{% /md %}}</dd><dt class="property-"
            title="">
        <span id="ids_csharp">
<a href="#ids_csharp" style="color: inherit; text-decoration: inherit;">Ids</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">List&lt;string&gt;</span>
    </dt>
    <dd>{{% md %}}List of IDs corresponding to Platform TLS certificates.
{{% /md %}}</dd></dl>
{{% /choosable %}}

{{% choosable language go %}}
<dl class="resources-properties"><dt class="property-"
            title="">
        <span id="id_go">
<a href="#id_go" style="color: inherit; text-decoration: inherit;">Id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The provider-assigned unique ID for this managed resource.
{{% /md %}}</dd><dt class="property-"
            title="">
        <span id="ids_go">
<a href="#ids_go" style="color: inherit; text-decoration: inherit;">Ids</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">[]string</span>
    </dt>
    <dd>{{% md %}}List of IDs corresponding to Platform TLS certificates.
{{% /md %}}</dd></dl>
{{% /choosable %}}

{{% choosable language nodejs %}}
<dl class="resources-properties"><dt class="property-"
            title="">
        <span id="id_nodejs">
<a href="#id_nodejs" style="color: inherit; text-decoration: inherit;">id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The provider-assigned unique ID for this managed resource.
{{% /md %}}</dd><dt class="property-"
            title="">
        <span id="ids_nodejs">
<a href="#ids_nodejs" style="color: inherit; text-decoration: inherit;">ids</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string[]</span>
    </dt>
    <dd>{{% md %}}List of IDs corresponding to Platform TLS certificates.
{{% /md %}}</dd></dl>
{{% /choosable %}}

{{% choosable language python %}}
<dl class="resources-properties"><dt class="property-"
            title="">
        <span id="id_python">
<a href="#id_python" style="color: inherit; text-decoration: inherit;">id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The provider-assigned unique ID for this managed resource.
{{% /md %}}</dd><dt class="property-"
            title="">
        <span id="ids_python">
<a href="#ids_python" style="color: inherit; text-decoration: inherit;">ids</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">Sequence[str]</span>
    </dt>
    <dd>{{% md %}}List of IDs corresponding to Platform TLS certificates.
{{% /md %}}</dd></dl>
{{% /choosable %}}





<h2 id="package-details">Package Details</h2>
<dl class="package-details">
	<dt>Repository</dt>
	<dd><a href="https://github.com/pulumi/pulumi-fastly">https://github.com/pulumi/pulumi-fastly</a></dd>
	<dt>License</dt>
	<dd>Apache-2.0</dd>
	<dt>Notes</dt>
	<dd>{{% md %}}This Pulumi package is based on the [`fastly` Terraform Provider](https://github.com/fastly/terraform-provider-fastly).{{% /md %}}</dd>
</dl>

