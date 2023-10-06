# Installation 

```conda install -c "conda-forge/label/broken" rasterio ```

``` conda install -c anaconda scikit-image  ```

# Add LoadImageFromFileAzuriaGeo  to transforms/loading.py

```anaconda3/envs/openmmlab_env/lib/python3.8/site-packages/mmcv/transforms/loading.py```

# Add LoadImageFromFileAzuriaGeo to Registry 

``` anaconda3/envs/openmmlab_env/lib/python3.8/site-packages/mmcv/transforms/__init__.py ```

# Uncomment Resizing method of opencv ligne 115-118 in geometric.py

``` anaconda3/envs/openmmlab_env/lib/python3.8/site-packages/mmcv/image/geometric.py ```