# SLIDE 

We post all updates to SLIDE Project here. 

To update submodules: 
1. `$ git submodule init`
2. `$ git submodule update`
3. To update the HashingDeepLearning repo cd into its directory and run `$ git pull origin master` and commit the result, to update the SLIDE_opt_ia repo cd into its directory and run `$ git pull origin prv_opt_ia` and commit the result.

## Links to Repositories 
1. The original slide code [MLSys 2020](https://arxiv.org/abs/1903.03129) can be found [here](https://github.com/keroro824/HashingDeepLearning).
2. The optimized slide [MLSys 2021](https://proceedings.mlsys.org/paper/2021/file/3636638817772e42b59d74cff571fbb3-Paper.pdf) code can be found [here](https://github.com/IntelLabs/SLIDE_opt_ia). Please note this requires ICC compiler. Refer to README.Intel.md file in the repository. 
3. Negative Sampling [ICML 2021](http://proceedings.mlr.press/v139/daghaghi21a/daghaghi21a.pdf) code can be found [here](https://github.com/RUSH-LAB/NegativeSampling). Please note this requires ICC compiler. 


## Commercial Grade Software and Python Bindings
Please check out https://thirdai.com/bolt for commercial implementations, python bindings, of these ideas and extentsions to other applications.  The software does not have any compiler dependencies and can be used on any CPU (AMD, ARM, Intel) 
