connect\_router
===

Connect 1.x had this nifty little sinatra-style router accessible as `connect.router`.
For some reason it was removed in Connect 2.x.

`connect_router` is the code router code from connect 1.8.6 that makes it easy to unbreak your connect apps without changing functionality.

    var connect = require('connect')
      ;

    connect.router = require('connect_router');
