Fork of COCO API - [philferriere / cocoapi](https://github.com/philferriere/cocoapi)
===========================================

# This fork's README:

This fork was created to update the philferriere clone with newer commits from original repo.

Please go through the `cocodataset-master` branch of this repo to use the up to date code from original repo.

# Progress of work and installation

Commits from original repo up till commit id `8c9bcc3cf640524c4c20a9c40e89cb6a2f2fa0e9` of master branch have been
merged in this branch at the time of updating this README.

This branch has been tested for python `v3.7` on Windows 10 with Anaconda.

Sample notebooks provided may have issues unrelated to this project, but needs further investigation and work.

Python `v2.x` has been tested, but installation doesn't work.

I am accepting PRs for any fixes for 2.7, but might not end up working on it myself.

Installation should be as follows:

```
$ pip install git+https://github.com/gautamchitnis/cocoapi.git@cocodataset-master#subdirectory=PythonAPI
Collecting git+https://github.com/gautamchitnis/cocoapi.git@cocodataset-master#subdirectory=PythonAPI
  Cloning https://github.com/gautamchitnis/cocoapi.git (to revision cocodataset-master) to c:\users\<USER_NAME>\appdata\local\temp\pip-req-build-s94zepg_
  Running command git clone -q https://github.com/gautamchitnis/cocoapi.git 'C:\Users\<USER_NAME>\AppData\Local\Temp\pip-req-build-s94zepg_'
  Running command git checkout -b cocodataset-master --track origin/cocodataset-master
  Branch cocodataset-master set up to track remote branch cocodataset-master from origin.
  Switched to a new branch 'cocodataset-master'
Building wheels for collected packages: pycocotools
  Building wheel for pycocotools (setup.py) ... done
  Created wheel for pycocotools: filename=pycocotools-2.0-cp37-cp37m-win_amd64.whl size=79887 sha256=87f406db43a54ce0b7a1002d12fc3cdb702e825d257be9e3b933bf5babc5e3f3
  Stored in directory: C:\Users\<USER_NAME>\AppData\Local\Temp\pip-ephem-wheel-cache-enxlc8z4\wheels\6e\c9\59\56484d4d5ac1ab292a452b4c3870277256551505954fc4a1db
Successfully built pycocotools
Installing collected packages: pycocotools
Successfully installed pycocotools-2.0
```

Please make sure you don't have any other versions of `pycocotools` installed in your environment.

Feel free to open issues and I'll try my best to help out!
