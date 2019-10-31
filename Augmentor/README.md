# Augmentor in action

Image augmentation for machine learning experiments.

## installation

```pip3 install scikit-image==0.15.0 Augmentor opencv-python==3.4.3.18 ```

## usage

initialization

```imgaugAugmentor = ImgaugAugmentor(None)```

images augmentation

```aug_image = imgaugAugmentor.aug_image(image)```

bounding boxes augmentation

```aug_image, aug_bboxes = imgaugAugmentor.aug_image_and_bbox(image, bboxes_labels)```

masks augmentation

```aug_image, aug_segmap = imgaugAugmentor.aug_image_and_mask(image, segmap, num_classes)```

keypoints augmentation

```aug_image, aug_keypoints = imgaugAugmentor.aug_image_and_keypoint(image, keypoints)```

heapmaps augmentation

```aug_image, aug_heapmap = imgaugAugmentor.aug_image_and_heapmap(image, heapmap)```

## reference

* [Augmentor](<https://github.com/mdbloice/Augmentor>)
* [Augmentor-doc](http://augmentor.readthedocs.io)

