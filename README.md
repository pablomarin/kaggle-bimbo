# kaggle-bimbo
This repo shows a Data Science process specifically for the Kaggle Bimbo competition:

https://www.kaggle.com/c/grupo-bimbo-inventory-demand

In this competition, Grupo Bimbo invites Kagglers to develop a model to accurately forecast inventory demand based on historical sales data. Doing so will make sure consumers of its over 100 bakery products aren’t staring at empty shelves, while also reducing the amount spent on refunds to store owners with surplus product unfit for sale.

Steps to download the repo in local git:

1) In your local folder Kaggler/Bimbo: sudo git init

2) git config --global user.email "xxx@xxx.com"

3) git config --global user.name "Your name"

4) sudo git remote add origin https://github.com/pablomarin/kaggle-bimbo.git

5) git remote -v

6) sudo git clone https://github.com/pablomarin/kaggle-bimbo.git or sudo git pull origin master

7) cd input-data/

8) sudo wget https://s3.amazonaws.com/bbts-kaggle/bimbo/cliente_tabla.csv

9) sudo wget https://s3.amazonaws.com/bbts-kaggle/bimbo/producto_tabla.csv

10) sudo wget https://s3.amazonaws.com/bbts-kaggle/bimbo/sample_submission.csv

11) sudo wget https://s3.amazonaws.com/bbts-kaggle/bimbo/test.csv

12) sudo wget https://s3.amazonaws.com/bbts-kaggle/bimbo/town_state.csv

13) sudo wget https://s3.amazonaws.com/bbts-kaggle/bimbo/train.csv

14) Once the project is downloaded completely, then: git add .

15) git commit -m "message"

16) git push -u origin master
