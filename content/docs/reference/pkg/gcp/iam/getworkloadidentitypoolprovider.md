
---
title: "GetWorkloadIdentityPoolProvider"
title_tag: "Function GetWorkloadIdentityPoolProvider | Module iam | Package GCP"
meta_desc: "Explore the GetWorkloadIdentityPoolProvider function of the iam module, including examples, input properties, output properties, and supporting types. "
---



<!-- WARNING: this file was generated by Pulumi Docs Generator. -->
<!-- Do not edit by hand unless you're certain you know what you are doing! -->




## Using GetWorkloadIdentityPoolProvider {#using}

{{< chooser language "typescript,python,go,csharp" / >}}


{{% choosable language nodejs %}}
<div class="highlight"><pre class="chroma"><code class="language-typescript" data-lang="typescript"><span class="k">function </span>getWorkloadIdentityPoolProvider<span class="p">(</span><span class="nx">args</span><span class="p">:</span> <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/gcp/iam/#GetWorkloadIdentityPoolProviderArgs">GetWorkloadIdentityPoolProviderArgs</a></span><span class="p">, </span><span class="nx">opts</span><span class="p">?:</span> <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/pulumi/#InvokeOptions">InvokeOptions</a></span><span class="p">): Promise&lt;<span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/gcp/iam/#GetWorkloadIdentityPoolProviderResult">GetWorkloadIdentityPoolProviderResult</a></span>></span></code></pre></div>
{{% /choosable %}}


{{% choosable language python %}}
<div class="highlight"><pre class="chroma"><code class="language-python" data-lang="python"><span class="k">def </span>get_workload_identity_pool_provider(</span><span class="nx">project</span><span class="p">:</span> <span class="nx">Optional[str]</span> = None<span class="p">, </span><span class="nx">workload_identity_pool_id</span><span class="p">:</span> <span class="nx">Optional[str]</span> = None<span class="p">, </span><span class="nx">workload_identity_pool_provider_id</span><span class="p">:</span> <span class="nx">Optional[str]</span> = None<span class="p">, </span><span class="nx">opts</span><span class="p">:</span> <span class="nx"><a href="/docs/reference/pkg/python/pulumi/#pulumi.InvokeOptions">Optional[InvokeOptions]</a></span> = None<span class="p">) -&gt;</span> GetWorkloadIdentityPoolProviderResult</code></pre></div>
{{% /choosable %}}


{{% choosable language go %}}
<div class="highlight"><pre class="chroma"><code class="language-go" data-lang="go"><span class="k">func </span>LookupWorkloadIdentityPoolProvider<span class="p">(</span><span class="nx">ctx</span><span class="p"> *</span><span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/v2/go/pulumi?tab=doc#Context">Context</a></span><span class="p">, </span><span class="nx">args</span><span class="p"> *</span><span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-gcp/sdk/v4/go/gcp/iam?tab=doc#LookupWorkloadIdentityPoolProviderArgs">LookupWorkloadIdentityPoolProviderArgs</a></span><span class="p">, </span><span class="nx">opts</span><span class="p"> ...</span><span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/v2/go/pulumi?tab=doc#InvokeOption">InvokeOption</a></span><span class="p">) (*<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-gcp/sdk/v4/go/gcp/iam?tab=doc#LookupWorkloadIdentityPoolProviderResult">LookupWorkloadIdentityPoolProviderResult</a></span>, error)</span></code></pre></div>

> Note: This function is named `LookupWorkloadIdentityPoolProvider` in the Go SDK.

{{% /choosable %}}


{{% choosable language csharp %}}
<div class="highlight"><pre class="chroma"><code class="language-csharp" data-lang="csharp"><span class="k">public static class </span><span class="nx">GetWorkloadIdentityPoolProvider </span><span class="p">{</span><span class="k">
    public static </span>Task&lt;<span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Gcp/Pulumi.Gcp.Iam.GetWorkloadIdentityPoolProviderResult.html">GetWorkloadIdentityPoolProviderResult</a></span>> <span class="p">InvokeAsync(</span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Gcp/Pulumi.Gcp.Iam.GetWorkloadIdentityPoolProviderArgs.html">GetWorkloadIdentityPoolProviderArgs</a></span><span class="p"> </span><span class="nx">args<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi/Pulumi.InvokeOptions.html">InvokeOptions</a></span><span class="p">? </span><span class="nx">opts = null<span class="p">)</span><span class="p">
}</span></code></pre></div>
{{% /choosable %}}



The following arguments are supported:


{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="workloadidentitypoolid_csharp">
<a href="#workloadidentitypoolid_csharp" style="color: inherit; text-decoration: inherit;">Workload<wbr>Identity<wbr>Pool<wbr>Id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The id of the pool which is the
final component of the pool resource name.
{{% /md %}}</dd>
    <dt class="property-required"
            title="Required">
        <span id="workloadidentitypoolproviderid_csharp">
<a href="#workloadidentitypoolproviderid_csharp" style="color: inherit; text-decoration: inherit;">Workload<wbr>Identity<wbr>Pool<wbr>Provider<wbr>Id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The id of the provider which is the
final component of the resource name.
{{% /md %}}</dd>
    <dt class="property-optional"
            title="Optional">
        <span id="project_csharp">
<a href="#project_csharp" style="color: inherit; text-decoration: inherit;">Project</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The project in which the resource belongs. If it
is not provided, the provider project is used.
{{% /md %}}</dd>
</dl>
{{% /choosable %}}

{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="workloadidentitypoolid_go">
<a href="#workloadidentitypoolid_go" style="color: inherit; text-decoration: inherit;">Workload<wbr>Identity<wbr>Pool<wbr>Id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The id of the pool which is the
final component of the pool resource name.
{{% /md %}}</dd>
    <dt class="property-required"
            title="Required">
        <span id="workloadidentitypoolproviderid_go">
<a href="#workloadidentitypoolproviderid_go" style="color: inherit; text-decoration: inherit;">Workload<wbr>Identity<wbr>Pool<wbr>Provider<wbr>Id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The id of the provider which is the
final component of the resource name.
{{% /md %}}</dd>
    <dt class="property-optional"
            title="Optional">
        <span id="project_go">
<a href="#project_go" style="color: inherit; text-decoration: inherit;">Project</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The project in which the resource belongs. If it
is not provided, the provider project is used.
{{% /md %}}</dd>
</dl>
{{% /choosable %}}

{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="workloadidentitypoolid_nodejs">
<a href="#workloadidentitypoolid_nodejs" style="color: inherit; text-decoration: inherit;">workload<wbr>Identity<wbr>Pool<wbr>Id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The id of the pool which is the
final component of the pool resource name.
{{% /md %}}</dd>
    <dt class="property-required"
            title="Required">
        <span id="workloadidentitypoolproviderid_nodejs">
<a href="#workloadidentitypoolproviderid_nodejs" style="color: inherit; text-decoration: inherit;">workload<wbr>Identity<wbr>Pool<wbr>Provider<wbr>Id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The id of the provider which is the
final component of the resource name.
{{% /md %}}</dd>
    <dt class="property-optional"
            title="Optional">
        <span id="project_nodejs">
<a href="#project_nodejs" style="color: inherit; text-decoration: inherit;">project</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The project in which the resource belongs. If it
is not provided, the provider project is used.
{{% /md %}}</dd>
</dl>
{{% /choosable %}}

{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="workload_identity_pool_id_python">
<a href="#workload_identity_pool_id_python" style="color: inherit; text-decoration: inherit;">workload_<wbr>identity_<wbr>pool_<wbr>id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The id of the pool which is the
final component of the pool resource name.
{{% /md %}}</dd>
    <dt class="property-required"
            title="Required">
        <span id="workload_identity_pool_provider_id_python">
<a href="#workload_identity_pool_provider_id_python" style="color: inherit; text-decoration: inherit;">workload_<wbr>identity_<wbr>pool_<wbr>provider_<wbr>id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The id of the provider which is the
final component of the resource name.
{{% /md %}}</dd>
    <dt class="property-optional"
            title="Optional">
        <span id="project_python">
<a href="#project_python" style="color: inherit; text-decoration: inherit;">project</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The project in which the resource belongs. If it
is not provided, the provider project is used.
{{% /md %}}</dd>
</dl>
{{% /choosable %}}




## GetWorkloadIdentityPoolProvider Result {#result}

The following output properties are available:



{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span id="attributecondition_csharp">
<a href="#attributecondition_csharp" style="color: inherit; text-decoration: inherit;">Attribute<wbr>Condition</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="attributemapping_csharp">
<a href="#attributemapping_csharp" style="color: inherit; text-decoration: inherit;">Attribute<wbr>Mapping</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">Dictionary&lt;string, string&gt;</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="aws_csharp">
<a href="#aws_csharp" style="color: inherit; text-decoration: inherit;">Aws</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#getworkloadidentitypoolprovideraw">List&lt;Get<wbr>Workload<wbr>Identity<wbr>Pool<wbr>Provider<wbr>Aw&gt;</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="description_csharp">
<a href="#description_csharp" style="color: inherit; text-decoration: inherit;">Description</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="disabled_csharp">
<a href="#disabled_csharp" style="color: inherit; text-decoration: inherit;">Disabled</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="displayname_csharp">
<a href="#displayname_csharp" style="color: inherit; text-decoration: inherit;">Display<wbr>Name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="id_csharp">
<a href="#id_csharp" style="color: inherit; text-decoration: inherit;">Id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The provider-assigned unique ID for this managed resource.
{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="name_csharp">
<a href="#name_csharp" style="color: inherit; text-decoration: inherit;">Name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="oidcs_csharp">
<a href="#oidcs_csharp" style="color: inherit; text-decoration: inherit;">Oidcs</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#getworkloadidentitypoolprovideroidc">List&lt;Get<wbr>Workload<wbr>Identity<wbr>Pool<wbr>Provider<wbr>Oidc&gt;</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="state_csharp">
<a href="#state_csharp" style="color: inherit; text-decoration: inherit;">State</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="workloadidentitypoolid_csharp">
<a href="#workloadidentitypoolid_csharp" style="color: inherit; text-decoration: inherit;">Workload<wbr>Identity<wbr>Pool<wbr>Id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="workloadidentitypoolproviderid_csharp">
<a href="#workloadidentitypoolproviderid_csharp" style="color: inherit; text-decoration: inherit;">Workload<wbr>Identity<wbr>Pool<wbr>Provider<wbr>Id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="project_csharp">
<a href="#project_csharp" style="color: inherit; text-decoration: inherit;">Project</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>
</dl>
{{% /choosable %}}

{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span id="attributecondition_go">
<a href="#attributecondition_go" style="color: inherit; text-decoration: inherit;">Attribute<wbr>Condition</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="attributemapping_go">
<a href="#attributemapping_go" style="color: inherit; text-decoration: inherit;">Attribute<wbr>Mapping</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">map[string]string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="aws_go">
<a href="#aws_go" style="color: inherit; text-decoration: inherit;">Aws</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#getworkloadidentitypoolprovideraw">[]Get<wbr>Workload<wbr>Identity<wbr>Pool<wbr>Provider<wbr>Aw</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="description_go">
<a href="#description_go" style="color: inherit; text-decoration: inherit;">Description</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="disabled_go">
<a href="#disabled_go" style="color: inherit; text-decoration: inherit;">Disabled</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="displayname_go">
<a href="#displayname_go" style="color: inherit; text-decoration: inherit;">Display<wbr>Name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="id_go">
<a href="#id_go" style="color: inherit; text-decoration: inherit;">Id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The provider-assigned unique ID for this managed resource.
{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="name_go">
<a href="#name_go" style="color: inherit; text-decoration: inherit;">Name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="oidcs_go">
<a href="#oidcs_go" style="color: inherit; text-decoration: inherit;">Oidcs</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#getworkloadidentitypoolprovideroidc">[]Get<wbr>Workload<wbr>Identity<wbr>Pool<wbr>Provider<wbr>Oidc</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="state_go">
<a href="#state_go" style="color: inherit; text-decoration: inherit;">State</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="workloadidentitypoolid_go">
<a href="#workloadidentitypoolid_go" style="color: inherit; text-decoration: inherit;">Workload<wbr>Identity<wbr>Pool<wbr>Id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="workloadidentitypoolproviderid_go">
<a href="#workloadidentitypoolproviderid_go" style="color: inherit; text-decoration: inherit;">Workload<wbr>Identity<wbr>Pool<wbr>Provider<wbr>Id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="project_go">
<a href="#project_go" style="color: inherit; text-decoration: inherit;">Project</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>
</dl>
{{% /choosable %}}

{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span id="attributecondition_nodejs">
<a href="#attributecondition_nodejs" style="color: inherit; text-decoration: inherit;">attribute<wbr>Condition</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="attributemapping_nodejs">
<a href="#attributemapping_nodejs" style="color: inherit; text-decoration: inherit;">attribute<wbr>Mapping</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">{[key: string]: string}</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="aws_nodejs">
<a href="#aws_nodejs" style="color: inherit; text-decoration: inherit;">aws</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#getworkloadidentitypoolprovideraw">Get<wbr>Workload<wbr>Identity<wbr>Pool<wbr>Provider<wbr>Aw[]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="description_nodejs">
<a href="#description_nodejs" style="color: inherit; text-decoration: inherit;">description</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="disabled_nodejs">
<a href="#disabled_nodejs" style="color: inherit; text-decoration: inherit;">disabled</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="displayname_nodejs">
<a href="#displayname_nodejs" style="color: inherit; text-decoration: inherit;">display<wbr>Name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="id_nodejs">
<a href="#id_nodejs" style="color: inherit; text-decoration: inherit;">id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The provider-assigned unique ID for this managed resource.
{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="name_nodejs">
<a href="#name_nodejs" style="color: inherit; text-decoration: inherit;">name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="oidcs_nodejs">
<a href="#oidcs_nodejs" style="color: inherit; text-decoration: inherit;">oidcs</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#getworkloadidentitypoolprovideroidc">Get<wbr>Workload<wbr>Identity<wbr>Pool<wbr>Provider<wbr>Oidc[]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="state_nodejs">
<a href="#state_nodejs" style="color: inherit; text-decoration: inherit;">state</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="workloadidentitypoolid_nodejs">
<a href="#workloadidentitypoolid_nodejs" style="color: inherit; text-decoration: inherit;">workload<wbr>Identity<wbr>Pool<wbr>Id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="workloadidentitypoolproviderid_nodejs">
<a href="#workloadidentitypoolproviderid_nodejs" style="color: inherit; text-decoration: inherit;">workload<wbr>Identity<wbr>Pool<wbr>Provider<wbr>Id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="project_nodejs">
<a href="#project_nodejs" style="color: inherit; text-decoration: inherit;">project</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>
</dl>
{{% /choosable %}}

{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span id="attribute_condition_python">
<a href="#attribute_condition_python" style="color: inherit; text-decoration: inherit;">attribute_<wbr>condition</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="attribute_mapping_python">
<a href="#attribute_mapping_python" style="color: inherit; text-decoration: inherit;">attribute_<wbr>mapping</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">Mapping[str, str]</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="aws_python">
<a href="#aws_python" style="color: inherit; text-decoration: inherit;">aws</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#getworkloadidentitypoolprovideraw">Sequence[Get<wbr>Workload<wbr>Identity<wbr>Pool<wbr>Provider<wbr>Aw]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="description_python">
<a href="#description_python" style="color: inherit; text-decoration: inherit;">description</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="disabled_python">
<a href="#disabled_python" style="color: inherit; text-decoration: inherit;">disabled</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="display_name_python">
<a href="#display_name_python" style="color: inherit; text-decoration: inherit;">display_<wbr>name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="id_python">
<a href="#id_python" style="color: inherit; text-decoration: inherit;">id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The provider-assigned unique ID for this managed resource.
{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="name_python">
<a href="#name_python" style="color: inherit; text-decoration: inherit;">name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="oidcs_python">
<a href="#oidcs_python" style="color: inherit; text-decoration: inherit;">oidcs</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#getworkloadidentitypoolprovideroidc">Sequence[Get<wbr>Workload<wbr>Identity<wbr>Pool<wbr>Provider<wbr>Oidc]</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="state_python">
<a href="#state_python" style="color: inherit; text-decoration: inherit;">state</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="workload_identity_pool_id_python">
<a href="#workload_identity_pool_id_python" style="color: inherit; text-decoration: inherit;">workload_<wbr>identity_<wbr>pool_<wbr>id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="workload_identity_pool_provider_id_python">
<a href="#workload_identity_pool_provider_id_python" style="color: inherit; text-decoration: inherit;">workload_<wbr>identity_<wbr>pool_<wbr>provider_<wbr>id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="project_python">
<a href="#project_python" style="color: inherit; text-decoration: inherit;">project</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>
</dl>
{{% /choosable %}}




## Supporting Types


<h4 id="getworkloadidentitypoolprovideraw">Get<wbr>Workload<wbr>Identity<wbr>Pool<wbr>Provider<wbr>Aw</h4>
{{% choosable language nodejs %}}
> See the   <a href="/docs/reference/pkg/nodejs/pulumi/gcp/types/output/#GetWorkloadIdentityPoolProviderAw">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the   <a href="https://pkg.go.dev/github.com/pulumi/pulumi-gcp/sdk/v4/go/gcp/iam?tab=doc#GetWorkloadIdentityPoolProviderAw">output</a> API doc for this type.
{{% /choosable %}}
{{% choosable language csharp %}}
> See the   <a href="/docs/reference/pkg/dotnet/Pulumi.Gcp/Pulumi.Gcp.Iam.Outputs.GetWorkloadIdentityPoolProviderAw.html">output</a> API doc for this type.
{{% /choosable %}}



{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="accountid_csharp">
<a href="#accountid_csharp" style="color: inherit; text-decoration: inherit;">Account<wbr>Id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>
</dl>
{{% /choosable %}}

{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="accountid_go">
<a href="#accountid_go" style="color: inherit; text-decoration: inherit;">Account<wbr>Id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>
</dl>
{{% /choosable %}}

{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="accountid_nodejs">
<a href="#accountid_nodejs" style="color: inherit; text-decoration: inherit;">account<wbr>Id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>
</dl>
{{% /choosable %}}

{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="account_id_python">
<a href="#account_id_python" style="color: inherit; text-decoration: inherit;">account_<wbr>id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>
</dl>
{{% /choosable %}}

<h4 id="getworkloadidentitypoolprovideroidc">Get<wbr>Workload<wbr>Identity<wbr>Pool<wbr>Provider<wbr>Oidc</h4>
{{% choosable language nodejs %}}
> See the   <a href="/docs/reference/pkg/nodejs/pulumi/gcp/types/output/#GetWorkloadIdentityPoolProviderOidc">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the   <a href="https://pkg.go.dev/github.com/pulumi/pulumi-gcp/sdk/v4/go/gcp/iam?tab=doc#GetWorkloadIdentityPoolProviderOidc">output</a> API doc for this type.
{{% /choosable %}}
{{% choosable language csharp %}}
> See the   <a href="/docs/reference/pkg/dotnet/Pulumi.Gcp/Pulumi.Gcp.Iam.Outputs.GetWorkloadIdentityPoolProviderOidc.html">output</a> API doc for this type.
{{% /choosable %}}



{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="allowedaudiences_csharp">
<a href="#allowedaudiences_csharp" style="color: inherit; text-decoration: inherit;">Allowed<wbr>Audiences</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">List&lt;string&gt;</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>
    <dt class="property-required"
            title="Required">
        <span id="issueruri_csharp">
<a href="#issueruri_csharp" style="color: inherit; text-decoration: inherit;">Issuer<wbr>Uri</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>
</dl>
{{% /choosable %}}

{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="allowedaudiences_go">
<a href="#allowedaudiences_go" style="color: inherit; text-decoration: inherit;">Allowed<wbr>Audiences</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">[]string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>
    <dt class="property-required"
            title="Required">
        <span id="issueruri_go">
<a href="#issueruri_go" style="color: inherit; text-decoration: inherit;">Issuer<wbr>Uri</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>
</dl>
{{% /choosable %}}

{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="allowedaudiences_nodejs">
<a href="#allowedaudiences_nodejs" style="color: inherit; text-decoration: inherit;">allowed<wbr>Audiences</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string[]</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>
    <dt class="property-required"
            title="Required">
        <span id="issueruri_nodejs">
<a href="#issueruri_nodejs" style="color: inherit; text-decoration: inherit;">issuer<wbr>Uri</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>
</dl>
{{% /choosable %}}

{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="allowed_audiences_python">
<a href="#allowed_audiences_python" style="color: inherit; text-decoration: inherit;">allowed_<wbr>audiences</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">Sequence[str]</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>
    <dt class="property-required"
            title="Required">
        <span id="issuer_uri_python">
<a href="#issuer_uri_python" style="color: inherit; text-decoration: inherit;">issuer_<wbr>uri</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>
</dl>
{{% /choosable %}}





<h2 id="package-details">Package Details</h2>
<dl class="package-details">
	<dt>Repository</dt>
	<dd><a href="https://github.com/pulumi/pulumi-gcp">https://github.com/pulumi/pulumi-gcp</a></dd>
	<dt>License</dt>
	<dd>Apache-2.0</dd>
	<dt>Notes</dt>
	<dd>This Pulumi package is based on the [`google-beta` Terraform Provider](https://github.com/hashicorp/terraform-provider-google-beta).</dd>
</dl>
