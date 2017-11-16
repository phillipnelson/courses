# Practical Deep Learning for Coders (fast.ai courses)

These are the lecture materials from [Practical Deep Learning for Coders](http://course.fast.ai/). Two important parts of the course are  [our online forums](http://forums.fast.ai/) and [our wiki](http://wiki.fast.ai/index.php/Main_Page).  If you are encountering an error, we recommend that you first search the forums and wiki for a solution.  If you can't find the answer there, the next step is to ask your question on the forums.  See this advice on [how to ask for help](http://wiki.fast.ai/index.php/How_to_ask_for_Help) in a way that will allow others to most quickly and effectively be able to help you.  Please don't use Github Issues to ask for help debugging (many questions have already been answered in the forums).

# Personal Environment

- This repo: git@github.com:phillipnelson/fastai-courses.git

```
git clone git@github.com:phillipnelson/fastai-courses.git
virtualenv ai-env
source ai-env/bin/activate
pip install -r fastai-courses/requirements.txt
mkdir ~/Data
curl http://files.fast.ai/files/dogscats.zip > ~/Data/dogscats.zip
unzip ~/Data/dogscats.zip 
```


# Remote Environment



#TODO Should be able to commit notebook changes back to personal repo:

- Save github write credentials to `~/.ssh/gh_ai_rsa.pub`


# Additional Notes

## Jupyter

- pass: dl_course

## Files

http://files.fast.ai/files/

e.g.

- Dogs cats: http://files.fast.ai/files/dogscats.zip

## GPU

- `nvidia-smi` Driver information
- `~/.keras/keras.json` Keras configuration (backend)
- `~/.theanorc` GPU, CPU


