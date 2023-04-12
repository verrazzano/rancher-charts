## Release Information

The upstream branch this release is branched from is `release-v2.7` using commit hash `176424fce4f19ab8b01141dcec2d4453f075aad2`.

## Asset Changes

The following assets were updated.

### Rancher Webhook 2.0.0+up0.3.0

The contents of `charts/rancher-webhook/2.0.0+up0.3.0` were modified. The asset was recreated using the following steps:

```
cd charts/rancher-webhook
tar -cvzf rancher-webhook-2.0.0+up0.3.0.tgz 2.0.0+up0.3.0
mv rancher-webhook-2.0.0+up0.3.0.tgz ../../assets/rancher-webhook
```