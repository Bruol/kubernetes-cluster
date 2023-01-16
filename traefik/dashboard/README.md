# Config for traefik dashboard

### missing secret

create secret.yaml

```yaml
apiVersion: v1
kind: Secret
metadata:
  name: traefik-dashboard-auth
  namespace: traefik
type: Opaque
data:
  users:
```
