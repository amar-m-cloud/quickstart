    1  sudo cat /var/lib/jenkins/secrets/initialAdminPassword
    2  mvn --version
    3  mvn
    4  sudo yum install mvn
    5  sudo yum install maven
    6  mvn
    7  mvn --version
    8  mkdir mavendemo
    9  ll
   10  cd mavendemo/
   11  ll
   12  mkdir mavenproject
   13  ll
   14  cd mv
   15  cd mavenproject/
   16  ll
   17  pwd
   18  mvn archetype:generate
   19  ll
   20  cd quickstart
   21  ll
   22  git push
   23  git init
   24  git status
   25  git add .
   26  git status
   27  git commit -m "pushing local maven project to GitHub"
   28  git config --global --edit
   29  git commit --amend --reset-author
   30  git status
   31  git remote add origin https://github.com/amar-m-cloud/quickstart.git
   32  git branch -M main
   33  git status
   34  git push -u origin main
   35  cd /var/lib/jenkins/workspace/
   36  ll
   37  cd m
   38  cd build-maven-project/
   39  ll
   40  cd target/
   41  ll
   42  cd ..
   43  sudo vi /etc/sudoers
   44  cd ..
   45  ll
   46  cd build-maven-project/
   47  ll
   48  pwd
   49  ll
   50  sudo yum install tree
   51  ll
   52  tree src
   53  ll
   54  java -cp target/quickstart-1.0-SNAPSHOT.jar com.devopsclass.App
   55  cd ..
   56  ll
   57  cd mvn-build-deploy/
   58  ll
   59  cd ..
   60  tree workspace/
   61  ll
   62  cd workspace/
   63  ll
   64  history
