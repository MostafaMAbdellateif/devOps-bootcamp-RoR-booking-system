# Adding Ticket

1. Created new ticket using
```shell
rails g scaffold Ticket name:string reference:integer price:float     
```
2. Migrate the db to create/use the new db table (tickets) using
```shell
bin/rails db:migrate RAILS_ENV=development
```
3. Run the server using
```shell
rails s
```