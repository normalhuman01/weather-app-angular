<h3 align="center">Previsión del Tiempo (API: Open Weather) con Angular y TypeScript</h3>

<h4 align="center">Comandos</h4>

***Instalación de Angular:***
```
npm install -g @angular/cli
```

***Verificando las versiones:***
```
node -v
```
```
ng version
```

***Creando el proyecto:***
```
ng new weather
```

***Creando las páginas:***
```
ng g m pages/home
```
```
ng g m pages/bookmarks
```

***Creando los componentes:***
```
ng g c pages/home --type page
```
```
ng g c pages/bookmarks --type page
```

***Iniciando el Proyecto:***
```
ng s
```
```
http://localhost:4200/
```

***Desactivar Advertencia:***
```
ng config -g cli.warnings.versionMismatch false
```

***NGRX: Store***
```
ng add @ngrx/store
```
```
ng add @ngrx/store-devtools
```

***NGRX: Effect***
```
ng add @ngrx/effects
```

***Creando los componentes***
```
ng g c pages/home/components/current-weather
```
```
ng g c /shared/components/detailed-weather
```

<h3 align="center">Enlaces</h3>

[API: OpenWeather - Claves](https://home.openweathermap.org/api_keys) <br>
[jv-weather](https://github.com/JGhignatti/jv-weather) <br>
[NGRX](https://ngrx.io/) <br>
[NGRX: Store](ngrx.io/guide/store) <br>
[Redux DevTools](https://chrome.google.com/webstore/detail/redux-devtools/lmhkpmbekcpmknklioeibfkpmmfibljd?hl=pt-BR)
