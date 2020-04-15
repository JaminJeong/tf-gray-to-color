# gray2color

## pix2pix

## Data Augmentation
```bash
$ bash data_augmentation.sh
```
## Train
```bash
$ bash pix2pix-gray2color.sh
```

## Result
```bash
$ ls output
epoch_0.jpg
....
epoch_100.jpg

```

![human_gray_origin_generation](./images/result.jpg)

## test
```bash
$ bash inference.sh
$ ls generate_image

```

![flower_gray_origin_generation](./images/epoch_148.jpg)


### Reference
 - https://www.tensorflow.org/tutorials/generative/pix2pix
 - https://phillipi.github.io/pix2pix/
