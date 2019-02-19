# AspNetCoreVueBoilerplate

Easy to use boilerplate with vue-cli support built in (Thanks to [aspnetcore-vueclimiddleware](https://github.com/EEParker/aspnetcore-vueclimiddleware))

## Project setup

Go to the `ClientApp` directory, you can initialize a new vue project here using the vue-cli tool (if you don't like my configuration for example). The default ClientApp vue configuration is as follows:

- Babel
- TypeScript
- Progressive Web App (PWA) Support
- Router
- Vuex
- CSS Pre-processors
- Linter / Formatter

Once you're happy with your configuration install the required npm modules by using the following command in the `ClientApp` directory.

```
npm install
```

## Run the project

You can run the project through Visual Studio by opening the `AspNetCoreVueBoilerplate.sln` file and press the `F5` key.

Alternatively if you don't want to use Visual Studio you can enter the `AspNetCoreVueBoilerplate` directory and run the following command.

```
dotnet run AspNetCoreVueBoilerplate
```

Then you can go to `http://localhost:5000/` to view the app.
*NOTE:* If you enable SSL in your development environment you will not be able to use hot module replacement.

## Swagger

The project uses [Swashbuckle.AspNetCore](https://github.com/domaindrivendev/Swashbuckle.AspNetCore) to generate a Swagger/OpenAPI specification. You can also use the Swagger UI by going to the `/swagger/` route.
