# Custom image for k3d to have NFS support

Add NFS support in k3d using custom k3s dockerfile

## To use

Run `export K3D_FIX_CGROUPV2=false` first and then `k3d cluster create -i <image>`

## To do

Ideally shouldn't have to override the k3d custom entrypoint like this, but not sure how to inject the nfs commands otherwise.

## Tested with this version

TBD
