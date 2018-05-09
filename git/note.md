#  1 git 取消对文件的跟踪
  git rm --cached file

  git 取消对文件夹的跟踪
  git rm -r --cached dir

# 打tag
  git tag -a v1.0 -m 'message'

  推送tag
  git push  --tags