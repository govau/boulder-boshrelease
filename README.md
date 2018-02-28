

```bash
bosh create-release --force && bosh upload-release && bosh deploy -d boulder -n boulder-deployment.yml
```