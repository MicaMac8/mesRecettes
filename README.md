:construction_worker:
# Mica boilerplate

### description :dog:
This is a boilerplate with an [atomic design](http://atomicdesign.bradfrost.com/) inspired file structure. It uses [Jade](https://pugjs.org/api/getting-started.html) (Pug) as template engine and [Sass](http://sass-lang.com/) (scss) as preprocessor. Ready for [Prepros](https://prepros.io/) compiler.

### Recommended Settings :panda_face:

* Compiler : [Prepros](https://prepros.io/) (remove *prepros.cfg* if you don't use Prepros compiler)

* template engine : [Jade (Pug)](https://pugjs.org/api/getting-started.html)  

##### CSS
* preprocessor : [Sass](http://sass-lang.com/)  
* [PostCSS](http://postcss.org/) : [Autoprefixer](https://autoprefixer.github.io/)    
* reset : normalize.scss (modifie *app/base/_normalize.scss*)  
* Style guides : [SMACSS](https://smacss.com/)
* Linter (atom) : [sass-lint](https://atom.io/packages/linter-sass-lint)  

##### JS    
* Style guides : [Standard Happiness](https://github.com/JedWatson/happiness) (with ";")  
* Linter (atom) : [js-standard](https://github.com/ricardofbarros/linter-js-standard) (Happiness)  

* Libraries :  
  * [jQuery](https://jquery.com/) ([jQuery Core 3.1.1.min](https://code.jquery.com/) is loaded in *app/templates/layout.jade*)  
  * [Event Emitter](https://github.com/asyncly/EventEmitter2) (*app/vendors/eventemitter2.js*)  
