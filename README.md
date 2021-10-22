Stuble Collection
=================

My personal [stuble](https://github.com/emsifa/stuble) collection that you can use to scaffold some codes in your project to speed up your development.

## Usage

### Download Collection

Make sure you have install [Stuble](https://github.com/emsifa/stuble) in your local computer.
You can check it by running following command below:

```bash
stuble --version
```

In terminal/cmd, move to your project directory, then you can download this collection by running command below:

```
stuble get emsifa/stuble-collection
```

It will download repository files into `./stubs` in your project directory.

### Generate Scaffolds

If you want to see available scaffolds in this collection, run following command below:

```
stuble ls emsifa/stuble-collection
```

If you already found scaffold name you want to generate, you can generate it by running command below:

```
stuble make emsifa/stuble-collection/laravel8-basic-crud
```

Stuble will ask you to fill parameters needed in that scaffold. And generate files to your project.