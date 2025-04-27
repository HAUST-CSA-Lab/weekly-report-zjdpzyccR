# Weekly_Report
HAUST-CSA-Lab Weekly Report Submission Office

## 周报提交指北

1.   克隆仓库到本地

      a. **创建ssh key，用于ssh方式克隆github代码。** （如果未配置过）在电脑上合适的位置新建一个文件夹，在文件夹下打开终端使用`ssh-keygen -t rsa -b 4096 -C "你的邮箱"`（把“你的邮箱”替换成）命令，创建ssh key，下面的选项全部直接敲回车即可。 随后使用 `cat ~/.ssh/id_rsa.pub` 命令查看生成的公钥，并完整的复制下来。 在github仓库界面点击自己的头像，选择 settings 。进入到设置页面后，点击左侧的 SSH and GPG keys 选项。点击 New SSH key 选项，并将复制下来的内容粘贴上去，添加该 ssh key 的描述。随后点击 Add SSH key ，并一路点击确认即可

​	    b. **点击醒目的绿色`code`按钮，选择ssh，复制链接**      并在终端运行命令				`git clone "链接"` 即可。

2. 把周报的文件放到克隆下来的目录中

3. （假如你是第一次使用）运行`git config --global user.email "you@example.com"`和`git config --global user.name "Your Name"`命令。（分别是你创建github账号使用的邮箱和你的github名字）

   
4. 在仓库的根目录（Weekly_Report-yourname）下运行 `git add .;` `git commit -m "班级+姓名+第x周周报";` `git push`命令，即可完成提交。

注：周报的格式不作要求，清楚说明内容即可。尽量不要出现背书内容（指复制资料/ai助手的大段文字）。但也不要过于简洁，可以说说自己对某个知识点的理解和感悟。

周报提交时间在每周日24：00前。`连续两周未提交周报`和`连续超过两次隔一周交一次周报`者，视为自愿退出实验室。同时，如后期有名额有限的任务，则以周报质量为依据安排，请大家务必重视。

期待大家学有所得。
