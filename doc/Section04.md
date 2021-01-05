# Section04: BitBucket

<a id = "contents">

# Contents
* [BitBucket Architecture](#Architecture)
* [BitBucket - Practical LAB](#lab)

### Pickup
* [AWS Management Console](https://github.com/Pippippi3104/2020_DevOps_CICDwithJenkinsAnsibleDockerKubernetes/blob/main/doc/Section02_CICDpipeline.md#1st--aws-management-console)


<a id = "Architecture">

## BitBucket Architecture
* ![Image](../src/images/Section04/init001.png)


<a id = "lab">

## BitBucket - Practical LAB
* ![Image](../src/images/Section04/lab001.png)
* ![Image](../src/images/Section04/lab002.png)
* ![Image](../src/images/Section04/lab003.png)
* ![Image](../src/images/Section04/lab004.png)
* ![Image](../src/images/Section04/lab005.png)
* ![Image](../src/images/Section04/lab006.png)
* ![Image](../src/images/Section04/lab007.png)
* ![Image](../src/images/Section04/lab008.png)
* ![Image](../src/images/Section04/lab009.png)
* ![Image](../src/images/Section04/lab010.png)
* ![Image](../src/images/Section04/lab011.png)
* ![Image](../src/images/Section04/lab012.png)
* ![Image](../src/images/Section04/lab013.png)
* ![Image](../src/images/Section04/lab014.png)
* ![Image](../src/images/Section04/lab015.png)
* ![Image](../src/images/Section04/lab016.png)
* ![Image](../src/images/Section04/lab017.png)
* ![Image](../src/images/Section04/lab018.png)
* ![Image](../src/images/Section04/lab019.png)
* ![Image](../src/images/Section04/lab020.png)
* ![Image](../src/images/Section04/lab021.png)

* commands
  ```
  git clone https://SatoshiShimamura@bitbucket.org/SatoshiShimamura/devops-pipeline-project.git
  (pass: UmXWhR6R29G6Rrw49Ycb)
  ls -l
  ```
  ```
  cd devops-pipeline-project
  ls -la
  git config user.name SatoshiShimamura
  git config user.email origamistfrancais@gmail.com
  git remote -v
  ```
  * push までの流れ
  ```
  vi README.md
  git add .
  git status
  git commit -m "devops project code updated"
  git push origin master (UmXWhR6R29G6Rrw49Ycb)
  ```
  * Branchを切る
  ```
  git branch
  git branch feature
  git checkout feature
  vi README.md
  git add .
  git status
  git commit -m "code modified"
  git push origin feature (UmXWhR6R29G6Rrw49Ycb)
  ```

### [Return to Contents](#contents)