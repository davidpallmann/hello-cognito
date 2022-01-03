# Hello, Cognito!

This is the code project for the [Hello, Cognito!](https://davidpallmann.hashnode.dev/hello-cognito) blog post. 

This episode: Amazon Cognito. In this Hello, Cloud blog series, we're covering the basics of AWS cloud services for newcomers who are .NET developers. If you love C# but are new to AWS, or to this particular service, this should give you a jumpstart.

In this post we'll introduce Amazon Cognito and use it to secure a "Hello, Cloud" .NET web application. We'll do this step-by-step, making no assumptions other than familiarity with C# and Visual Studio. We're using Visual Studio 2022 and .NET 6.

## Our Hello, Cognito Project

We're going to create an ASP.NET MVC web application that uses Cognito for user sign-in and new user registration. We'll limit ourselves to a Cognito user pool today, and tackle federation and social identities another time. The app we'll be creating is inspired by the AWS ASP.NET Core Identity Provider for Amazon Cognito sample, updated here for .NET 6. We'll use our own application dialogs for authentication prompts. 

See the blog post for the tutorial to create this project and run it on AWS.

