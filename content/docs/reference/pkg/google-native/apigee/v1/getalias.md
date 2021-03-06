
---
title: "getAlias"
title_tag: "google-native.apigee/v1.getAlias"
meta_desc: "Documentation for the google-native.apigee/v1.getAlias function with examples, input properties, output properties, and supporting types."
---



<!-- WARNING: this file was generated by Pulumi Docs Generator. -->
<!-- Do not edit by hand unless you're certain you know what you are doing! -->

Gets an alias.




## Using getAlias {#using}

{{< chooser language "typescript,python,go,csharp" / >}}


{{% choosable language nodejs %}}
<div class="highlight"><pre class="chroma"><code class="language-typescript" data-lang="typescript"><span class="k">function </span>getAlias<span class="p">(</span><span class="nx">args</span><span class="p">:</span> <span class="nx">GetAliasArgs</span><span class="p">,</span> <span class="nx">opts</span><span class="p">?:</span> <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/pulumi/#InvokeOptions">InvokeOptions</a></span><span class="p">): Promise&lt;<span class="nx"><a href="#result">GetAliasResult</a></span>></span></code></pre></div>
{{% /choosable %}}


{{% choosable language python %}}
<div class="highlight"><pre class="chroma"><code class="language-python" data-lang="python"><span class="k">def </span>get_alias(</span><span class="nx">alias_id</span><span class="p">:</span> <span class="nx">Optional[str]</span> = None<span class="p">,</span>
              <span class="nx">environment_id</span><span class="p">:</span> <span class="nx">Optional[str]</span> = None<span class="p">,</span>
              <span class="nx">keystore_id</span><span class="p">:</span> <span class="nx">Optional[str]</span> = None<span class="p">,</span>
              <span class="nx">organization_id</span><span class="p">:</span> <span class="nx">Optional[str]</span> = None<span class="p">,</span>
              <span class="nx">opts</span><span class="p">:</span> <span class="nx"><a href="/docs/reference/pkg/python/pulumi/#pulumi.InvokeOptions">Optional[InvokeOptions]</a></span> = None<span class="p">) -&gt;</span> GetAliasResult</code></pre></div>
{{% /choosable %}}


{{% choosable language go %}}
<div class="highlight"><pre class="chroma"><code class="language-go" data-lang="go"><span class="k">func </span>LookupAlias<span class="p">(</span><span class="nx">ctx</span><span class="p"> *</span><span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/v3/go/pulumi?tab=doc#Context">Context</a></span><span class="p">,</span> <span class="nx">args</span><span class="p"> *</span><span class="nx">LookupAliasArgs</span><span class="p">,</span> <span class="nx">opts</span><span class="p"> ...</span><span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/v3/go/pulumi?tab=doc#InvokeOption">InvokeOption</a></span><span class="p">) (*<span class="nx"><a href="#result">LookupAliasResult</a></span>, error)</span></code></pre></div>

> Note: This function is named `LookupAlias` in the Go SDK.

{{% /choosable %}}


{{% choosable language csharp %}}
<div class="highlight"><pre class="chroma"><code class="language-csharp" data-lang="csharp"><span class="k">public static class </span><span class="nx">GetAlias </span><span class="p">{</span><span class="k">
    public static </span>Task&lt;<span class="nx"><a href="#result">GetAliasResult</a></span>> <span class="p">InvokeAsync(</span><span class="nx">GetAliasArgs</span><span class="p"> </span><span class="nx">args<span class="p">,</span> <span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi/Pulumi.InvokeOptions.html">InvokeOptions</a></span><span class="p">? </span><span class="nx">opts = null<span class="p">)</span><span class="p">
}</span></code></pre></div>
{{% /choosable %}}



The following arguments are supported:


{{% choosable language csharp %}}
<dl class="resources-properties"><dt class="property-required"
            title="Required">
        <span id="aliasid_csharp">
<a href="#aliasid_csharp" style="color: inherit; text-decoration: inherit;">Alias<wbr>Id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd><dt class="property-required"
            title="Required">
        <span id="environmentid_csharp">
<a href="#environmentid_csharp" style="color: inherit; text-decoration: inherit;">Environment<wbr>Id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd><dt class="property-required"
            title="Required">
        <span id="keystoreid_csharp">
<a href="#keystoreid_csharp" style="color: inherit; text-decoration: inherit;">Keystore<wbr>Id</a>
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
    <dd>{{% md %}}{{% /md %}}</dd></dl>
{{% /choosable %}}

{{% choosable language go %}}
<dl class="resources-properties"><dt class="property-required"
            title="Required">
        <span id="aliasid_go">
<a href="#aliasid_go" style="color: inherit; text-decoration: inherit;">Alias<wbr>Id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd><dt class="property-required"
            title="Required">
        <span id="environmentid_go">
<a href="#environmentid_go" style="color: inherit; text-decoration: inherit;">Environment<wbr>Id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd><dt class="property-required"
            title="Required">
        <span id="keystoreid_go">
<a href="#keystoreid_go" style="color: inherit; text-decoration: inherit;">Keystore<wbr>Id</a>
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
    <dd>{{% md %}}{{% /md %}}</dd></dl>
{{% /choosable %}}

{{% choosable language nodejs %}}
<dl class="resources-properties"><dt class="property-required"
            title="Required">
        <span id="aliasid_nodejs">
<a href="#aliasid_nodejs" style="color: inherit; text-decoration: inherit;">alias<wbr>Id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd><dt class="property-required"
            title="Required">
        <span id="environmentid_nodejs">
<a href="#environmentid_nodejs" style="color: inherit; text-decoration: inherit;">environment<wbr>Id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd><dt class="property-required"
            title="Required">
        <span id="keystoreid_nodejs">
<a href="#keystoreid_nodejs" style="color: inherit; text-decoration: inherit;">keystore<wbr>Id</a>
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
    <dd>{{% md %}}{{% /md %}}</dd></dl>
{{% /choosable %}}

{{% choosable language python %}}
<dl class="resources-properties"><dt class="property-required"
            title="Required">
        <span id="alias_id_python">
<a href="#alias_id_python" style="color: inherit; text-decoration: inherit;">alias_<wbr>id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd><dt class="property-required"
            title="Required">
        <span id="environment_id_python">
<a href="#environment_id_python" style="color: inherit; text-decoration: inherit;">environment_<wbr>id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd><dt class="property-required"
            title="Required">
        <span id="keystore_id_python">
<a href="#keystore_id_python" style="color: inherit; text-decoration: inherit;">keystore_<wbr>id</a>
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
    <dd>{{% md %}}{{% /md %}}</dd></dl>
{{% /choosable %}}




## getAlias Result {#result}

The following output properties are available:



{{% choosable language csharp %}}
<dl class="resources-properties"><dt class="property-"
            title="">
        <span id="alias_csharp">
<a href="#alias_csharp" style="color: inherit; text-decoration: inherit;">Alias</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Resource ID for this alias. Values must match the regular expression `[^/]{1,255}`.{{% /md %}}</dd><dt class="property-"
            title="">
        <span id="certsinfo_csharp">
<a href="#certsinfo_csharp" style="color: inherit; text-decoration: inherit;">Certs<wbr>Info</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#googlecloudapigeev1certificateresponse">Pulumi.<wbr>Google<wbr>Native.<wbr>Apigee.<wbr>V1.<wbr>Outputs.<wbr>Google<wbr>Cloud<wbr>Apigee<wbr>V1Certificate<wbr>Response</a></span>
    </dt>
    <dd>{{% md %}}Chain of certificates under this alias.{{% /md %}}</dd><dt class="property-"
            title="">
        <span id="type_csharp">
<a href="#type_csharp" style="color: inherit; text-decoration: inherit;">Type</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Type of alias.{{% /md %}}</dd></dl>
{{% /choosable %}}

{{% choosable language go %}}
<dl class="resources-properties"><dt class="property-"
            title="">
        <span id="alias_go">
<a href="#alias_go" style="color: inherit; text-decoration: inherit;">Alias</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Resource ID for this alias. Values must match the regular expression `[^/]{1,255}`.{{% /md %}}</dd><dt class="property-"
            title="">
        <span id="certsinfo_go">
<a href="#certsinfo_go" style="color: inherit; text-decoration: inherit;">Certs<wbr>Info</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#googlecloudapigeev1certificateresponse">Google<wbr>Cloud<wbr>Apigee<wbr>V1Certificate<wbr>Response</a></span>
    </dt>
    <dd>{{% md %}}Chain of certificates under this alias.{{% /md %}}</dd><dt class="property-"
            title="">
        <span id="type_go">
<a href="#type_go" style="color: inherit; text-decoration: inherit;">Type</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Type of alias.{{% /md %}}</dd></dl>
{{% /choosable %}}

{{% choosable language nodejs %}}
<dl class="resources-properties"><dt class="property-"
            title="">
        <span id="alias_nodejs">
<a href="#alias_nodejs" style="color: inherit; text-decoration: inherit;">alias</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Resource ID for this alias. Values must match the regular expression `[^/]{1,255}`.{{% /md %}}</dd><dt class="property-"
            title="">
        <span id="certsinfo_nodejs">
<a href="#certsinfo_nodejs" style="color: inherit; text-decoration: inherit;">certs<wbr>Info</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#googlecloudapigeev1certificateresponse">Google<wbr>Cloud<wbr>Apigee<wbr>V1Certificate<wbr>Response</a></span>
    </dt>
    <dd>{{% md %}}Chain of certificates under this alias.{{% /md %}}</dd><dt class="property-"
            title="">
        <span id="type_nodejs">
<a href="#type_nodejs" style="color: inherit; text-decoration: inherit;">type</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Type of alias.{{% /md %}}</dd></dl>
{{% /choosable %}}

{{% choosable language python %}}
<dl class="resources-properties"><dt class="property-"
            title="">
        <span id="alias_python">
<a href="#alias_python" style="color: inherit; text-decoration: inherit;">alias</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Resource ID for this alias. Values must match the regular expression `[^/]{1,255}`.{{% /md %}}</dd><dt class="property-"
            title="">
        <span id="certs_info_python">
<a href="#certs_info_python" style="color: inherit; text-decoration: inherit;">certs_<wbr>info</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#googlecloudapigeev1certificateresponse">Google<wbr>Cloud<wbr>Apigee<wbr>V1Certificate<wbr>Response</a></span>
    </dt>
    <dd>{{% md %}}Chain of certificates under this alias.{{% /md %}}</dd><dt class="property-"
            title="">
        <span id="type_python">
<a href="#type_python" style="color: inherit; text-decoration: inherit;">type</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Type of alias.{{% /md %}}</dd></dl>
{{% /choosable %}}




## Supporting Types


<h4 id="googlecloudapigeev1certinforesponse">Google<wbr>Cloud<wbr>Apigee<wbr>V1Cert<wbr>Info<wbr>Response</h4>



{{% choosable language csharp %}}
<dl class="resources-properties"><dt class="property-required"
            title="Required">
        <span id="basicconstraints_csharp">
<a href="#basicconstraints_csharp" style="color: inherit; text-decoration: inherit;">Basic<wbr>Constraints</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}X.509 basic constraints extension.{{% /md %}}</dd><dt class="property-required"
            title="Required">
        <span id="expirydate_csharp">
<a href="#expirydate_csharp" style="color: inherit; text-decoration: inherit;">Expiry<wbr>Date</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}X.509 `notAfter` validity period in milliseconds since epoch.{{% /md %}}</dd><dt class="property-required"
            title="Required">
        <span id="isvalid_csharp">
<a href="#isvalid_csharp" style="color: inherit; text-decoration: inherit;">Is<wbr>Valid</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Flag that specifies whether the certificate is valid. Flag is set to `Yes` if the certificate is valid, `No` if expired, or `Not yet` if not yet valid.{{% /md %}}</dd><dt class="property-required"
            title="Required">
        <span id="issuer_csharp">
<a href="#issuer_csharp" style="color: inherit; text-decoration: inherit;">Issuer</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}X.509 issuer.{{% /md %}}</dd><dt class="property-required"
            title="Required">
        <span id="publickey_csharp">
<a href="#publickey_csharp" style="color: inherit; text-decoration: inherit;">Public<wbr>Key</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Public key component of the X.509 subject public key info.{{% /md %}}</dd><dt class="property-required"
            title="Required">
        <span id="serialnumber_csharp">
<a href="#serialnumber_csharp" style="color: inherit; text-decoration: inherit;">Serial<wbr>Number</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}X.509 serial number.{{% /md %}}</dd><dt class="property-required"
            title="Required">
        <span id="sigalgname_csharp">
<a href="#sigalgname_csharp" style="color: inherit; text-decoration: inherit;">Sig<wbr>Alg<wbr>Name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}X.509 signatureAlgorithm.{{% /md %}}</dd><dt class="property-required"
            title="Required">
        <span id="subject_csharp">
<a href="#subject_csharp" style="color: inherit; text-decoration: inherit;">Subject</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}X.509 subject.{{% /md %}}</dd><dt class="property-required"
            title="Required">
        <span id="subjectalternativenames_csharp">
<a href="#subjectalternativenames_csharp" style="color: inherit; text-decoration: inherit;">Subject<wbr>Alternative<wbr>Names</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">List&lt;string&gt;</span>
    </dt>
    <dd>{{% md %}}X.509 subject alternative names (SANs) extension.{{% /md %}}</dd><dt class="property-required"
            title="Required">
        <span id="validfrom_csharp">
<a href="#validfrom_csharp" style="color: inherit; text-decoration: inherit;">Valid<wbr>From</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}X.509 `notBefore` validity period in milliseconds since epoch.{{% /md %}}</dd><dt class="property-required"
            title="Required">
        <span id="version_csharp">
<a href="#version_csharp" style="color: inherit; text-decoration: inherit;">Version</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">int</span>
    </dt>
    <dd>{{% md %}}X.509 version.{{% /md %}}</dd></dl>
{{% /choosable %}}

{{% choosable language go %}}
<dl class="resources-properties"><dt class="property-required"
            title="Required">
        <span id="basicconstraints_go">
<a href="#basicconstraints_go" style="color: inherit; text-decoration: inherit;">Basic<wbr>Constraints</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}X.509 basic constraints extension.{{% /md %}}</dd><dt class="property-required"
            title="Required">
        <span id="expirydate_go">
<a href="#expirydate_go" style="color: inherit; text-decoration: inherit;">Expiry<wbr>Date</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}X.509 `notAfter` validity period in milliseconds since epoch.{{% /md %}}</dd><dt class="property-required"
            title="Required">
        <span id="isvalid_go">
<a href="#isvalid_go" style="color: inherit; text-decoration: inherit;">Is<wbr>Valid</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Flag that specifies whether the certificate is valid. Flag is set to `Yes` if the certificate is valid, `No` if expired, or `Not yet` if not yet valid.{{% /md %}}</dd><dt class="property-required"
            title="Required">
        <span id="issuer_go">
<a href="#issuer_go" style="color: inherit; text-decoration: inherit;">Issuer</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}X.509 issuer.{{% /md %}}</dd><dt class="property-required"
            title="Required">
        <span id="publickey_go">
<a href="#publickey_go" style="color: inherit; text-decoration: inherit;">Public<wbr>Key</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Public key component of the X.509 subject public key info.{{% /md %}}</dd><dt class="property-required"
            title="Required">
        <span id="serialnumber_go">
<a href="#serialnumber_go" style="color: inherit; text-decoration: inherit;">Serial<wbr>Number</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}X.509 serial number.{{% /md %}}</dd><dt class="property-required"
            title="Required">
        <span id="sigalgname_go">
<a href="#sigalgname_go" style="color: inherit; text-decoration: inherit;">Sig<wbr>Alg<wbr>Name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}X.509 signatureAlgorithm.{{% /md %}}</dd><dt class="property-required"
            title="Required">
        <span id="subject_go">
<a href="#subject_go" style="color: inherit; text-decoration: inherit;">Subject</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}X.509 subject.{{% /md %}}</dd><dt class="property-required"
            title="Required">
        <span id="subjectalternativenames_go">
<a href="#subjectalternativenames_go" style="color: inherit; text-decoration: inherit;">Subject<wbr>Alternative<wbr>Names</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">[]string</span>
    </dt>
    <dd>{{% md %}}X.509 subject alternative names (SANs) extension.{{% /md %}}</dd><dt class="property-required"
            title="Required">
        <span id="validfrom_go">
<a href="#validfrom_go" style="color: inherit; text-decoration: inherit;">Valid<wbr>From</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}X.509 `notBefore` validity period in milliseconds since epoch.{{% /md %}}</dd><dt class="property-required"
            title="Required">
        <span id="version_go">
<a href="#version_go" style="color: inherit; text-decoration: inherit;">Version</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">int</span>
    </dt>
    <dd>{{% md %}}X.509 version.{{% /md %}}</dd></dl>
{{% /choosable %}}

{{% choosable language nodejs %}}
<dl class="resources-properties"><dt class="property-required"
            title="Required">
        <span id="basicconstraints_nodejs">
<a href="#basicconstraints_nodejs" style="color: inherit; text-decoration: inherit;">basic<wbr>Constraints</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}X.509 basic constraints extension.{{% /md %}}</dd><dt class="property-required"
            title="Required">
        <span id="expirydate_nodejs">
<a href="#expirydate_nodejs" style="color: inherit; text-decoration: inherit;">expiry<wbr>Date</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}X.509 `notAfter` validity period in milliseconds since epoch.{{% /md %}}</dd><dt class="property-required"
            title="Required">
        <span id="isvalid_nodejs">
<a href="#isvalid_nodejs" style="color: inherit; text-decoration: inherit;">is<wbr>Valid</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Flag that specifies whether the certificate is valid. Flag is set to `Yes` if the certificate is valid, `No` if expired, or `Not yet` if not yet valid.{{% /md %}}</dd><dt class="property-required"
            title="Required">
        <span id="issuer_nodejs">
<a href="#issuer_nodejs" style="color: inherit; text-decoration: inherit;">issuer</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}X.509 issuer.{{% /md %}}</dd><dt class="property-required"
            title="Required">
        <span id="publickey_nodejs">
<a href="#publickey_nodejs" style="color: inherit; text-decoration: inherit;">public<wbr>Key</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Public key component of the X.509 subject public key info.{{% /md %}}</dd><dt class="property-required"
            title="Required">
        <span id="serialnumber_nodejs">
<a href="#serialnumber_nodejs" style="color: inherit; text-decoration: inherit;">serial<wbr>Number</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}X.509 serial number.{{% /md %}}</dd><dt class="property-required"
            title="Required">
        <span id="sigalgname_nodejs">
<a href="#sigalgname_nodejs" style="color: inherit; text-decoration: inherit;">sig<wbr>Alg<wbr>Name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}X.509 signatureAlgorithm.{{% /md %}}</dd><dt class="property-required"
            title="Required">
        <span id="subject_nodejs">
<a href="#subject_nodejs" style="color: inherit; text-decoration: inherit;">subject</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}X.509 subject.{{% /md %}}</dd><dt class="property-required"
            title="Required">
        <span id="subjectalternativenames_nodejs">
<a href="#subjectalternativenames_nodejs" style="color: inherit; text-decoration: inherit;">subject<wbr>Alternative<wbr>Names</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string[]</span>
    </dt>
    <dd>{{% md %}}X.509 subject alternative names (SANs) extension.{{% /md %}}</dd><dt class="property-required"
            title="Required">
        <span id="validfrom_nodejs">
<a href="#validfrom_nodejs" style="color: inherit; text-decoration: inherit;">valid<wbr>From</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}X.509 `notBefore` validity period in milliseconds since epoch.{{% /md %}}</dd><dt class="property-required"
            title="Required">
        <span id="version_nodejs">
<a href="#version_nodejs" style="color: inherit; text-decoration: inherit;">version</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">number</span>
    </dt>
    <dd>{{% md %}}X.509 version.{{% /md %}}</dd></dl>
{{% /choosable %}}

{{% choosable language python %}}
<dl class="resources-properties"><dt class="property-required"
            title="Required">
        <span id="basic_constraints_python">
<a href="#basic_constraints_python" style="color: inherit; text-decoration: inherit;">basic_<wbr>constraints</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}X.509 basic constraints extension.{{% /md %}}</dd><dt class="property-required"
            title="Required">
        <span id="expiry_date_python">
<a href="#expiry_date_python" style="color: inherit; text-decoration: inherit;">expiry_<wbr>date</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}X.509 `notAfter` validity period in milliseconds since epoch.{{% /md %}}</dd><dt class="property-required"
            title="Required">
        <span id="is_valid_python">
<a href="#is_valid_python" style="color: inherit; text-decoration: inherit;">is_<wbr>valid</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Flag that specifies whether the certificate is valid. Flag is set to `Yes` if the certificate is valid, `No` if expired, or `Not yet` if not yet valid.{{% /md %}}</dd><dt class="property-required"
            title="Required">
        <span id="issuer_python">
<a href="#issuer_python" style="color: inherit; text-decoration: inherit;">issuer</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}X.509 issuer.{{% /md %}}</dd><dt class="property-required"
            title="Required">
        <span id="public_key_python">
<a href="#public_key_python" style="color: inherit; text-decoration: inherit;">public_<wbr>key</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Public key component of the X.509 subject public key info.{{% /md %}}</dd><dt class="property-required"
            title="Required">
        <span id="serial_number_python">
<a href="#serial_number_python" style="color: inherit; text-decoration: inherit;">serial_<wbr>number</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}X.509 serial number.{{% /md %}}</dd><dt class="property-required"
            title="Required">
        <span id="sig_alg_name_python">
<a href="#sig_alg_name_python" style="color: inherit; text-decoration: inherit;">sig_<wbr>alg_<wbr>name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}X.509 signatureAlgorithm.{{% /md %}}</dd><dt class="property-required"
            title="Required">
        <span id="subject_python">
<a href="#subject_python" style="color: inherit; text-decoration: inherit;">subject</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}X.509 subject.{{% /md %}}</dd><dt class="property-required"
            title="Required">
        <span id="subject_alternative_names_python">
<a href="#subject_alternative_names_python" style="color: inherit; text-decoration: inherit;">subject_<wbr>alternative_<wbr>names</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">Sequence[str]</span>
    </dt>
    <dd>{{% md %}}X.509 subject alternative names (SANs) extension.{{% /md %}}</dd><dt class="property-required"
            title="Required">
        <span id="valid_from_python">
<a href="#valid_from_python" style="color: inherit; text-decoration: inherit;">valid_<wbr>from</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}X.509 `notBefore` validity period in milliseconds since epoch.{{% /md %}}</dd><dt class="property-required"
            title="Required">
        <span id="version_python">
<a href="#version_python" style="color: inherit; text-decoration: inherit;">version</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">int</span>
    </dt>
    <dd>{{% md %}}X.509 version.{{% /md %}}</dd></dl>
{{% /choosable %}}

<h4 id="googlecloudapigeev1certificateresponse">Google<wbr>Cloud<wbr>Apigee<wbr>V1Certificate<wbr>Response</h4>



{{% choosable language csharp %}}
<dl class="resources-properties"><dt class="property-required"
            title="Required">
        <span id="certinfo_csharp">
<a href="#certinfo_csharp" style="color: inherit; text-decoration: inherit;">Cert<wbr>Info</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#googlecloudapigeev1certinforesponse">List&lt;Pulumi.<wbr>Google<wbr>Native.<wbr>Apigee.<wbr>V1.<wbr>Inputs.<wbr>Google<wbr>Cloud<wbr>Apigee<wbr>V1Cert<wbr>Info<wbr>Response&gt;</a></span>
    </dt>
    <dd>{{% md %}}Chain of certificates under this name.{{% /md %}}</dd></dl>
{{% /choosable %}}

{{% choosable language go %}}
<dl class="resources-properties"><dt class="property-required"
            title="Required">
        <span id="certinfo_go">
<a href="#certinfo_go" style="color: inherit; text-decoration: inherit;">Cert<wbr>Info</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#googlecloudapigeev1certinforesponse">[]Google<wbr>Cloud<wbr>Apigee<wbr>V1Cert<wbr>Info<wbr>Response</a></span>
    </dt>
    <dd>{{% md %}}Chain of certificates under this name.{{% /md %}}</dd></dl>
{{% /choosable %}}

{{% choosable language nodejs %}}
<dl class="resources-properties"><dt class="property-required"
            title="Required">
        <span id="certinfo_nodejs">
<a href="#certinfo_nodejs" style="color: inherit; text-decoration: inherit;">cert<wbr>Info</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#googlecloudapigeev1certinforesponse">Google<wbr>Cloud<wbr>Apigee<wbr>V1Cert<wbr>Info<wbr>Response[]</a></span>
    </dt>
    <dd>{{% md %}}Chain of certificates under this name.{{% /md %}}</dd></dl>
{{% /choosable %}}

{{% choosable language python %}}
<dl class="resources-properties"><dt class="property-required"
            title="Required">
        <span id="cert_info_python">
<a href="#cert_info_python" style="color: inherit; text-decoration: inherit;">cert_<wbr>info</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#googlecloudapigeev1certinforesponse">Google<wbr>Cloud<wbr>Apigee<wbr>V1Cert<wbr>Info<wbr>Response]</a></span>
    </dt>
    <dd>{{% md %}}Chain of certificates under this name.{{% /md %}}</dd></dl>
{{% /choosable %}}





<h2 id="package-details">Package Details</h2>
<dl class="package-details">
	<dt>Repository</dt>
	<dd><a href="https://github.com/pulumi/pulumi-google-native">https://github.com/pulumi/pulumi-google-native</a></dd>
	<dt>License</dt>
	<dd>Apache-2.0</dd>
</dl>

