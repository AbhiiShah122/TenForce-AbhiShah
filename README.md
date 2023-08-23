# TenForce-AbhiShah
Exercise 1: Completed.

Exercise 2: Below are a few other ways to implement the mentioned problem statement.

1) Instead of using the ".Result" we should use the async-await to handle the unexpected errors. (Implemented in the provided solution)
2) We are invoking the "GetAllPlanets()" multiple times instead we can store the data in a variable. (Implemented in the provided solution)
3) To retrieve "MoonDto" data we can call the "Task.WhenAll()" to retrieve it in async. (Implemented in the provided solution)

Here, With the above-mentioned improvements the execution time of the service is dropped from **~110 seconds** to **~80 seconds**.
