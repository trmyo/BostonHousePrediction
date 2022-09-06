## BostonHousePrediction

### Software And Tools Requirements

1. [Github Account](https://github.com)
2. [HerokuAccount](https://heroku.com)
2. [VSCodeIDE](https://code.visualstudio.com/)
4. [GitCLI](https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control)

Create a new environment using

'''
cond create -p bostonHouse python==3.7 -y
'''

Activate the environment

'''
conda activate bostonHouse
'''

To install required libraries

'''
pip install -r requirements.txt
'''

To configure git account if already configured
'''
git config --global user.name
'''

if not configured then
'''
git config --global user.name "trmyo"
'''

To configure email of github
'''
git config --global user.email "trmyo@yahoo.com"
'''

To commit changes in Github repository
1. "git add ."   # adding all files 
2. "git status"   # to check the status of files
3. "git commit -m "First Commit"
4. "git push origin main"  # to push to main branch

