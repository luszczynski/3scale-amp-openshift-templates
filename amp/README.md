oc import-image redhat-sso73-openshift --from=registry.access.redhat.com/redhat-sso-7/sso73-openshift --confirm -n openshift
oc set env dc/router ROUTER_ALLOW_WILDCARD_ROUTES=true -n default
