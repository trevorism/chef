#Chef Server

    https://trevor-chef-server.eastus.cloudapp.azure.com

The .chef folder is not checked in and can be downloaded from 
    
    https://trevor-chef-server.eastus.cloudapp.azure.com/organizations/trevorism/getting_started

Cookbooks
---------
A cookbook is the fundamental unit of configuration and policy distribution. A sample cookbook can be found in `cookbooks/starter`. After making changes to any cookbook, you must upload it to the Chef server using knife:

    $ knife upload cookbooks/starter

For more information about cookbooks, see the example files in the `starter` cookbook.

Roles
-----
Roles provide logical grouping of cookbooks and other roles. A sample role can be found at `roles/starter.rb`.



