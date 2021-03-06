# Configure Node.js

The Node.js engine exposes configuration options through the [boxfile.yml](http://docs.nanobox.io/boxfile/).

#### runtime
Specifies which Node.js runtime and version to use. The following runtimes are available:

- nodejs-0.8
- nodejs-0.10
- nodejs-0.12
- nodejs-4.0
- nodejs-4.1
- nodejs-4.2
- nodejs-4.3
- nodejs-4.4 *(default)*
- nodejs-5.0
- nodejs-5.1
- nodejs-5.2
- nodejs-5.3
- nodejs-5.4
- nodejs-5.5
- nodejs-5.6
- nodejs-5.7
- nodejs-5.8
- nodejs-5.9
- nodejs-5.10
- nodejs-5.11
- nodejs-5.12
- nodejs-6.0
- nodejs-6.1
- nodejs-6.2
- nodejs-6.3
- nodejs-6.4
- nodejs-6.5
- iojs-2.3

```yaml
run.config:
  engine.config:
    runtime: nodejs-4.4
```
