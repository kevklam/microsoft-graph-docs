---
description: "Automatically generated file. DO NOT MODIFY"
---

```javascript

const options = {
	authProvider,
};

const client = Client.init(options);

let updatableAsset = await client.api('/admin/windows/updates/updatableAssets/{updatableAssetId}')
	.version('beta')
	.get();

```