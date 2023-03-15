# dynamic-variables
An example of how to dynamically update variables using Dynamic Configuration!

## How it works

1. We use two configuration files: Our standard, and then our secondary configuration.
2. After cloning, run `sed` to replace a variable in our our secondary configuration and output to a new file, `newConfig.yml`. In this case, we are replacing `{parallelismVal}` with 4.
3. Run the continatuion orb to call this new file, and observe the custom value has taken effect.

## Further uses

In this example, we are simply making a switch that's hardcoded in our basic .yml file. However, this value can be fully dynamic and based on anything you can determine in a given job.

Hello, you!
