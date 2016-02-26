# testhome-cookbook

This cookbook creates a file, index.html, in /root. It has a dependency, ack cookbook, just to test dependency management with Berkshelf. I am using this cookbook from this Vagrant project: [https://github.com/rtacconi/chef-solo-demo](https://github.com/rtacconi/chef-solo-demo).

## Supported Platforms

Linux

## Attributes

None

## Usage

Just run the default recipe, see below

### testhome::default

Include `testhome` in your node's `run_list`:

```json
{
  "run_list": [
    "recipe[testhome::default]"
  ]
}
```

## License and Authors

Author:: Riccardo Tacconi (<rtacconi@gmail.com>)
