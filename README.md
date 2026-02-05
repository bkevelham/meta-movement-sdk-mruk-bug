# Movement SDK tracking bug when used in combination with MRUK

This repository exists in support of an issue reported on the Meta Movement SDK repository: https://github.com/oculus-samples/Unity-Movement/issues/130

What we noticed is that when taking the headset off and putting it back on, body tracking data no longer aligns with the body when the scene also contain an [MRUK](https://developers.meta.com/horizon/documentation/unity/unity-mr-utility-kit-overview/) prefab. The scenes in the repository serve to reproduce the issue. 
