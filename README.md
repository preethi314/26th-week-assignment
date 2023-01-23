# 26th-week-assignment
echo "welcome"|tee a{1..10}.txt

sudo yum install git -y
git clone git@github.com:preethi314/guvi-task-round3.git

read var1
read var2

if [ $var1 == $var2 ]
then
        cd ..
        tar -cvzf output.tar.gz task-directory/
        mv output.tar.gz task-directory/guvi-task-round3

        cd task-directory/

        cd guvi-task-round3/

        git add .
        git commit -m "adding files"
        git push origin main



else
        cd guvi-task-round3/
        git checkout -b develop

        cd ../..
        tar -cvzf output.tar.gz task-directory/
        
        tar -cvzf output.tar.gz task-directory/
        mv output.tar.gz task-directory/guvi-task-round3

        cd task-directory/

        cd guvi-task-round3/


        git add .
        git commit -m "adding files"

        git push -u origin develop
fi

-- INSERT --                                                                                                                                              

