# local-cors-anywhere

A quick npx script for running a local [cors-anywhere](https://github.com/Rob--W/cors-anywhere) instance.

## Usage
``` 
npx local-cors-anywhere
```

```
Usage: local-cors-anywhere [options]

Options:
  -V, --version      output the version number
  -h, --host <host>  Listen on a specific host, or set the HOST env variable
  -p, --port <port>  Listen on a specific port, or set the PORT env variable
  --help             display help for command
```

Then, in order to proxy to `https://github.com`, simply make a request to `http://localhost:8080/https://github.com`, replacing with any configuration options you may have set.

See [cors-anywhere](https://github.com/Rob--W/cors-anywhere) for more information.
