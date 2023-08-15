# WorganicTabV1

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 16.1.1.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Get clone 
> 
> npm install
> cd .\worganic-tab-v1\
> ng serve

## Abouts
Project créé par Johann Loreau
create le 2023/07/29
Le project sera voué à évolué suivant les remaques et conseils des visiteurs.

## Project :
V1 - Installation project
        > D:\project\v1\
        > ng new worganic-tab-v1
            / Would you like to add Angular routing? (y/N) 
                > N
            / Which stylesheet format would you like to use?
                > SCSS

    - Passage au projet au format standalone
        -> Modification main.ts
            \src\main.ts
            >> const routes: Routes = [
        -> Suppression app.module.ts
        -> Modification app.component.ts
            \src\app\app.component.ts
            Ajout du mode Standalone :
                @Component({...
                @Componen --> standalone: true
                ...
        -> Suppresion code app.component.html
            \src\app\app.component.html
        -> On le remplace par le code :
            <div>Page app.component</div>

    - Lancement du project :
        > ng serve
    "La V1 est ok"

    Infos plus :
    la page index.html :
        On ajoute <app-root></app-root> => page \src\app\app.component.ts 
        (app.component.ts : selector: 'app-root',)

## Historique :
Après -> v2 -> Mise en place du routing et de la structure du projet.

## Ressource :