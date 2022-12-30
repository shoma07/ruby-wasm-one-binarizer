# ruby-wasm-one-binarizer

Create One-binary Ruby using WebAssembly

## Usage

```sh
$ ./bin/ruby-wasm-one-binarizer -d <src directory> -e <entrypoint> -o <output path>
# display help
$ ./bin/ruby-wasm-one-binarizer -h
```

### Example

```sh
$ ./bin/ruby-wasm-one-binarizer -d ./example/src -e app.rb -o ./example/bin/app
$ ./example/bin/app World
Hello World!
```

## Features

- Compiling for multiple CPU architectures.
