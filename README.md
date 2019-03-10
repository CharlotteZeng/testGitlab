      git add . 
	  git status
	  git commit -m "测试"
	  git push
	  git pull
	  
	  git reflog
	  git log
	  #回滚上次add
	  git reset
	  #回滚到上一个版本
	  git reset --hard HEAD^
	  #回滚到上两个版本
	  git reset --hard HEAD^
	  #回滚到上100个版本
	  git reset --hard HEAD~100
	  #回滚到指定版本
	  git reset --hard bcb02877d21917876673224051fff53e467557ce
	  
	  branche1
	  change 1

                            
                            	  #将暂存区的文件拉到工作区内 使工作区未提交的更改丢失
                            	  git checkout -- <file>
                            	  
      branch1 
      测试切换分支
