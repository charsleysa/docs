Authenticate with Fly (and log out if you need to).
If you do not have an account, start with the `auth signup` command.
If you do have and account, begin with the `auth login` subcommand.

## Usage

~~~
flyctl auth [command] [flags]
~~~

## Available Commands
* [docker](/docs/flyctl/auth-docker/)	 - Authenticate docker
* [login](/docs/flyctl/auth-login/)	 - Log in a user
* [logout](/docs/flyctl/auth-logout/)	 - Logs out the currently logged in user
* [signup](/docs/flyctl/auth-signup/)	 - Create a new fly account
* [token](/docs/flyctl/auth-token/)	 - Show the current auth token
* [whoami](/docs/flyctl/auth-whoami/)	 - Displays the users email address/service identity currently 
authenticated and in use.


## Options

~~~
  -h, --help   help for auth
~~~

## Global Options

~~~
  -t, --access-token string   Fly API Access Token
  -j, --json                  json output
      --verbose               verbose output
~~~

## See Also

* [flyctl](/docs/flyctl/help/)	 - The Fly CLI

