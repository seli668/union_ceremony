# union_ceremony

log in ceremony.union.build with your github account

open the terminal and use the command:

mkdir -p ceremony && docker pull ghcr.io/unionlabs/union/mpc-client:v1.2 && docker run -v $(pwd)/ceremony:/ceremony -w /ceremony -p 4919:4919 --rm -it ghcr.io/unionlabs/union/mpc-client:v1.2
