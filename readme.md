# Fast style transfer in tf v2

A tensorflow v2 port of [fast style transfer method][fast].

<p align = 'center'>
<img src = 'input/style/udnie.jpg' width = '627px'>
<img src = 'input/content/chicago.jpg' height = '246px'>
<img src = 'output/udnie/chicago.jpg' height = '246px'>
</p>


## usage

### prequisite

[coco2014 dataset][coco] in `./data` dir.

```
data/
└── train2014/
    ├── *.jpg
    ├── .....
    ├── .....
    ├── .....
    └── *.jpg
```

[coco]: http://msvocds.blob.core.windows.net/coco2014/train2014.zip


### train

e.g.

train model using udnie style, chicago as test image, output all things in `model/udnie` dir.

```bash
$ 
```

### stylish

stylish image

```bash
$
```


stylish video


```bash
$
```

## refs

This project heavily borrow the code from project [lengstrom/fast-style-transfer][fast] but using tf v2 and keras model.

This implementation is based on
- [supplementary material][supplementary] of Justin's paper [Perceptual Losses for Real-Time Style Transfer and Super-Resolution][origin]
- Gatys' wonderful idea [A Neural Algorithm of Artistic Style][gaty]
- Ulyanov's [Instance Normalization: The Missing Ingredient for Fast Stylization][instance]

also, [tensorflow official site][tf tutorial] and [Justin's ppt in cs20si][ppt] help.


[tf tutorial]: https://tensorflow.google.cn/tutorials/generative/style_transfer
[fast]: https://github.com/lengstrom/fast-style-transfer
[origin]: https://cs.stanford.edu/people/jcjohns/eccv16/
[supplementary]: https://web.eecs.umich.edu/~justincj/
[gaty]: https://arxiv.org/abs/1508.06576
[ppt]: ./paper/06_00_slides.pdf
