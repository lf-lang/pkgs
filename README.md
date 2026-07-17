# Packages of Reactors for Lingua Franca

Lingua Franca packages contain reusable reactor class definitions.
Each package lives in its own GitHub repository and contains importable reactor classes plus some demo programs using these classes.

To use a package, clone the repo into your `lf-packages` directory in the root of your project or into
the directory pointed to by your `LF_PACKAGES` environment variable.
For example, for the `video-py` package:

```
git clone https://github.com/lf-lang/video-py.git
```

Alternatively, if your project is in a git repo, create a submodule:

```
git submodule add https://github.com/lf-lang/video-py.git
```

Then import the library reactors. For example:

```
import WebCam, VideoDisplay from <video-py>
```

## C Target Packages

- [MQTT publisher and subscriber](https://github.com/lf-lang/mqtt-c)
- [MuJoCo physics-based simulation](https://github.com/lf-lang/mujoco-c)

## CCpp Target Packages
- [Gazebo simulator](https://github.com/lf-lang/gazebo-ccpp)

## Python Target Packages
- [Edge AI library](https://github.com/lf-lang/edgeai-python)
- [Video and object detection](https://github.com/lf-lang/video-py)
