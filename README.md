# Movie API Gateway Service

## How to run it
- install [.NET](https://dotnet.microsoft.com/download)
- clone the repository
- go into the cloned directory and run the following command: 
`dotnet run`

## How to add more routes
All you need to edit is `ocelot.json`. Under the Routes key, append the list with the new routes. For more information check out the [ocelot documentation](https://ocelot.readthedocs.io/en/latest/introduction/gettingstarted.html).

Adaptations to the routes might be needed as part of the setup (such as setting up the correct addresses and ports).