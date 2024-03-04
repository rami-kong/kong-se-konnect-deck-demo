# kong-se-konnect-deck-demo

Reference flow for using Deck to deploy your Kong configurations, and using Github Actions into Kong Konnect (SaaS)

For this set-up, we will only apply changes to a default control plane

## Important ENV Variables


```yaml
KONNECT_PAT: ${{ secrets.KONNECT_PAT }}
```

You will need to retrive a System Access / Personal Access Token from Konnect Control Plane before you are able to run the ci/cd job