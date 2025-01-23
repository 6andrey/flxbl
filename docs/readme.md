
## build artifacts

> sfp build -v flxbl-devhub

## build artifact only changed

> sfp build -v flxbl-devhub --diffcheck

## create unlocked package

> sf package create --name force-app --package-type Unlocked  --no-namespace --target-dev-hub flxbl-devhub --path src\force-app\main\default


[Unlocked Packages](https://developer.salesforce.com/docs/atlas.en-us.sfdx_dev.meta/sfdx_dev/sfdx_dev_unlocked_pkg_intro.htm)

[Control Which Profile Settings Are Packaged](https://help.salesforce.com/s/articleView?id=release-notes.rn_packaging_scope_profiles.htm&release=248&type=5)
