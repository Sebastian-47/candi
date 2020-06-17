- Added debian10 compatibility
- Modified trilinos:
  - deactivated Amesos2
  - activated MUMPS (depends on ScaLAPACK)
  - adapted the md5 checksum, since trilinos itself was modified to accept 
    MUMPS as a smoother when using MueLu with ML synta
- Modified petsc:
  - added local installation path of ScaLAPACK
