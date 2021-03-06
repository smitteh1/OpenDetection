<h1 align="center">Open Detection 2</h1>
    <p align="center">
    <a href='https://github.com/smitteh1/OpenDetection3'>Open Detection 3 is coming!</a><br>
    <img src='https://img.shields.io/badge/OpenCV-2.4.10-violet'></img>
    <img src='https://img.shields.io/badge/Build-partial-yellow'></img>
    <img src='https://img.shields.io/badge/Dependencies-out%20of%20date-red'></img>

  </p>
<h3 align="center">Open source software that allows you to detect multiple types of objects and interact with the world using computer vision.</h3>

# Detection Methods
| Detection Method   | Header File       | Dependent Files                                       |
|--------------------|-------------------|-------------------------------------------------------|
| Finger Detection   | FingerDetection.h | VideoFeed.h / ImgProc.h                               |
| Face Detection     | FaceDetection.h   | VideoFeed.h / ImgProc.h                               |
| Face Tracking      | FaceTracker.h     | VideoFeed.h / ImgProc.h, FaceDetection.h, Cascade.xml |
| Face Recognition   | FaceReco.h        | VideoFeed.h / ImgProc.h, FaceDetection.h, Cascade.xml |
| Object Tracking    | ObjTracker.h      | VideoFeed.h / ImgProc.h, ObjCascade.xml               |
| Object Recognition | ObjReco.h         | VideoFeed.h / ImgProc.h, ObjTracker.h, ObjCascade.xml |

- More to come!

# Dependencies
- OpenCV (2.4.10)


# Systems Tested For
- Windows 32Bit (AMD)
- Windows 64Bit (Intel)
- Ubuntu 64Bit (Intel)
