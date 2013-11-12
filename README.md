Railscast sm-rc163
==================

self-referential
```
If one model is associated with itself. for ex user is associated with another user 
```
git clone
```
git clone https://github.com/sweetymehta/sm-rc163.git
```
instead of making extra actions in user controller for add or remove friend 
```
make a another model for following reason
1. making Rest standards clean(keeping on;y standard 7 action)
2. add_friend should belong to its controller
3. And also we want to add or remove multiple resource not single
```
see user.rb and friendship.rb
```
association for self-referencential
```
see user/show.html.erb
```
implementation of association
```
rails server
```
rails s
```
rails console
```
rails c
```
