# git学习笔记
1. git基本命令
    *  git config --global user.name "Your Name"
        *  git config --global user.email "email@example.com"
	        * 这俩个不解释，--global表示这台机器上的所有git仓库都使用这个配置
		    * git init 
		            * 使此目录变为git可以管理的目录
			        * git add "file"
				        * 将文件添加到仓库
					    * git commit -m "注释"
					            *将仓库里的文件提交到版本库
						        * git status 
							        * 查看仓库状态
								    * git diff "flie"
								            * 查看文件的改动
									        * git log 
										        * 显示最近到最远的提交记录，三次，
											    * git reset --head HEAD^
											            * 回退到上一个版本
												            * 加俩个^^表示回到上俩个版本
													            * 也可以 ~ number 回到上number个版本 
														     *其他的*
														     *以后再说*
