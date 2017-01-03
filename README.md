:construction_worker:
# Ted boilerplate

> Have you met Ted ?
> Ted Mosby Architect.

![Ted Mosby](source/public/images/ted.png)
Format: ![Alt Text](http://images.google.fr/imgres?imgurl=http%3A%2F%2Fimages.memes.com%2Fmeme%2F413853&imgrefurl=http%3A%2F%2Fwww.memes.com%2Fimg%2F413853&h=337&w=450&tbnid=CEubLwM9GmiLMM%3A&vet=1&docid=uRHFXPtmvDQ6HM&ei=KjxrWLmKC4LsaoTysqgH&tbm=isch&client=ubuntu&iact=rc&uact=3&dur=416&page=0&start=0&ndsp=23&ved=0ahUKEwi5x6q2pKXRAhUCthoKHQS5DHUQMwgbKAEwAQ&bih=900&biw=1076)

### description :dog:
This is a boilerplate with an [atomic design](http://atomicdesign.bradfrost.com/) inspired file structure. It uses [Jade](https://pugjs.org/api/getting-started.html) (Pug) as template engine and [Sass](http://sass-lang.com/) (scss) as preprocessor. Ready for [Prepros](https://prepros.io/) compiler.

### Recommended Settings :panda_face:

* Compiler : [Prepros](https://prepros.io/) (remove *prepros.cfg* if you don't use Prepros)

* template engine : [Jade (Pug)](https://pugjs.org/api/getting-started.html)  

##### CSS
* preprocessor : [Sass](http://sass-lang.com/)  
* [PostCSS](http://postcss.org/) : [Autoprefixer](https://autoprefixer.github.io/)    
* reset : [normalize.scss](https://github.com/kristerkari/normalize.scss) (modifie *app/base/_normalize.scss*)  
* Style guides : [SMACSS](https://smacss.com/)
* Linter (atom) : [sass-lint](https://atom.io/packages/linter-sass-lint)  

##### JS    
* Style guides : [Standard Happiness](https://github.com/JedWatson/happiness) (with ";")  
* Linter (atom) : [js-standard Happiness](https://github.com/ricardofbarros/linter-js-standard) (*.sass-lint.yml*)  

* Libraries :  
  * [jQuery](https://jquery.com/) ([jQuery Core 3.1.1.min](https://code.jquery.com/) is loaded in *app/templates/layout.jade*)  
  * [Event Emitter](https://github.com/asyncly/EventEmitter2) (*app/vendors/eventemitter2.js*)  
