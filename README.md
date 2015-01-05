# chef-zero

## setup

    $ bundle install --path=vendor/bundle

## bootstrap

    $ bundle exec knife zero bootstrap -i ~/.vagrant.d/insecure_private_key 192.168.33.10

## node list

    $ bundle exec knife node list

## chef_client

    $ bundle exec knife zero chef_client 'name:localhost' --attribute ipaddress

execute all nodes

    $ bundle exec knife zero chef_client 'name:*' --attribute ipaddress
