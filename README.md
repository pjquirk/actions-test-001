# actions-test-001

```kusto
source
| where Tenant == "<tenant_name>"
| where ident == "runner-job-agent"
| where message contains "JobHistory"
| where message contains "PoolSyncJob"
```

```csl
source
| where Tenant == "<tenant_name>"
| where ident == "runner-job-agent"
| where message contains "JobHistory"
| where message contains "PoolSyncJob"
```

```json
{ "foo": "bar" }
```
