```
cf2 cluster add demo --labels shortname=dev --labels type=non-prod --context demo-dev --name demo-dev --skip-tls-validation --insecure
cf2 cluster add demo --labels shortname=qa  --labels type=non-prod --context demo-qa  --name demo-qa  --skip-tls-validation --insecure

cf2 cluster add demo --labels shortname=staging  --labels type=prod --context demo-staging  --name demo-staging  --skip-tls-validation --insecure

cf2 cluster add demo --labels shortname=east  --labels type=prod --labels tenant=east --context demo-east  --name demo-east  --skip-tls-validation --insecure
cf2 cluster add demo --labels shortname=west  --labels type=prod --labels tenant=west --context demo-west  --name demo-west  --skip-tls-validation --insecure
```
