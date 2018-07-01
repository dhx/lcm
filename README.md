# lcm

```
# To deploy / update via r10k:
/opt/puppetlabs/puppet/bin/r10k deploy environment -p -v -t

# to ensure the isolation of the environments
for penv in production master
do
  puppet generate types --environment $penv
done
```
