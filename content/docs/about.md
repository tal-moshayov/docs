#About wercker
Wercker is a Docker-based platform for developing, building and
delivering your applications.  Wercker provides you with a toolchain to speed up
your development proces and allow you to build apps for the 21st century by
containerising your code and automating your development pipelines.

#Why wercker
At wercker, we believe that micro-services and Service Oriented
Architectures are the future. However, with great power comes great
responsibility and micro-services naturally introduce a lot of extra moving
parts in your application. To fully leverage the advantages of micro-services,
they should be managed carefully.

Wercker lets you do just that by setting up automated development pipelines.
Very much in the spirit of "_release early, release often_" you can
build and deploy your services with just a `git push` and let wercker work it's
magic. 

Under the hood wercker leverages Docker containers to not only provide users
with isolated environments to run code in, but also to allow pipeline
automatisation. Wercker runs your code in a container and takes it through what
we call _steps_ - scripts [developed by the community](https://app.wercker.com/#explore) - and saves the
output as a container.

Wercker also works for developers working on a website, blog or app that is not
necessaraly as complex. Because wercker is also a **workflow** and not only a
platform, you can start using wercker from the get-go with `wercker dev`. This
sets you up with a container locally and allows you to start developing in that
container, without changing your existing workflow. 

