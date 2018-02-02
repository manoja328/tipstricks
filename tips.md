sudo adduser <username>
 
You can read more about this command in the man pages of your system with man adduser.
 
You can then add a user to the sudo group with with the command:
 
sudo adduser <username> sudo

----------------------------



if there is hotname eroor go to 

/etc/hosts and set hostname


----------------------------


if ssh connection refused go install 

openssh-server


---------------------------------

zip -r compressed_filename.zip foldername  # to compress a folder

----------------------------------------


hit ctrl + f5 to reload cache in any website in chrome


--------------------------------------------------------------
http://uoa-eresearch.github.io/eresearch-cookbook/recipe/2014/11/20/conda/

conda info -e

conda create -n yourenvname

 -- conda create -n yourenvname python=x.x---

source activate yourenvname

source deactivate

conda remove -n yourenvname --all

-----------------------------

aws configure

aws s3 ls s3://mydatacollect/valimages/

aws s3 sync . s3://mydatacollect/valimages/ --acl public-read

aws s3 sync . s3://mydatacollect/valimages/ --acl public-read --follow-symlinks


