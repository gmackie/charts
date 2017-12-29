# My Helm Charts
This repo is a collection of helm charts/values.yaml files that I use for
running a bunch of stuff on my bare-metal kubernetes cluster. This will likely
evolve over time.


Currently only running with a single node, so most apps that just use TCP ports
are set to the external IP of the node... maybe one day that will change.

I also need to properly setup an NFS server/untangle my RAID setup to be able to
have enough storage to create PVs/PVCs
