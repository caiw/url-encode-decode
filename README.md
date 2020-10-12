A simple url encoder and decoder written in Python 3.

## urlencode

Use it on a file:

```sh
python /path/from/root/to/urlencode/dir/urlencode my_file.txt
```

Or with a pipe:

```sh
pbpaste | python /path/from/root/to/urlencode/dir/urlencode
```

Install by adding

```sh
export PATH="/path/from/root/to/urlencode/dir:$PATH"
```

to `~/.bash_profile` (MacOS 10.12+).  Then you can run it from anywhere without including the path or invoking python directly:

```sh
urlencode myfile.txt
```

```sh
echo "test" | urlencode
```

## urldecode

Same as above, but replace `urlencode` with `urldecode`.
