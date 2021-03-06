
---
title: "getDeveloper"
title_tag: "google-native.apigee/v1.getDeveloper"
meta_desc: "Documentation for the google-native.apigee/v1.getDeveloper function with examples, input properties, output properties, and supporting types."
---



<!-- WARNING: this file was generated by Pulumi Docs Generator. -->
<!-- Do not edit by hand unless you're certain you know what you are doing! -->

Returns the developer details, including the developer's name, email address, apps, and other information. **Note**: The response includes only the first 100 developer apps.




## Using getDeveloper {#using}

{{< chooser language "typescript,python,go,csharp" / >}}


{{% choosable language nodejs %}}
<div class="highlight"><pre class="chroma"><code class="language-typescript" data-lang="typescript"><span class="k">function </span>getDeveloper<span class="p">(</span><span class="nx">args</span><span class="p">:</span> <span class="nx">GetDeveloperArgs</span><span class="p">,</span> <span class="nx">opts</span><span class="p">?:</span> <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/pulumi/#InvokeOptions">InvokeOptions</a></span><span class="p">): Promise&lt;<span class="nx"><a href="#result">GetDeveloperResult</a></span>></span></code></pre></div>
{{% /choosable %}}


{{% choosable language python %}}
<div class="highlight"><pre class="chroma"><code class="language-python" data-lang="python"><span class="k">def </span>get_developer(</span><span class="nx">action</span><span class="p">:</span> <span class="nx">Optional[str]</span> = None<span class="p">,</span>
                  <span class="nx">developer_id</span><span class="p">:</span> <span class="nx">Optional[str]</span> = None<span class="p">,</span>
                  <span class="nx">organization_id</span><span class="p">:</span> <span class="nx">Optional[str]</span> = None<span class="p">,</span>
                  <span class="nx">opts</span><span class="p">:</span> <span class="nx"><a href="/docs/reference/pkg/python/pulumi/#pulumi.InvokeOptions">Optional[InvokeOptions]</a></span> = None<span class="p">) -&gt;</span> GetDeveloperResult</code></pre></div>
{{% /choosable %}}


{{% choosable language go %}}
<div class="highlight"><pre class="chroma"><code class="language-go" data-lang="go"><span class="k">func </span>LookupDeveloper<span class="p">(</span><span class="nx">ctx</span><span class="p"> *</span><span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/v3/go/pulumi?tab=doc#Context">Context</a></span><span class="p">,</span> <span class="nx">args</span><span class="p"> *</span><span class="nx">LookupDeveloperArgs</span><span class="p">,</span> <span class="nx">opts</span><span class="p"> ...</span><span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/v3/go/pulumi?tab=doc#InvokeOption">InvokeOption</a></span><span class="p">) (*<span class="nx"><a href="#result">LookupDeveloperResult</a></span>, error)</span></code></pre></div>

> Note: This function is named `LookupDeveloper` in the Go SDK.

{{% /choosable %}}


{{% choosable language csharp %}}
<div class="highlight"><pre class="chroma"><code class="language-csharp" data-lang="csharp"><span class="k">public static class </span><span class="nx">GetDeveloper </span><span class="p">{</span><span class="k">
    public static </span>Task&lt;<span class="nx"><a href="#result">GetDeveloperResult</a></span>> <span class="p">InvokeAsync(</span><span class="nx">GetDeveloperArgs</span><span class="p"> </span><span class="nx">args<span class="p">,</span> <span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi/Pulumi.InvokeOptions.html">InvokeOptions</a></span><span class="p">? </span><span class="nx">opts = null<span class="p">)</span><span class="p">
}</span></code></pre></div>
{{% /choosable %}}



The following arguments are supported:


{{% choosable language csharp %}}
<dl class="resources-properties"><dt class="property-required"
            title="Required">
        <span id="developerid_csharp">
<a href="#developerid_csharp" style="color: inherit; text-decoration: inherit;">Developer<wbr>Id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd><dt class="property-required"
            title="Required">
        <span id="organizationid_csharp">
<a href="#organizationid_csharp" style="color: inherit; text-decoration: inherit;">Organization<wbr>Id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd><dt class="property-optional"
            title="Optional">
        <span id="action_csharp">
<a href="#action_csharp" style="color: inherit; text-decoration: inherit;">Action</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd></dl>
{{% /choosable %}}

{{% choosable language go %}}
<dl class="resources-properties"><dt class="property-required"
            title="Required">
        <span id="developerid_go">
<a href="#developerid_go" style="color: inherit; text-decoration: inherit;">Developer<wbr>Id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd><dt class="property-required"
            title="Required">
        <span id="organizationid_go">
<a href="#organizationid_go" style="color: inherit; text-decoration: inherit;">Organization<wbr>Id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd><dt class="property-optional"
            title="Optional">
        <span id="action_go">
<a href="#action_go" style="color: inherit; text-decoration: inherit;">Action</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd></dl>
{{% /choosable %}}

{{% choosable language nodejs %}}
<dl class="resources-properties"><dt class="property-required"
            title="Required">
        <span id="developerid_nodejs">
<a href="#developerid_nodejs" style="color: inherit; text-decoration: inherit;">developer<wbr>Id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd><dt class="property-required"
            title="Required">
        <span id="organizationid_nodejs">
<a href="#organizationid_nodejs" style="color: inherit; text-decoration: inherit;">organization<wbr>Id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd><dt class="property-optional"
            title="Optional">
        <span id="action_nodejs">
<a href="#action_nodejs" style="color: inherit; text-decoration: inherit;">action</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd></dl>
{{% /choosable %}}

{{% choosable language python %}}
<dl class="resources-properties"><dt class="property-required"
            title="Required">
        <span id="developer_id_python">
<a href="#developer_id_python" style="color: inherit; text-decoration: inherit;">developer_<wbr>id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd><dt class="property-required"
            title="Required">
        <span id="organization_id_python">
<a href="#organization_id_python" style="color: inherit; text-decoration: inherit;">organization_<wbr>id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd><dt class="property-optional"
            title="Optional">
        <span id="action_python">
<a href="#action_python" style="color: inherit; text-decoration: inherit;">action</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd></dl>
{{% /choosable %}}




## getDeveloper Result {#result}

The following output properties are available:



{{% choosable language csharp %}}
<dl class="resources-properties"><dt class="property-"
            title="">
        <span id="accesstype_csharp">
<a href="#accesstype_csharp" style="color: inherit; text-decoration: inherit;">Access<wbr>Type</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Access type.{{% /md %}}</dd><dt class="property-"
            title="">
        <span id="appfamily_csharp">
<a href="#appfamily_csharp" style="color: inherit; text-decoration: inherit;">App<wbr>Family</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Developer app family.{{% /md %}}</dd><dt class="property-"
            title="">
        <span id="apps_csharp">
<a href="#apps_csharp" style="color: inherit; text-decoration: inherit;">Apps</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">List&lt;string&gt;</span>
    </dt>
    <dd>{{% md %}}List of apps associated with the developer.{{% /md %}}</dd><dt class="property-"
            title="">
        <span id="attributes_csharp">
<a href="#attributes_csharp" style="color: inherit; text-decoration: inherit;">Attributes</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#googlecloudapigeev1attributeresponse">List&lt;Pulumi.<wbr>Google<wbr>Native.<wbr>Apigee.<wbr>V1.<wbr>Outputs.<wbr>Google<wbr>Cloud<wbr>Apigee<wbr>V1Attribute<wbr>Response&gt;</a></span>
    </dt>
    <dd>{{% md %}}Optional. Developer attributes (name/value pairs). The custom attribute limit is 18.{{% /md %}}</dd><dt class="property-"
            title="">
        <span id="companies_csharp">
<a href="#companies_csharp" style="color: inherit; text-decoration: inherit;">Companies</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">List&lt;string&gt;</span>
    </dt>
    <dd>{{% md %}}List of companies associated with the developer.{{% /md %}}</dd><dt class="property-"
            title="">
        <span id="createdat_csharp">
<a href="#createdat_csharp" style="color: inherit; text-decoration: inherit;">Created<wbr>At</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Time at which the developer was created in milliseconds since epoch.{{% /md %}}</dd><dt class="property-"
            title="">
        <span id="developerid_csharp">
<a href="#developerid_csharp" style="color: inherit; text-decoration: inherit;">Developer<wbr>Id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}ID of the developer. **Note**: IDs are generated internally by Apigee and are not guaranteed to stay the same over time.{{% /md %}}</dd><dt class="property-"
            title="">
        <span id="email_csharp">
<a href="#email_csharp" style="color: inherit; text-decoration: inherit;">Email</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Required. Email address of the developer. This value is used to uniquely identify the developer in Apigee hybrid. Note that the email address has to be in lowercase only.{{% /md %}}</dd><dt class="property-"
            title="">
        <span id="firstname_csharp">
<a href="#firstname_csharp" style="color: inherit; text-decoration: inherit;">First<wbr>Name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Required. First name of the developer.{{% /md %}}</dd><dt class="property-"
            title="">
        <span id="lastmodifiedat_csharp">
<a href="#lastmodifiedat_csharp" style="color: inherit; text-decoration: inherit;">Last<wbr>Modified<wbr>At</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Time at which the developer was last modified in milliseconds since epoch.{{% /md %}}</dd><dt class="property-"
            title="">
        <span id="lastname_csharp">
<a href="#lastname_csharp" style="color: inherit; text-decoration: inherit;">Last<wbr>Name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Required. Last name of the developer.{{% /md %}}</dd><dt class="property-"
            title="">
        <span id="organizationname_csharp">
<a href="#organizationname_csharp" style="color: inherit; text-decoration: inherit;">Organization<wbr>Name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Name of the Apigee organization in which the developer resides.{{% /md %}}</dd><dt class="property-"
            title="">
        <span id="status_csharp">
<a href="#status_csharp" style="color: inherit; text-decoration: inherit;">Status</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Status of the developer. Valid values are `active` and `inactive`.{{% /md %}}</dd><dt class="property-"
            title="">
        <span id="username_csharp">
<a href="#username_csharp" style="color: inherit; text-decoration: inherit;">User<wbr>Name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Required. User name of the developer. Not used by Apigee hybrid.{{% /md %}}</dd></dl>
{{% /choosable %}}

{{% choosable language go %}}
<dl class="resources-properties"><dt class="property-"
            title="">
        <span id="accesstype_go">
<a href="#accesstype_go" style="color: inherit; text-decoration: inherit;">Access<wbr>Type</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Access type.{{% /md %}}</dd><dt class="property-"
            title="">
        <span id="appfamily_go">
<a href="#appfamily_go" style="color: inherit; text-decoration: inherit;">App<wbr>Family</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Developer app family.{{% /md %}}</dd><dt class="property-"
            title="">
        <span id="apps_go">
<a href="#apps_go" style="color: inherit; text-decoration: inherit;">Apps</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">[]string</span>
    </dt>
    <dd>{{% md %}}List of apps associated with the developer.{{% /md %}}</dd><dt class="property-"
            title="">
        <span id="attributes_go">
<a href="#attributes_go" style="color: inherit; text-decoration: inherit;">Attributes</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#googlecloudapigeev1attributeresponse">[]Google<wbr>Cloud<wbr>Apigee<wbr>V1Attribute<wbr>Response</a></span>
    </dt>
    <dd>{{% md %}}Optional. Developer attributes (name/value pairs). The custom attribute limit is 18.{{% /md %}}</dd><dt class="property-"
            title="">
        <span id="companies_go">
<a href="#companies_go" style="color: inherit; text-decoration: inherit;">Companies</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">[]string</span>
    </dt>
    <dd>{{% md %}}List of companies associated with the developer.{{% /md %}}</dd><dt class="property-"
            title="">
        <span id="createdat_go">
<a href="#createdat_go" style="color: inherit; text-decoration: inherit;">Created<wbr>At</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Time at which the developer was created in milliseconds since epoch.{{% /md %}}</dd><dt class="property-"
            title="">
        <span id="developerid_go">
<a href="#developerid_go" style="color: inherit; text-decoration: inherit;">Developer<wbr>Id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}ID of the developer. **Note**: IDs are generated internally by Apigee and are not guaranteed to stay the same over time.{{% /md %}}</dd><dt class="property-"
            title="">
        <span id="email_go">
<a href="#email_go" style="color: inherit; text-decoration: inherit;">Email</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Required. Email address of the developer. This value is used to uniquely identify the developer in Apigee hybrid. Note that the email address has to be in lowercase only.{{% /md %}}</dd><dt class="property-"
            title="">
        <span id="firstname_go">
<a href="#firstname_go" style="color: inherit; text-decoration: inherit;">First<wbr>Name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Required. First name of the developer.{{% /md %}}</dd><dt class="property-"
            title="">
        <span id="lastmodifiedat_go">
<a href="#lastmodifiedat_go" style="color: inherit; text-decoration: inherit;">Last<wbr>Modified<wbr>At</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Time at which the developer was last modified in milliseconds since epoch.{{% /md %}}</dd><dt class="property-"
            title="">
        <span id="lastname_go">
<a href="#lastname_go" style="color: inherit; text-decoration: inherit;">Last<wbr>Name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Required. Last name of the developer.{{% /md %}}</dd><dt class="property-"
            title="">
        <span id="organizationname_go">
<a href="#organizationname_go" style="color: inherit; text-decoration: inherit;">Organization<wbr>Name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Name of the Apigee organization in which the developer resides.{{% /md %}}</dd><dt class="property-"
            title="">
        <span id="status_go">
<a href="#status_go" style="color: inherit; text-decoration: inherit;">Status</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Status of the developer. Valid values are `active` and `inactive`.{{% /md %}}</dd><dt class="property-"
            title="">
        <span id="username_go">
<a href="#username_go" style="color: inherit; text-decoration: inherit;">User<wbr>Name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Required. User name of the developer. Not used by Apigee hybrid.{{% /md %}}</dd></dl>
{{% /choosable %}}

{{% choosable language nodejs %}}
<dl class="resources-properties"><dt class="property-"
            title="">
        <span id="accesstype_nodejs">
<a href="#accesstype_nodejs" style="color: inherit; text-decoration: inherit;">access<wbr>Type</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Access type.{{% /md %}}</dd><dt class="property-"
            title="">
        <span id="appfamily_nodejs">
<a href="#appfamily_nodejs" style="color: inherit; text-decoration: inherit;">app<wbr>Family</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Developer app family.{{% /md %}}</dd><dt class="property-"
            title="">
        <span id="apps_nodejs">
<a href="#apps_nodejs" style="color: inherit; text-decoration: inherit;">apps</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string[]</span>
    </dt>
    <dd>{{% md %}}List of apps associated with the developer.{{% /md %}}</dd><dt class="property-"
            title="">
        <span id="attributes_nodejs">
<a href="#attributes_nodejs" style="color: inherit; text-decoration: inherit;">attributes</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#googlecloudapigeev1attributeresponse">Google<wbr>Cloud<wbr>Apigee<wbr>V1Attribute<wbr>Response[]</a></span>
    </dt>
    <dd>{{% md %}}Optional. Developer attributes (name/value pairs). The custom attribute limit is 18.{{% /md %}}</dd><dt class="property-"
            title="">
        <span id="companies_nodejs">
<a href="#companies_nodejs" style="color: inherit; text-decoration: inherit;">companies</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string[]</span>
    </dt>
    <dd>{{% md %}}List of companies associated with the developer.{{% /md %}}</dd><dt class="property-"
            title="">
        <span id="createdat_nodejs">
<a href="#createdat_nodejs" style="color: inherit; text-decoration: inherit;">created<wbr>At</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Time at which the developer was created in milliseconds since epoch.{{% /md %}}</dd><dt class="property-"
            title="">
        <span id="developerid_nodejs">
<a href="#developerid_nodejs" style="color: inherit; text-decoration: inherit;">developer<wbr>Id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}ID of the developer. **Note**: IDs are generated internally by Apigee and are not guaranteed to stay the same over time.{{% /md %}}</dd><dt class="property-"
            title="">
        <span id="email_nodejs">
<a href="#email_nodejs" style="color: inherit; text-decoration: inherit;">email</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Required. Email address of the developer. This value is used to uniquely identify the developer in Apigee hybrid. Note that the email address has to be in lowercase only.{{% /md %}}</dd><dt class="property-"
            title="">
        <span id="firstname_nodejs">
<a href="#firstname_nodejs" style="color: inherit; text-decoration: inherit;">first<wbr>Name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Required. First name of the developer.{{% /md %}}</dd><dt class="property-"
            title="">
        <span id="lastmodifiedat_nodejs">
<a href="#lastmodifiedat_nodejs" style="color: inherit; text-decoration: inherit;">last<wbr>Modified<wbr>At</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Time at which the developer was last modified in milliseconds since epoch.{{% /md %}}</dd><dt class="property-"
            title="">
        <span id="lastname_nodejs">
<a href="#lastname_nodejs" style="color: inherit; text-decoration: inherit;">last<wbr>Name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Required. Last name of the developer.{{% /md %}}</dd><dt class="property-"
            title="">
        <span id="organizationname_nodejs">
<a href="#organizationname_nodejs" style="color: inherit; text-decoration: inherit;">organization<wbr>Name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Name of the Apigee organization in which the developer resides.{{% /md %}}</dd><dt class="property-"
            title="">
        <span id="status_nodejs">
<a href="#status_nodejs" style="color: inherit; text-decoration: inherit;">status</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Status of the developer. Valid values are `active` and `inactive`.{{% /md %}}</dd><dt class="property-"
            title="">
        <span id="username_nodejs">
<a href="#username_nodejs" style="color: inherit; text-decoration: inherit;">user<wbr>Name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Required. User name of the developer. Not used by Apigee hybrid.{{% /md %}}</dd></dl>
{{% /choosable %}}

{{% choosable language python %}}
<dl class="resources-properties"><dt class="property-"
            title="">
        <span id="access_type_python">
<a href="#access_type_python" style="color: inherit; text-decoration: inherit;">access_<wbr>type</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Access type.{{% /md %}}</dd><dt class="property-"
            title="">
        <span id="app_family_python">
<a href="#app_family_python" style="color: inherit; text-decoration: inherit;">app_<wbr>family</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Developer app family.{{% /md %}}</dd><dt class="property-"
            title="">
        <span id="apps_python">
<a href="#apps_python" style="color: inherit; text-decoration: inherit;">apps</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">Sequence[str]</span>
    </dt>
    <dd>{{% md %}}List of apps associated with the developer.{{% /md %}}</dd><dt class="property-"
            title="">
        <span id="attributes_python">
<a href="#attributes_python" style="color: inherit; text-decoration: inherit;">attributes</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#googlecloudapigeev1attributeresponse">Google<wbr>Cloud<wbr>Apigee<wbr>V1Attribute<wbr>Response]</a></span>
    </dt>
    <dd>{{% md %}}Optional. Developer attributes (name/value pairs). The custom attribute limit is 18.{{% /md %}}</dd><dt class="property-"
            title="">
        <span id="companies_python">
<a href="#companies_python" style="color: inherit; text-decoration: inherit;">companies</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">Sequence[str]</span>
    </dt>
    <dd>{{% md %}}List of companies associated with the developer.{{% /md %}}</dd><dt class="property-"
            title="">
        <span id="created_at_python">
<a href="#created_at_python" style="color: inherit; text-decoration: inherit;">created_<wbr>at</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Time at which the developer was created in milliseconds since epoch.{{% /md %}}</dd><dt class="property-"
            title="">
        <span id="developer_id_python">
<a href="#developer_id_python" style="color: inherit; text-decoration: inherit;">developer_<wbr>id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}ID of the developer. **Note**: IDs are generated internally by Apigee and are not guaranteed to stay the same over time.{{% /md %}}</dd><dt class="property-"
            title="">
        <span id="email_python">
<a href="#email_python" style="color: inherit; text-decoration: inherit;">email</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Required. Email address of the developer. This value is used to uniquely identify the developer in Apigee hybrid. Note that the email address has to be in lowercase only.{{% /md %}}</dd><dt class="property-"
            title="">
        <span id="first_name_python">
<a href="#first_name_python" style="color: inherit; text-decoration: inherit;">first_<wbr>name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Required. First name of the developer.{{% /md %}}</dd><dt class="property-"
            title="">
        <span id="last_modified_at_python">
<a href="#last_modified_at_python" style="color: inherit; text-decoration: inherit;">last_<wbr>modified_<wbr>at</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Time at which the developer was last modified in milliseconds since epoch.{{% /md %}}</dd><dt class="property-"
            title="">
        <span id="last_name_python">
<a href="#last_name_python" style="color: inherit; text-decoration: inherit;">last_<wbr>name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Required. Last name of the developer.{{% /md %}}</dd><dt class="property-"
            title="">
        <span id="organization_name_python">
<a href="#organization_name_python" style="color: inherit; text-decoration: inherit;">organization_<wbr>name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Name of the Apigee organization in which the developer resides.{{% /md %}}</dd><dt class="property-"
            title="">
        <span id="status_python">
<a href="#status_python" style="color: inherit; text-decoration: inherit;">status</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Status of the developer. Valid values are `active` and `inactive`.{{% /md %}}</dd><dt class="property-"
            title="">
        <span id="user_name_python">
<a href="#user_name_python" style="color: inherit; text-decoration: inherit;">user_<wbr>name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Required. User name of the developer. Not used by Apigee hybrid.{{% /md %}}</dd></dl>
{{% /choosable %}}




## Supporting Types


<h4 id="googlecloudapigeev1attributeresponse">Google<wbr>Cloud<wbr>Apigee<wbr>V1Attribute<wbr>Response</h4>



{{% choosable language csharp %}}
<dl class="resources-properties"><dt class="property-required"
            title="Required">
        <span id="name_csharp">
<a href="#name_csharp" style="color: inherit; text-decoration: inherit;">Name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}API key of the attribute.{{% /md %}}</dd><dt class="property-required"
            title="Required">
        <span id="value_csharp">
<a href="#value_csharp" style="color: inherit; text-decoration: inherit;">Value</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Value of the attribute.{{% /md %}}</dd></dl>
{{% /choosable %}}

{{% choosable language go %}}
<dl class="resources-properties"><dt class="property-required"
            title="Required">
        <span id="name_go">
<a href="#name_go" style="color: inherit; text-decoration: inherit;">Name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}API key of the attribute.{{% /md %}}</dd><dt class="property-required"
            title="Required">
        <span id="value_go">
<a href="#value_go" style="color: inherit; text-decoration: inherit;">Value</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Value of the attribute.{{% /md %}}</dd></dl>
{{% /choosable %}}

{{% choosable language nodejs %}}
<dl class="resources-properties"><dt class="property-required"
            title="Required">
        <span id="name_nodejs">
<a href="#name_nodejs" style="color: inherit; text-decoration: inherit;">name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}API key of the attribute.{{% /md %}}</dd><dt class="property-required"
            title="Required">
        <span id="value_nodejs">
<a href="#value_nodejs" style="color: inherit; text-decoration: inherit;">value</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Value of the attribute.{{% /md %}}</dd></dl>
{{% /choosable %}}

{{% choosable language python %}}
<dl class="resources-properties"><dt class="property-required"
            title="Required">
        <span id="name_python">
<a href="#name_python" style="color: inherit; text-decoration: inherit;">name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}API key of the attribute.{{% /md %}}</dd><dt class="property-required"
            title="Required">
        <span id="value_python">
<a href="#value_python" style="color: inherit; text-decoration: inherit;">value</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Value of the attribute.{{% /md %}}</dd></dl>
{{% /choosable %}}





<h2 id="package-details">Package Details</h2>
<dl class="package-details">
	<dt>Repository</dt>
	<dd><a href="https://github.com/pulumi/pulumi-google-native">https://github.com/pulumi/pulumi-google-native</a></dd>
	<dt>License</dt>
	<dd>Apache-2.0</dd>
</dl>

