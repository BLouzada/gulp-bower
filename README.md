# gulp-bower

Demonstração da utilização do bower overrides junto com gulp
From stackoverflow:
https://stackoverflow.com/questions/41329043/whats-resolutions-and-overrides-in-a-bower-json-file
Overrides

Overrides section is used to override the file(s) references when pointing to dependent library.

Task runners in most cases use the bower configuration library metadata to inject links to these libraries into a page's content. When we want to inject a bootstrap link into a page, we do not need to go into the "bower_components" folder, find the package, and investigate the file content. We can use the component metadata to find the main, injectable file reference.

-Rodando o projeto
*Npm install
*./node_modules/.bin/bower install
*./node_modules/.bin/gulp