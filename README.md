# CameraTransform

[![DOC](https://readthedocs.org/projects/cameratransform/badge/)](https://cameratransform.readthedocs.io)
[![test](https://github.com/rgerum/cameratransform/actions/workflows/test.yml/badge.svg)](https://github.com/rgerum/cameratransform/actions/workflows/test.yml)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![DOI](https://img.shields.io/badge/DOI-10.1016/j.softx.2019.100333-blue.svg)](https://doi.org/10.1016/j.softx.2019.100333)


CameraTransform is a python package which can be used to fit camera transformations and apply them to project points
from the camera space to the world space and back.

For installation and usage please refere to the [Documentation](http://cameratransform.readthedocs.org/).

v1.2.1.2 by Streetscope, 23-Sep-2026 modified from fork of repo:
https://github.com/rgerum/cameratransform
branch: main
commit: e85578d
https://github.com/rgerum/cameratransform/commit/e85578daa6651542ae1ee1df37152ebae709c5c8

Modifications to pyproject.toml to get the __init__.py file when installing forked repo with pip.
Inserted the following lines into pyproject.toml:
[tool.hatch.build.targets.wheel.force-include]
"cameratransform/__init__.py" = "cameratransform/__init__.py"
