# laravel-4.2-job-queue-example
A simple example to trigger a job queue

# how to make (Too Lazy to write)
Create a new directory as 'jobs'

File 1. App -> Start -> Global
  Inside the addDirectories function ,  put a new line by adding a comma as below.(without quotations)
	  # "app_path().'/jobs'," 
    
    2. create the job inside the jobs folder (check SendEmail class file)
    
    3. create a route and make a controller function.
      inside that ,  call the job (check Home Controller).
      
      That's all ! just call the function and test or clone this repo , go to home page and click the trigger anchor button. You will get   the example text
