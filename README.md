# Global Game Jam thank you websites


## Directory Layout

    /bundles
        bundle.css                  --> Generated by gulp task 'dev'. Contains all styles the project needs.
        bundle.js                   --> Generated by gulp task 'dev'. Contains all scripts the project needs.
    /fonts                          --> Contains all fonts the project needs. Some of the fonts may be grabbed from node_modules. Such as font awesome.
    /images                         --> Contains all images the project needs.
    /javascripts
        /animations                 --> Contains all scripts that control animations.
            section-1.js            --> Controls the animations of section 1.
            section-2.js            --> Controls the animations of section 2.
            section-3.js            --> Controls the animations of section 3.
        main.js                     --> The entry point javascript file. Contains global settings and project bootstrapping.
    /node_modules                   --> Contains 3rd party dependencies.
    /scss                           --> Contains all scss files the project needs.
    .gitignore
    gulpfile.js                     --> Gulp tasks.
    index.html                      --> The html structure of this project.
    package.json
        

## Getting Started

1. Install dependencies:

        npm install

2. Start gulp task:

        gulp dev   
       
        
## Getting Ready For Production

1. Minimize files using gulp task:

        gulp prod

2. Upload files to your server and run:

        npm install --production
        
   Add `--production` tag to only install dependencies that are needed for production environment.


## License

MIT
