Transform
#########

Here we provide dataset transformation examples such as reidentification, reindexing, label
redefinition, and tiling.

In addition to these, Datumaro provides a total of 22 transformations,
including polygon to bbox, merging segmentation masks, annotation and attribution removal, etc.
Please refer `here <https://github.com/openvinotoolkit/datumaro/blob/develop/datumaro/plugins/transforms.py>`_.

.. toctree::
   :maxdepth: 1
   :hidden:

   notebooks/05_transform
   notebooks/06_tiling

.. grid:: 1 2 2 2
   :gutter: 2

   .. grid-item-card::

      .. button-ref:: notebooks/05_transform
         :color: primary
         :outline:
         :expand:

   .. grid-item-card::

      .. button-ref:: notebooks/06_tiling
         :color: primary
         :outline:
         :expand:

      This transform is known to be useful for detecting small objects in high-resolution input images [1]_.


References
^^^^^^^^^^

.. [1] F., Ozge Unel, Burak O. Ozkalayci, and Cevahir Cigla. "The power of tiling for small object detection." Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition Workshops. 2019.
