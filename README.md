# aliyun-region-names
Alibaba Cloud (aliyun) JSON mapping of region names to their descriptive counterparts

## Usage
There are 2 `JSON` files, a simple version to quickly access region names programatically and the equivalent to the Aliyun API.

### aliyun-region-names-simple.json
This file is the msot simple one, you just load and parse the `JSON` into your application and access the regions by name.

### aliyun-region-names.json
This file mimics the `DescribeRegions` API response and adds an extra property called `GlobalName` with the english name.
