# Page Directives

This repository contain the public Page Directives JavaScript library that lets authors turn ordinary web pages into personalised, interactive experiences. Add a few attributes to your markup and the library fills in CRM data, prepopulates forms, shows or hides content by condition, verifies identity, and opens up collaborative pages where visitors and your team communicate together.

You will need Send2CRM.js and a Send2CRM service to connect to.

## License

Use of this software is subject to the [EULA](https://github.com/FuseInfoTech/loupejs/blob/main/EULA.txt)

## page-directives.min.js

This is the main client library. To include on your website:

```
<script src="/page-directives.min.js"></script>
```

### Optional: Subresource Integrity (SRI) hash verification

Copy the SRI hash from the page-directives.sri-hash.sha384 file.

```
<script
  src="/page-directives.min.js"
  integrity="sha384-YQ3FeqLyUD9MrJhqIsvAVo8k82eMCV4RmcgAK8QFfOUq/pDFX0RRC1HVFHYIAbPO"
  crossorigin="anonymous">
</script>
```

If delivering via CDN, ensure that a specific version is applied and the hash used is from the same release.

## CDN hosted

The library may be delivered directly from Github via the jsDelivr CDN.

Instead of copying the script file to your web server, reference the latest version directly:

```
https://cdn.jsdelivr.net/gh/FuseInfoTech/loupejs/page-directives@v0.1.0/page-directives.min.js
```
