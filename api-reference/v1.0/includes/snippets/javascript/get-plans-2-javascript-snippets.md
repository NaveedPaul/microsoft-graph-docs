---
description: "Automatically generated file. DO NOT MODIFY"
---

```javascript

const options = {
	authProvider,
};

const client = Client.init(options);

let plans = await client.api('/groups/{group-id}/planner/plans')
	.get();

```