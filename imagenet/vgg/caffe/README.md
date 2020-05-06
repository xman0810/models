# vgg

https://github.com/BVLC/caffe/wiki/Model-Zoo#models-used-by-the-vgg-team-in-ilsvrc-2014

- VGG_ILSVRC_16_layers.caffemodel, download from below link

  `http://www.robots.ox.ac.uk/~vgg/software/very_deep/caffe/VGG_ILSVRC_16_layers.caffemodel`

- VGG_ILSVRC_16_layers_deploy.prototxt goes here

  `https://gist.github.com/ksimonyan/211839e770f7b538e2d8#file-vgg_ilsvrc_16_layers_deploy-prototxt`

- Accuracy:
  - 16-layer: 7.5% top-5 error on ILSVRC-2012-val, 7.4% top-5 error on ILSVRC-2012-test
  - 19-layer: 7.5% top-5 error on ILSVRC-2012-val, 7.3% top-5 error on ILSVRC-2012-test

- Preprocess
  - the following BGR values should be subtracted: [103.939, 116.779, 123.68].
