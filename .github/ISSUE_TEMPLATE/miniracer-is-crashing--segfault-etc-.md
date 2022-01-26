---
name: MiniRacer is crashing (segfault etc)
about: Bug report for crashes, segfaults, etc
title: ''
labels: bug
assignees: ''

---

**Environment**

Please run the following Ruby script and replace this section with the output:

```ruby
require "mini_racer"
require "libv8-node"

puts <<~EOS
RUBY_VERSION : #{RUBY_VERSION}
RUBY_PLATFORM: #{RUBY_PLATFORM}
MiniRacer::LIBV8_NODE_VERSION: #{MiniRacer::LIBV8_NODE_VERSION}
MiniRacer::VERSION: #{MiniRacer::VERSION}
Libv8::Node::VERSION: #{Libv8::Node::VERSION}
Libv8::Node::NODE_VERSION: #{Libv8::Node::NODE_VERSION}
Libv8::Node::LIBV8_VERSION: #{Libv8::Node::LIBV8_VERSION}
EOS
```

**Describe the bug**
A clear and concise description of what the bug is.

**To Reproduce**
Steps to reproduce the behavior, minimal code example, …

**Crash report/output**

<details>
<summary>Full output of crash / segmentation fault output</summary>

```
PUT YOUR OUTPUT HERE
```

</details>
