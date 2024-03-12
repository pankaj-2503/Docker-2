
### Docker commands - :)

-- docker run (whatever you want to run)
 -- port mapping command - docker run -p 27017:27017 mongo
  -- checking status - docker ps
   -- run in detached mode - docker run -d -p 27017:27107 mongo
    -- docker kill (whatever running)
     -- for postgress - docker run -e POSTGRES_PASSWORD=mysecretpassword -d -p 5432:5432 postgres

      -- docker images (shows all images that you have on your machines)
       -- docker ps (shows all containers on your machine)
        -- docker run -d mongo (running detached mode)
         --  docker rmi (ro remove images)
           --  docker exec - (to execute a command inside a container)
