# Version control for D2P&O
Version control Design-to-Robotic-Production and -Operation projects

## A hybrid approach
Version control for software development can be done easily with git, meant to be used to do version control on source code, being the compiled binaries and executables an outcome from the source code that is not tracked by version control systems like git. However git has some limitations when it comes to version 3D models and visual programming scripts developed in software like Rhino, as these format are binary files, which are often also quite large.

### Options to deal with binary files and large files
So far we have explored the following options:
1. Git LFS (Git Large File Storage)
2. DVC (Data version control)
3. Speckle 

### Learnings and recommendations
- Git LFS is the easiest solution to adopt and use for beginners.
- DVC is very powerful but requires more in depth knowledge of git and requires more infrastructural considerations. Git LFS is a more out of the box solution compared to DVC which is more flexible.
- Speckle is a great complement to do version control on 3D models.


## References