# make sure to run in root/sam-app-py directory!!!
# TODO: Import your own library!
# use the code you built in boto_utils to create a easy library that you can use with your serverless function
# this will teach you how to use Makefiles to import your own library from any kind of runtime
# theoretically you could import any binary. Not just Python! It could be any other version of python (even 2.7)
# you can precompile libraries not natively supported in the cloud. This is a real game changer for development.
# with this make file you can pull any dependencies you want in you local environment and push it to production
# what will happen upon every sam build is that SAM will run this make file and precompile it into a layer.
# this layer will show up like an imported library in your app file.

# let's break down what you have to do:
# 1. Make a directory called "python" (it's good practice since, as your projects get larger, you can start to build with several other languages)
# 2. Copy all the python files you need. You can just copy all of them if you like ;)
# 3. Copy your credential files. This library is it's own little module. It doesn't have access to production IAM settings
# 4. export the home directory for this particular layer to be the newly created "python" directory
# HINT: Makefiles work kind of like bash scripts. Available to you are commands like mkdir, export, and cp
# HINT: $(ARTIFACTS_DIR) is an environment variable that resolves to this "layers" personal directory. That'll be your " working directoy for the layer.
# HINT: $(PWD) is the current path relative to your develpoment environment. You can use this variable to locate your files.
build-CustomLayer:
    ### YOUR CODE HERE ###
