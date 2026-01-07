# Defold (web engines benchmark)

This project is meant for evaluating the features and capabilities of the Defold engine. It's built on top of the Defold sample project [***Roids***](https://github.com/defold/sample-roids) (a basic 2D shooter game), to which we added CI and some extras to learn more about the engine.

> This repository is part of our web engines benchmark. [See the *Unity* project](https://github.com/hg-argo/web-engines-benchmark) for reference.

[-> Web version of the project](https://hg-argo.github.io/web-engines-benchmark) (hosted on GitHub Pages through CI)
[-> Original sample project repository](https://github.com/defold/sample-roids)

## Content

![Gameplay preview](./roids.gif)

We used this project to try the features of the engine, and check how we can deploy such project. Here is a list of the elements changed from the original project:

- CI workflow to release the game for PC, Mac and Web

## Side notes

The editor and approach of Defold on development is very interesting, and that's why we added it as a candidate for our benchmark. The engine is very good for 2D projects, but it turns out that it's not really appropriate for 2D projects. That's the reason we explored the solution, but not by making the expected reference project.