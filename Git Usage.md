#### Git Usage
###### 1. Always pull
```
$ git pull
```


###### 2. Make sure you are on the branch master
```
$ git checkout master
```


###### 3. Branch a new feature when you want to develop something
```
$ git branch feature-xxx
```


###### 4. Checkout to the branch and start working
```
$ git checkout feature-xxx
```


###### 5. Every time you achieve something, commit it
```
$ git add the/path/of/sth/1.rb
$ git add the/path/of/another/sth/2.scss 
$ git commit -m 'Finish the component xxx-yyy functionally'
```


###### 6. When you finish everything, push and go back to master
```
$ git push
$ git checkout master
$ git pull # fetch up the latest progress on master
$ git merge --no-ff feature-xxx # merge master with the branch you just finished
```


###### 7. Sometimes there exists conflicts, then you have to fix it one-by-one. After merging, push it
```
$ git push
```


###### 8. After everything is done, delete the branch
```
$ git branch -d feature-xxx
```


###### 9. And repeat things above again and again
