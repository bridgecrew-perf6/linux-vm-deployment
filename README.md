# linux-vm-deployment

Steps to follow

1. Run `sudo ./setup.sh master`
2. This setup will only set the server for production environment.In order to set this for development we can add that statement in the file or we can do that after logging into chatwoot server.

If we are using this locally, change `database.yml` since it finds a db on a port.

To setup develepment environment.

1. sudo -i -u chatwoot
2. cd chatwoot.
3. run `rails db:create` and `rails db:reset`.

we can find the app on `localhost:3000`

In order to remove chatwoot, please follow (this.)[https://github.com/chatwoot/docs/issues/109]
