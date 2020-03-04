# Algorithms registry

Check `algos.json` for a simple list of algorithms and functions we want to have deployed. This is used in the https://dash.disarm.io tool.

Each entry needs to have _either_ a `repo` (preferable) or an `image` field. The `repo` field will enable the dashboard to load the `test_req.json` and `stack.yml` files, which are helpful for testing and deployment.
