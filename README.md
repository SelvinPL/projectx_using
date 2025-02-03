Project shows how to make github action which may be executed from [other repo](https://github.com/SelvinPL/projectx).

This action takes a tag from [other repo](https://github.com/SelvinPL/projectx) as parameter and uses it to update submodule (which is this [other repo](https://github.com/SelvinPL/projectx)) and then create PR.

[Other repo](https://github.com/SelvinPL/projectx) requires `GH_TOKEN` secret which is PAT with Action read-write permissions to this repo
