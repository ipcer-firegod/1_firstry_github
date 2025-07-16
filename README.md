# 1_firstry_github
1_firstry_github in github. I create this in github, and then I will clone it in vscode.

## 流程说明

### 1_在vscode中进行以下
1.在github上创建了一个新仓库 1_firstry_github

2.在vscode中的源代码管理中“克隆仓库”，出现问题：
fatal: unable to access 'https://github.com/ipcer-firegod/1_firstry_github.git/': SSL certificate problem: unable to get local issuer certificate

3.在github中复制ssh。cd到D:\CSProgrom\Semester\2_Sophomore\Second_sem\Git\1_firstry中，
手动git clone git@github.com:ipcer-firegod/1_firstry_github.git，成功

4.vscode中源代码管理“打开文件夹”，打开刚才克隆的文件夹。
克隆的是 1_firstry_github ，打开的是 上一级目录 1_firstry

5.保存以上至此的更改。输入提交消息，“提交”，“同步更改”

### 2_在github中进行以下
1.“同步更改”成功，github上出现vscode中的更改。
（注意，之前的尝试中“同步更改”失败过，暂时不清楚具体原因，推测可能是加速、安全软件、github本身等原因）

2.现在在github中更改了文件，等下进入vscode中查看。
保存，依旧需要提交消息

### 3_在vscode中进行以下
1.github上有更改后，vscode中的本地仓库会出现“同步更改”（拉取），进行后即可同步github上的更改

3.为再次确保正常、以及查看推送、拉取、同步等操作，此次更改结束后，再进入github网站中进行结束

### 4_在github中进行以下
1.调整位置，将3中的结尾部分放在4的结尾

2.现在推测：
vscode中，更改文件后，输入提交消息后，进行一次“提交”，即是一次版本，在左侧可以观察到前面每次的提交（不论是在vscode中还是github中）
然后“同步更改”，则可将更改“推送”（推测的）到github中去。即vscode中“同步更改”=“推送”。
github中，同样如此，更改文件后，需要进行一次“提交”。

0.大概可以完成此次尝试，流程基本结束。
条件为：Steam++的加速github没有开启，安全软件没有关闭，github使用的是镜像网站bgithub.xyz。
（现在推测，直接“克隆仓库”是从github本站进行克隆http，手动克隆http也不会行；镜像网站上的http和本站不一样，应该可以使用。而ssh在两个网站上都是一样的。）

### 5_在vscode中进行以下
1.同步更改（从 origin/main 中拉取一个提交）。
在github中更改后，进入vscode就有提示可以进行“同步更改”了。应该是之前打开的始终“git fetch”导致的。
询问ai后，得知有关设置。

2.分支、存储、标记等功能暂未尝试。
此次尝试到此为止