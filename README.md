# jhrepo



  "Name": "Subscription Manager",
  "Id": "9c1078ce-77b0-4d2c-9645-337028e48972",
  "IsCustom": true,
  "Description": "Custom role to allow users to manage resources in a specific subscription",
  "Actions": [
    "Microsoft.Resources/deployments/*",
    "Microsoft.Resources/subscriptions/resourceGroups/*",
    "Microsoft.Resources/subscriptions/resourceGroups/read",
    "Microsoft.Resources/subscriptions/resourceGroups/write",
    "Microsoft.Resources/subscriptions/resourceGroups/delete",
    "Microsoft.Resources/subscriptions/resourceGroups/moveResources"
  ],
  "AssignableScopes": [
    "/subscriptions/9c1078ce-77b0-4d2c-9645-337028e48972"
  ]
}