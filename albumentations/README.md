# albumentations in action

Image augmentation for machine learning experiments.

## installation

```pip3 install scikit-image albumentations==0.3.2```

## usage

initialization

```albuAugmentor= AlbumentationsAugmentor(None)```

images augmentation

```aug_image = albuAugmentor.aug_image(image)```

bounding boxes augmentation

```aug_image, aug_bboxes = albuAugmentor.aug_image_and_bbox(image, bboxes_labels)```

masks augmentation

```aug_image, aug_segmap = albuAugmentor.aug_image_and_mask(image, segmap)```

keypoints augmentation

```aug_image, aug_keypoints = albuAugmentor.aug_image_and_keypoint(image, keypoints)```

## reference

* [albumentations](<https://github.com/albu/albumentations>)
* [albumentations-doc](https://albumentations.readthedocs.io/en/latest/)

