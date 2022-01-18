# angular-tour-stackblitz

# Deploying an application

Deploying your application is the process of compiling, or building, your code and hosting the JavaScript, CSS, and HTML on a web server.

This section builds on the previous steps in the Getting Started tutorial and shows you how to deploy your application.

# Prerequisites

A best practice is to run your project locally before you deploy it. To run your project locally, you need the following installed on your computer:

    Node.js.

The Angular CLI. From the terminal, install the Angular CLI globally with:
          
    npm install -g @angular/cli

        
With the Angular CLI, you can use the command ng to create new workspaces, new projects, serve your application during development, or produce builds to share or distribute.

# Running your application locally

Download the source code from your StackBlitz project by clicking the Download Project icon in the left menu, across from Project, to download your project as a zip archive.
Download the stackblitz project

Unzip the archive and change directory to the newly created project. For example:

    cd angular-ynqttp

To download and install npm packages, use the following npm CLI command:

    npm install
    
Use the following CLI command to run your application locally:
  
    ng serve

To see your application in the browser, go to http://localhost:4200/. If the default port 4200 is not available, you can specify another port with the port flag as in the following example:

    ng serve --port 4201

While serving your application, you can edit your code and see the changes update automatically in the browser. To stop the ng serve command, press Ctrl+c.

# Building and hosting your application

To build your application for production, use the build command. By default, this command uses the production build configuration.
          
    ng build


This command creates a dist folder in the application root directory with all the files that a hosting service needs for serving your application.

If the above ng build command throws an error about missing packages, append the missing dependencies in your local project's package.json file to match the one in the downloaded StackBlitz project.

Copy the contents of the dist/my-project-name folder to your web server. Because these files are static, you can host them on any web server capable of serving files; such as Node.js, Java, .NET, or any backend such as Firebase, Google Cloud, or App Engine. For more information, see Building & Serving and Deployment.

# What's next

In this tutorial, you've laid the foundation to explore the Angular world in areas such as mobile development, UX/UI development, and server-side rendering. You can go deeper by studying more of Angular's features, engaging with the vibrant community, and exploring the robust ecosystem.
Learning more Angular

For a more in-depth tutorial that leads you through building an application locally and exploring many of Angular's most popular features, see Tour of Heroes.

To explore Angular's foundational concepts, see the guides in the Understanding Angular section such as Angular Components Overview or Template syntax.
Joining the community

Tweet that you've completed this tutorial, tell us what you think, or submit suggestions for future editions.

Keep current by following the Angular blog.
Exploring the Angular ecosystem

To support your UX/UI development, see Angular Material.

The Angular community also has an extensive network of third-party tools and libraries.
Last reviewed on Wed Sep 15 2021
