# imgls

imgls is a command-line tool which prints an ls style listing of image files.
Inspired by the list output in [feh](https://feh.finalrewind.org/).


## Example Output

```
$ imgls 
NUM FORMAT  WIDTH HEIGHT  SIZE  FILENAME
1 jpeg  2448  3264  2M  IMG_20160107_081137.jpg
2 jpeg  2448  3264  2M  IMG_20160107_081749.jpg
3 jpeg  2448  3264  4M  IMG_20160209_195745.jpg
4 jpeg  2448  3264  4M  IMG_20160209_195814.jpg
5 jpeg  2448  3264  5M  IMG_20160209_195833.jpg
6 jpeg  2448  3264  2M  IMG_20160707_201515.jpg
7 jpeg  2448  3264  2M  IMG_20160707_203408.jpg
8 jpeg  2448  3264  1M  IMG_20160806_183223.jpg
9 jpeg  2448  3264  1M  IMG_20160806_183253.jpg
```


## Install

```shell
$ go get -u github.com/rsookram/imgls/cmd/imgls
```


## License

imgls is licensed under the [MIT license](LICENSE).

