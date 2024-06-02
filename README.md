# Exoplanet ML

Machine learning models and utilities for exoplanet science.

## Code Author

Chris Shallue: [@cshallue](https://github.com/cshallue)

## Walkthrough

You can jump straight to the [AstroNet walkthrough](exoplanet-ml/astronet/README.md#walkthrough).

Otherwise, click through to the desired directory as outlined below.

## Directories

[astronet/](exoplanet-ml/astronet/)

* A neural network for identifying exoplanets in light curves. Contains code for:
  * Downloading and preprocessing Kepler light curves.
  * Building different types of neural network classification models.
  * Training and evaluating a new model.
  * Using a trained model to generate new predictions.

[astrowavenet/](exoplanet-ml/astrowavenet/)

* A generative model for light curves.

[light_curve/](exoplanet-ml/light_curve)

* Utilities for operating on light curves. These include:
  * Reading Kepler data from `.fits` files.
  * Applying a median filter to smooth and normalize a light curve.
  * Phase folding, splitting, removing periodic events, etc.
* [light_curve/fast_ops/](exoplanet-ml/light_curve/fast_ops) contains optimized
C++ light curve operations.

[tf_util/](exoplanet-ml/tf_util)

* Shared TensorFlow utilities.

[third_party/](exoplanet-ml/third_party/)

* Utilities derived from third party code.

# Citation

If you find this code useful, please cite our paper:

Shallue, C. J., & Vanderburg, A. (2018). Identifying Exoplanets with Deep
Learning: A Five-planet Resonant Chain around Kepler-80 and an Eighth Planet
around Kepler-90. *The Astronomical Journal*, 155(2), 94.

Full text available at [*The Astronomical Journal*](http://iopscience.iop.org/article/10.3847/1538-3881/aa9e09/meta).

# Disclaimer

This is not an official Google product.
