# PyTorch Conflict Groups Test Fixture

This fixture tests issue #265: handling conflict groups with resolution-markers that use `extra == 'group-...'` markers.

The issue occurs when uv generates resolution-markers with internal extras markers like `extra == 'group-10-pytorch-conflict-groups-cpu'` which need to be evaluated correctly.
