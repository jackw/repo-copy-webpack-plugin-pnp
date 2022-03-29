# The solution to this issue is to update [yarn berry to 3.2.0+](https://github.com/webpack-contrib/copy-webpack-plugin/issues/643#issuecomment-1024798817) 


## repo-copy-webpack-plugin-pnp

Dummy repo using yarn 3.1.0 and pnp module resolution which potentially breaks `copy-webpack-plugin@10`.

To reproduce:

1. clone this repo
2. run `yarn`
3. run `yarn build`
