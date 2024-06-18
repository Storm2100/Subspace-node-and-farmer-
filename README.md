Download executables from subspace docs
https://docs.subspace.network/docs/farming-&-staking/farming/advanced-cli/cli-install/



depends on your hardware specification


Guide for ubuntu

open terminal


upload files to directory

change directory using

cd /home/ PATH_TO_FILE

make node files executable using


chmod +x subspace-node-ubuntu-x86_64-v2-gemini-3h-2024-jun-11


start node using


   
  ./subspace-node-ubuntu-x86_64-v2-gemini-3h-2024-jun-11 \
    run \
    --chain gemini-3h \
    --base-path NODE_DATA_PATH \
    --farmer \
    --name "NICKNAME"
    --sync snap 


    
    NODE SYNC SHOULD START
