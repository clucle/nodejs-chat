# nodejs-chat
nodejs chat

if i use mongo db

enter cmd

and create data folder
  (C:\data)
  
and make mongod.cfg  path mongodb


  this is my mongod.cfg

    ##Which IP address(es) mongod should bind to.
    bind_ip = 127.0.0.1

    ##Which port mongod should bind to.
    port = 27017

    ##I set this to true, so that only critical events and errors are logged.
    quiet = true

    ##store data here
    dbpath=C:\data\db

    ##The path to the log file to which mongod should write its log messages.
    logpath=C:\mongodb\log\mongo.log

    ##I set this to true so that the log is not overwritten upon restart of mongod.
    logappend = true

    ##log read and write operations
    diaglog=3

    ##It ensures write durability and data consistency much as any journaling scheme would be expected to do.
    ##Only set this to false if you don’t really care about your data (or more so, the loss of it).
    journal = true
    
    
and path mongodb/bin  and mongod
  (C:\mongodb\bin>mongod) <- in my window
  
and node app!
  
