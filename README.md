# models
models for cvitek-mlir test

## fetch all models

  ```sh
  $ curl -s https://packagecloud.io/install/repositories/github/git-lfs/script.deb.sh | sudo bash
  $ sudo apt-get install git-lfs

  $ export GIT_LFS_SKIP_SMUDGE=1
  $ git clone https://github.com/cvitek-mlir/models.git
  $ cd models
  $ git lfs install
  $ git lfs fetch --all
  ```

