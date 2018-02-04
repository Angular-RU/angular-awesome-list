<p align="center">
  <a href="https://angular-ru.github.io" target="_blank">
    <img src="/media/awesome-angular.png" alt="Awesome Angular" />
  </a>
</p>

# Awesome Angular [![Awesome TipeIO](https://img.shields.io/badge/Awesome%20Angular-@TipeIO-6C6AE7.svg)](https://github.com/gdi2290/awesome-angular) [![Awesome devarchy.com](https://img.shields.io/badge/Awesome%20Angular-@devarchy.com-86BDC1.svg)](https://github.com/brillout/awesome-angular-components)

Здесь вы найдете список полезных репозиториев, стартеры, примеры, учебные пособия, компоненты, модули, видеоролики и все остальное причастное к экосистеме Angular. А также вы можете подписаться на наш чат в телеграмме: 

[![Angular-RU](https://img.shields.io/badge/Telegram_chat:-Angular_RU-216bc1.svg?style=flat)](https://t.me/angular_ru)

##### Current Angular version:
[![npm version](https://badge.fury.io/js/%40angular%2Fcore.svg)](https://www.npmjs.com/~angular)

##### Current Browser support for Angular:
[![Sauce Test Status](https://saucelabs.com/browser-matrix/angular2-ci.svg)](https://saucelabs.com/u/angular2-ci)

**Содержание**:

* [Angular](#angular)
  * [Официальные ресурсы](#angular-official)
  * [Новости в twitter](#twitter)
  * [Сообщества](#community)
  * [Серверный рендеринг](#server-side-rendering)
  * [Cheatsheet (чит-лист)](#cheatsheet)
  * [UI библиотеки](#angular-ui)
    * [Material Design](#material)
  * [Важные особенности](#features)
    * [Компоненты](#components)
    * [Шаблоны](#templates)
    * [Обнаружение изменений](#change-detection)
    * [Внедрение зависимостей](#dependency-injection)
    * [Директивы](#directives)
    * [Пайпы](#pipes)
    * [Web Workers](#web-workers)
    * [HTTP](#http)
    * [Роутинг](#router)
    * [Тестирование](#test)
    * [Ahead-of-Time компиляция](#aot)
  * [Angular CLI](#angular-cli)
  * [Dev Tools](#dev-tools)
  * [Starter Kit](#starter-kit)
  * [Webpack стартеры](#webpack)
  * [Angular Universal](#universal-angular)
    * [Universal (основные ресурсы)](#universal-general-resources)
    * [Основные источники](#universal-seed-projects)
  * [Публикации](#series)
  * [Видеоуроки](#video-tutorials)
  * [Стайл-гайды](#style-guides)
  * [Angular Connect конференция](#angular-connect)
  * [Книги](#books)
  * [Курсы и тренинги](#on-site-training)
  * [Подборка статей](#approach-and-explanation)
  * [Интеграция](#integrations)
  * [Подборка компонентов](#components-list)
  * [Пайпы](#pipes-seed)
  * [Примеры приложений](#site-templates)
  * [Генераторы](#generators)
  * [Инструменты документации](#documentation-tools)
  * [TodoMVC](#todomvc)
  * [TypeScript](#angular-in-typescript)
    * [TypeScript (основные ресурсы)](#typescript-general-resources)
    * [Основные источники](#typescript-seed-projects)
  * [Dart](#angular-in-dart)
    * [Основные источники](#dart-seed-projects)
  * [Babel](#angular-in-babel)
    * [Babel (основные ресурсы)](#babel-general-resources)
    * [Online Playground](#babel-angular-online-playground)
    * [Основные источники](#babel-seed-projects)
    * [Babel плагины](#babel-plugins)
  * [ES5](#angular-in-es5)
    * [Основные источники](#es5-seed-projects)
  * [Ionic](#ionic-in-angular)
    * [Ionic 2 (основные ресурсы)](#ionic-general-resources)
  * [Meteor](#meteor-in-angular)
    * [Meteor (основные ресурсы)](#meteor-general-resources)
    * [Основные источники](#meteor-seed-projects)
  * [NativeScript](#angular-in-nativescript)
    * [NativeScript (основные ресурсы)](#nativescript-general-resources)
    * [Основные источники](#nativescript-seed-projects)
  * [React Native](#angular-in-react-native)
    * [React Native (основные ресурсы)](#react-native-general-resources)
  * [Haxe](#angular-in-haxe)
    * [Основные источники](#haxe-seed-projects)
  * [Scala](#angular-in-scala)
    * [Основные источники](#scala-seed-projects)
  * [Bit](#angular-components-with-bit)
  * [Security](#security)
  * [NgRx](#ngrx)
--------

<h2 id="angular">Angular</h2>

> Angular - это платформа для разработки мобильных и десктопных веб-приложений.

<h3 id="angular">Официальные ресурсы</h3>

* [Сайт](https://angular.io/)
* [Блог](http://angularjs.blogspot.com/)
* [Документация по фреймворку](https://angular.io/docs/js/latest/)
* [Чит-лист частовстречающихся вещей в Angular](https://angular.io/guide/cheatsheet)
* [Быстрый старт](https://angular.io/guide/quickstart)
* [GitHub репозиторий](https://github.com/angular/angular)

<h3 id="twitter">Новости в twitter</h3>

> Данный список хорош тем, что благодаря нему, вы будете в курсе основных событий.

##### Angular Team (эксперты из команды Angular)

* [Мишко Хевери (@mhevery)](https://twitter.com/mhevery)
* [Игор Минар (@mhevery)](https://twitter.com/mhevery)
* [Брэд Грин (bradlygreen)](https://twitter.com/bradlygreen)
* [Наоми Блэк (@naomitraveller)](https://twitter.com/naomitraveller)
* [Тобиас Бош (@tbosch1009)](https://twitter.com/tbosch1009)
* [Кара Эриксон (@karaforthewin)](https://twitter.com/karaforthewin)
* [Роб Уормальд (@robwormald)](https://twitter.com/robwormald)

##### [Google Developer Experts](https://developers.google.com/experts/all/technology/web-technologies)
* [Джек Франклин](https://twitter.com/jack_franklin)
* [Тьерри Шатель](https://twitter.com/ThierryChatel)
* [Ури Шейк](https://twitter.com/urishaked)
* [Гонсало Руис из Виллы Суарес](https://twitter.com/gruizdevilla)
* [Джон Папа](https://twitter.com/sharondio)
* [Джон Папа](https://twitter.com/John_Papa)
* [Дэн Вахлин](https://twitter.com/danwahlin)
* [Кристиан Вейер](https://twitter.com/christianweyer)
* [Тоддский девиз](https://twitter.com/toddmotto)
* [Тим Раффлес](https://twitter.com/timruffles)
* [Вассим Чхаг](https://twitter.com/manekinekko)
* [Aaron Frost](https://twitter.com/js_dev)
* [Аарон Фрост](https://twitter.com/willmendesneto)
* [Джаред Уильямс](https://twitter.com/jaredwilli)
* [Жерар Санс](https://twitter.com/gerardsans)
* [Паскаль Прехт](https://twitter.com/PascalPrecht)
* [Джефф Whelpley](https://twitter.com/jeffwhelpley/)
* [Рауль Хименес](https://twitter.com/elecash/)
* [Киро Нанес](https://twitter.com/cironunesdev/)
* [Максим Сальников](https://twitter.com/webmaxru)
* [Дебора Курата](https://twitter.com/deborahkurata)
* [Минько Гечев](https://twitter.com/mgechev)
* [Шай Резник](https://twitter.com/shai_reznik)

##### Остальные известные эксперты:

* [Патрик Стэплтон (@gdi2290)](https://twitter.com/gdi2290)
* [Скотт Мосс (@scotups)](https://twitter.com/scotups)
* [Брэд Грин (@bradlygreen)](https://twitter.com/bradlygreen)
* [Джефф Кросс (@jeffbcross)](https://twitter.com/jeffbcross)
* [Виктор Савкин (@victorsavkin)](https://twitter.com/victorsavkin)
* [Павел Козловский (@pkozlowski_os)](https://twitter.com/pkozlowski_os)
* [Алексей Охрименко (@Ai_boy)](https://twitter.com/Ai_boy)

##### Сообщества:

* [egghead.io (@eggheadio)](https://twitter.com/eggheadio)
* [hirez.io (@hirez_io)](https://twitter.com/hirez_io)
* [hypedrivendev.io (@cedric_exbrayat)](https://twitter.com/cedric_exbrayat)
* [amcdnl.com (@amcdnl)](https://twitter.com/amcdnl)
* [ultimateangular.com (@ultimateangular)](https://twitter.com/ultimateangular)

##### Митапы:

* [Angular Moscow (@AngularMoscow)](https://twitter.com/AngularMoscow)
* [Angular NYC (@ngNewYork)](https://twitter.com/ngNewYork)

Этот список далеко не полный...

<h3 id="community">Сообщества</h3>

* [`Angular сообщества в twitter`](https://twitter.com/search?f=users&vertical=default&q=%23angular&src=tyah)

![](https://habrastorage.org/webt/uo/hi/ce/uohices8pudw2cib-lji_yp4wte.png)

* [Канал в Gitter](https://gitter.im/angular/angular)
* [Вопросы по Angular на StackOverflow](https://stackoverflow.com/questions/tagged/angular)
* [Angular на Reddit](https://www.reddit.com/r/Angular2/)
* [Подкасты от AngularAir](http://angularair.com/)
* [Подкатсы от Devchat по Angular](https://devchat.tv/adv-in-angular)
* [Журнал ng-newsletter](http://www.ng-newsletter.com)
* [Витрина приложений от Angular Expo](http://angularexpo.com/)
* [Чат от AngularBuddies в Slack](https://angularbuddies.slack.com/messages/ng-2/)
* [Чат от dartlang.slack.com в Slack](https://dartlang.slack.com/messages/angular2) 
* [Подборка популярных Twitter's аккаунтов](http://theherdlocker.com/tweet/popularity/angular2)

---

<h3 id="server-side-rendering">Серверный рендеринг</h3>

* [Официальный репозиторий Angular Universal (GitHub)](https://github.com/angular/universal)
* [Русскоязычный репозиторий Angular Universal (GitHub)](https://github.com/Angular-RU/angular-universal-starter)
- [@ng-seed/universal](https://github.com/ng-seed/universal) - Angular Universal стартер

---

<h3 id="cheatsheet">Cheatsheet (чит-лист)</h3>

* [Официальный cheatsheet от Angular](https://angular.io/guide/cheatsheet)
* [Официальный cheatsheet по AngularDart](https://docs.google.com/document/d/1FYyA-b9rc2UtlYyQXjW7lx4Y08MSpuWcbbuqVCxHga0/edit#heading=h.34sus6g4zss3)
* [Еще один cheatsheet для AngularDart](https://github.com/andresaraujo/angular2_cheatsheet_dart)
* [Чек-лист Angular Performance](https://github.com/mgechev/angular-performance-checklist)

---

<h3 id="angular-ui">UI библиотеки</h3>

<h4 id="material">Material Design</h4>

* [Официальный репозиторий Angular Material Design (GitHub)](https://github.com/angular/material2)
* [Коллекция Material Design компонентов (md2)](https://github.com/Promact/md2) 
* [Коллекция компонентов на основе материала Material Design Lite (angular2-mdl)](https://www.npmjs.com/package/angular2-mdl) 
* [Компоненты, созданные с помощью Google Material Design Lite framework (mdl-ext)](https://www.npmjs.com/package/mdl-ext)
* [Компоненты Materialize library (ng2-materialize)](https://github.com/sherweb/ng2-materialize)
* [Material Light](https://github.com/YagoLopez/material-light) 
* [Легковесная библиотека на основе Material Design](https://github.com/src-zone/material)

---

<h3 id="features">Важные особенности</h3>

<h4 id="components">Компоненты</h4>

Компонент управляет отображением представления на экране, в ее основе используется Shadow DOM по умолчанию (для создания инкапсулированного визуального поведения). Как правило, компоненты используются для создания простого виджета в пользовательском интерфейсе, в то же время они могут представлять из себя набор еще более простых компонентов внутри себя (для увеличения абстракции и создания простых функциональных виджетов внутри приложения).

```js
@Component({
  selector: 'html-name-element'
})
export class MyComponent {
  // ...
}
```

<h4 id="templates">Шаблоны</h4>

Шаблон - это ваша html-разметка, в которой вы можете описывать ваши взаимодействия с DOM на основе модели данных и событий вашего класса компонента (в примере, контроллер MyComponent).

```js
@Component({
 template: 'my-component.component.html'
})
export class MyComponent {
 
  public title: string = "Hello world";
  
  // ..

}
```

```html
<!-- my-component.component.html -->
<p>
  Интерполяция: {{ title }},  
  или так:      {{ this.title }}
</p>
```

<h4 id="change-detection">Обнаружение изменений</h4>

Каждый компонент имеет свой собственный детектор изменений, который гарантирует проверку привязок данных, определенных шаблоне.

<h4 id="dependency-injection">Внедрение зависимостей</h4>

Внедрение зависимостей (англ. Dependency Injection) — это композиция структурных шаблонов проектирования, при которой за каждую функцию приложения отвечает один, условно независимый объект (сервис), который может иметь необходимость использовать другие объекты (зависимости), известные ему интерфейсами. Зависимости передаются (внедряются) сервису в момент его создания.


```js
// logger.service.ts
@Injectable()
export class LoggerService {
  // ..
  
  public get trace() {
    return console.debug.bind(console);
  }
  
}
```

```js
// my-component.component.ts
@Component({ /* .. */ })
export class MyComponent {
 
  constructor(private logger: LoggerService) {
    logger.trace('Init MyComponent');
  }

}
```

<h4 id="directives">Директивы</h4>

Директивы позволяют получать прямой доступ к DOM ваших элементов. Они бывают двух видов: структурные и атрибутные.

Атрибутная директива:

```js
@Directive({
  selector: '[bold]'
})
export class BoldDirective {
     
    constructor(private elementRef: ElementRef){
        this.elementRef.nativeElement.style.fontWeight = "bold";
    }
}
```

Здесь внедряется сервис "ElementRef". Он представляет ссылку на элемент, к которому будет применяться директива:


```html
<!-- my-component.component.html -->
<p bold>Hello world</p>
```

Структурные директивы:

Структурные директивы изменяют структуру DOM с помощью добавления или удаления html-элементов. Существует минимум три встроенных структурных директивы: ngIf, ngSwitch и ngFor.

```js
@Component({ /* ... */ })
export class AppComponent {
    // ..
    
    public items = ["Apple iPhone", "Huawei Mate", "Samsung Galaxy", "Motorola Moto Z"];
}
```

```html
<!-- my-component.component.html -->
<ul>
  <li *ngFor="let item of items">{{item}}</li>
</ul>
```

<h4 id="pipes">Пайпы</h4>

Пайп (pipe) представляет собой особый обработчик, который позволяет форматировать отображаемые значения

```js
// my-component.component.ts
@Component({ /* .. */ })
export class MyComponent {
  public fields = [ { id: 1 }, { id: 2 } ];
}
```

```html
<!-- my-component.component.html -->
Читаемый вывод объекта: 
<pre> {{ fields | json }} </pre>
```

Помимо стандартных, вы можете писать собственные

```js
@Pipe({ name: 'factorial' })
export class FactorialPipe implements PipeTransform {
  transform(value: number, args?: any): number {
    if (value <= 0) return 0;
     
    let result = 1;
    for (let i = 1; i <= value; i++) {
        result = result * i;
    }
    
    return result;
  }
}
```

```js
// my-component.component.ts
@Component({ /* .. */ })
export class MyComponent {
  public x = 5;
}
```

```html
<!-- my-component.component.html -->
Факториал числа {{ x }} равен {{ x | factorial }}
<!-- Факториал числа 5 равен 120 -->
```

<h4 id="web-workers">Web Workers</h4>

Поддержка Web Worker в Angular предназначена для упрощенного распараллеливания в вашем приложении. Когда ваше приложение запускается, Angular проводит всю основную работу по обработке вашей логики в отдельных потоках, ядро выполняет вычисление в своем рабочем потоке, в то время как другие функции могут и вовсе выполняться не в потоках.

<h4 id="http">HTTP</h4>

Самый распространенный способ получить данные от web-служб — это через HttpClient сервис доступный для внедрения зависимостей в ваших компонентах. Angular HttpClient довольно прост. Все, что нам нужно сделать, это вызвать метода get и передать ему url. Данный метод get возвращает объект Observable. Этот класс является частью библиотеки rxjs, которая используется во многих местах Angular'а.

```js
// rest.service.ts
@Injectable()
export class RestService {

  constructor(private httpClient: HttpClient) {}
  
  public getByObservable(url: string): Observable<any> {
      return this.httpClient.get(url);
  }
  
  public getByPromise(url: string): Promise<any> {
      return this.httpClient.get(url).toPromise();
  }
 
}
```

Подобно обещанию (Promise), наблюдатель (Observable) не содержит в себе сразу значения. Вместо этого у него есть метод подписки(subscribe), где мы можем зарегистрировать обратный вызов(callback). Этот callback вызывается, как только результат будет доступен. Помимо обещания, Observable может вернуть более одного значения. Вы можете вернуть себе поток результатов. Но это не имеет значения в данном случае. В нашем случае Observable возвращает только одно значение.

```js
// my-component.component.ts
@Component({ /* .. */ })
export class MyComponent {

  constructor(private rest: RestService) {}
  
  // Observable classic examples
  public getFields() {
    this.rest.getByObservable('http://anyurl.com').subscibe(value =>{
      // value - результат
    },
    error => {
      // error - объект ошибки
    });
  }
  
  // Promise classic examples
  public async getAsyncField() {
    try {
      // value - результат
      const value = await this.rest.getByPromise('http://anyurl.com');
    } catch (error) {
      // error - объект ошибки
    }
  }
  
}
```

<h4 id="router">Роутинг</h4>

* [Официальная документация Router](https://angular.io/guide/router.html#sts=Router%20imports)
* [ui-router](https://github.com/angular-ui/ui-router)

<h4 id="test">Тестирование</h4>

* [Тестирование Http сервиса с Jasmine](http://chariotsolutions.com/blog/post/testing-http-services-angular-2-jasmine/)
* [UI-тестирование компонентов с TestComponentBuilder](http://chariotsolutions.com/blog/post/testing-angular-2-components-unit-tests-testcomponentbuilder/)

<h4 id="aot">Ahead-of-Time компиляция</h4>

* [Официальная документация](https://angular.io/guide/aot-compiler)
* [AOT в Angular](http://blog.mgechev.com/2016/08/14/ahead-of-time-compilation-angular-offline-precompilation/)
* [Сборка Angular приложения для продакшина](http://blog.mgechev.com/2016/06/26/tree-shaking-angular2-production-build-rollup-javascript/)
* [Прояснения в Ahead-Of-Time компиляции в Angular](http://slides.com/wassimchegham/demystifying-ahead-of-time-compilation-in-angular-2-aot-jit)
* [Несколько решений по работе с Ahead of Time (AOT)](https://blog.craftlab.hu/multiple-solutions-for-angular-ahead-of-time-aot-compilation-c474d9a0d508)
* [Пример кода с Webpack и AOT](https://github.com/blacksonic/angular2-aot-webpack)
* [Пример кода с Rollup и AOT](https://github.com/mgechev/angular2-ngc-rollup-build)

---

### Angular CLI

> Angular CLI - инструмент для быстрой разработки приложений на Angular

* [Официальный сайт](https://cli.angular.io/) 
* [Официальный репозиторий](https://github.com/angular/angular-cli)

---

### Dev Tools

* [@compodoc/ngd-cli](https://github.com/compodoc/ngd) - Просмотр зависимостей в Angular
* [angular-playground](http://www.angularplayground.it/) - Scenario Driven Development
* [@ngrx/store-devtools](https://github.com/ngrx/store-devtools) - Инструменты разработчика для @ngrx/store.
* [angular-prettyjson](https://github.com/matiboy/angular2-prettyjson) - Улучшенный вывод объектов в шаблоне для отладки (директива json)
* [Augury](https://github.com/rangle/augury) - Chrome расширение разработчика для отладки 
* [angular-webpack-config](https://github.com/ng-seed/angular-webpack-config) - Заготовленная Webpack конфигурация для быстрого старта

---

### Starter Kit

* [test-angular-seed-project](https://github.com/angular/angular2-seed) - Простой стартер Angular
* [generator-ng-fullstack](https://github.com/ericmdantas/generator-ng-fullstack) - ng-fullstack yeoman генератор
* [asaf-test](https://github.com/preboot/angular-library-seed) - Angular стартер от preboot
* [angular-seed](https://github.com/mgechev/angular-seed) - Angular стартер от Minko Gechev - [clarity-seed](https://github.com/vmware/clarity-seed) - Clarity Design System's стартер
* [Colmena CMS](https://github.com/colmena/colmena-cms) - Colmena CMS (LoopBack + Angular)

---

<h3 id="webpack">Webpack стартеры</h3>

* [Официальный сайт Webpack](https://webpack.js.org)
* [Angular Webpack стартер от AngularClass (@PatrickJS)](https://github.com/gdi2290/angular-starter)
* [Angular Webpack стартер от Preboot](https://github.com/preboot/angular-webpack)
* [Angular Nightly Webpack стартер](https://github.com/qdouble/angular-webpack2-starter)
* [Angular Webpack стартер с ASP.NET Core от Damien Bowden](https://github.com/damienbod/AngularWebpackVisualStudio)
* [Webpack конфигурация для Angular разработки от ng-seed](https://github.com/ng-seed/angular-webpack-config)

---

<h3 id="universal-angular">Angular Universal</h3>

> Universal (изоморфный) - рендеринг приложений Angular на серверной стороне

<h4 id="universal-general-resources">Universal (основные ресурсы)</h4>

* [Официальный репозиторий (GitHub)](https://github.com/angular/universal)

<h4 id="universal-seed-projects">Основные источники</h4>

* [universal-starter](https://github.com/angular/universal-starter) - Angular Universal стартер от @Angular-Class
* [ng-seed/universal](https://github.com/ng-seed/universal) - Angular Universal стартер с Webpack, dev/prod modes, DLLs, AoT compilation, HMR, SCSS compilation, lazy loading, config, cache, i18n, SEO, TSLint/codelyzer

---

<h3 id="series">Публикации</h3>

* Ionic
  * Angular
    * [Введение](http://blog.ionic.io/angular-2-series-introduction/)
    * [Компоненты](http://blog.ionic.io/angular-2-series-components/)
* Auth0
  * Angular
    * [Работаем c пайпами (pipes)](https://auth0.com/blog/angular2-series-working-with-pipes/)
    * [Паттерн проектирования Domain Model and Dependency Injection](https://auth0.com/blog/angular-2-series-part-2-domain-models-and-dependency-injection/)
    * [Создание Desktop приложения на Angular 2 и Electron](https://auth0.com/blog/create-a-desktop-app-with-angular-2-and-electron/)
* thoughtram
  * Angular Template Syntax
    * [Введение](https://blog.thoughtram.io/angular/2015/08/11/angular-2-template-syntax-demystified-part-1.html)
* [letsboot.com](https://medium.com/letsboot)
  * Test Driven Development
    * [Angular TDD, Karma, Jasmine, PhantomJS, Gitlab-CI](https://medium.com/letsboot/angular-4-and-testing-angular-cli-gitlab-ci-ng-test-phantomjs-tdd-afc20f50b928)
  * Angular and Firebase
    * [Учимся настраивать и работать AngularFire](https://medium.com/letsboot/lets-learn-how-to-install-and-setup-angularfire2-4-0-135d72bb0a41)

---

<h3 id="video-tutorials">Видеоуроки</h3>

* [Egghead.io - Angular](https://egghead.io/technologies/angular2)
* [Egghead.io - Разработка приложения на Angular + Redux](https://egghead.io/courses/building-a-time-machine-with-angular-2-and-rxjs)
* [HiRez.io - Angular: основы](https://www.hirez.io/c/angular-basics-1/e/episode-1-course-overview)
* [HiRez.io - Angular: введение в компоненты](https://www.hirez.io/c/components-1/e/episode-1-course-overview)
* [Udemy - Введение в Angular](https://www.udemy.com/introduction-to-angular2/)
* [Udemy - Angular и TypeScript для начинающих](https://www.udemy.com/angular-2-tutorial-for-beginners/)
* [Udemy - Курс по Angular](https://www.udemy.com/the-complete-guide-to-angular-2/)
* [Pluralsight - Angular: обзор](https://www.pluralsight.com/courses/angular-2-first-look)
* [Pluralsight - Angular 2: Getting Started](https://www.pluralsight.com/courses/angular-2-getting-started-update)
* [Channel9 - Будущее TypeScript](https://channel9.msdn.com/Events/Build/2015/3-644)
* [Channel9 - Создание кроссплатформенных приложений с Angular](https://channel9.msdn.com/Events/Build/2016/T627)
* [Code School - Разгоняем Angular](https://www.codeschool.com/courses/accelerating-through-angular)
* [Angular - типизированное хранилище](https://www.youtube.com/watch?v=bEkPEnudm7s&feature=youtu.be)
* [Angular - расширенные советы и рекомендации](https://www.youtube.com/watch?v=vyiyJCLlGwo&feature=youtu.be)
* [Angular Fullstack](https://www.youtube.com/channel/UCRefxaAA-7PfezH3CY87fzw)
* [Angular Master Class](https://www.udemy.com/angular-crash-course-for-beginners)

---

<h3 id="style-guides">Стайл-гайды</h3>

* [Официальный Angular Style guide](https://angular.io/guide/styleguide)
* [Описание того, как нужно составлять правила для TSLint](https://github.com/ng-seed/angular-tslint-rules)
* [codelyzer](https://github.com/mgechev/codelyzer) - Линтер для Angular проектов
* [angular-tslint-rules](https://github.com/ng-seed/angular-tslint-rules) - Сборник лучших правил TSLint & codelyzer

---

<h3 id="angular-connect">Angular Connect конференция</h3>

* [Основной доклад – Brad Green, Igor Minar and Jules Kremer](https://www.youtube.com/watch?v=UxjgUjVpe24)
* [Стратегии тестирования Angular – Julie Ralph](https://www.youtube.com/watch?v=C0F2E-PRm44)
* [Создание нативных мобильных приложений с Angular and NativeScript​ - Sebastian Witalec](https://www.youtube.com/watch?v=4SbiiyRSIwo)
* [Angular Data Flow – Jeff Cross, Rob Wormald and Alex Rickabaugh](https://www.youtube.com/watch?v=bVI5gGTEQ_U)
* [Стратегии итеративных обновлений больших Angular-приложений – Jen Bourey](https://www.youtube.com/watch?v=8tGcdaItj0I)
* [Отладка Angular приложений с ипсользованием Batarangle – Yuri Takhteyev and Igor Krivanov](https://www.youtube.com/watch?v=cAC4d3KIQcM)
* [Разработка приложений с Firebase and Angular - Sara Robinson](https://www.youtube.com/watch?v=RD0xYicNcaY)
* [Концепции Angular - Victor Savkin and Tobias Bosch](https://www.youtube.com/watch?v=4YmnbGoh49U)
* [Модульность Angular приложений – Pawel Kozlowski](https://www.youtube.com/watch?v=9odY9Rh5kTQ)
* [Создание приложений реального времени на Angular и Meteor - Uri Goldshtein](https://www.youtube.com/watch?v=3FT0BqYASCo)

---

<h3 id="books">Книги</h3>

* [ng-book 2](https://www.ng-book.com/2/) `fullstack.io`
* [Как стать ниндзя в Angular](https://books.ninja-squad.com/angular) `Ninja Squad`
* [Angular разработка с TypeScript](https://www.manning.com/books/angular-2-development-with-typescript) `Manning Publications`
* [Angular в бою](https://www.manning.com/books/angular-in-action) `Manning Publications`
* [Практики Angular](https://leanpub.com/practical-angular-2) `Leanpub`
* [Переходим на Angular](https://www.packtpub.com/web-development/switching-angular-2) `Packt Publishing`
* [Angular тренинги](https://www.gitbook.com/book/rangle-io/ngcourse2/details) `Rangle.io`
* [Изучаем Angular](http://learnangular2.com/) `Ionic Team`
* [Тестирование Angular приложений](https://www.manning.com/books/testing-angular-applications) `Manning Publications`

---

<h3 id="on-site-training">Онлайн тренинги</h3>

* [AngularClass](https://angularclass.com)
* [Angular Boot Camp](https://angularbootcamp.com)
* [thoughtram](http://thoughtram.io/training.html)
* [Egghead.io](https://egghead.io/angularjs-enterprise-training-workshop)
* [ng-book](https://www.ng-book.com/2/)
* [Angular Workshop](http://chariotsolutions.com/course/angular-workshop-fundamentals-architecture/)
* [Web Age Solutions](http://www.webagesolutions.com/courses/WA2533-introduction-to-angular-2-programming)
* [Letsboot.com](https://www.letsboot.com/angular-2-in-house-training-support)
* [Free on-site 2-days training delivered by SFEIR (in France)](https://school.sfeir.com/project/sa200/)

---

<h3 id="approach-and-explanation">Подборка статей</h3>

* Victor Savkin
  * [Внедрение зависимостей (DI) в AngularJS и Angular](https://vsavkin.com/dependency-injection-in-angular-1-and-angular-2-d69589979c18)
  * [Пишем на Angular с Typescript](https://vsavkin.com/writing-angular-2-in-typescript-1fa77c78d8e8)
  * [Angular - синтаксис шаблонов](https://vsavkin.com/angular-2-template-syntax-5f2ee9f13c6a)
  * [Концепция The Core Concepts of Angular 2](https://vsavkin.com/the-core-concepts-of-angular-2-c3d6cbe04d04)
  * [Основные файзы при разработке на Angular](https://vsavkin.com/two-phases-of-angular-2-applications-fda2517604be)
  * [Стратегии обнаружения в Angular](https://vsavkin.com/change-detection-in-angular-2-4f216b855d4c)
  * [Поддержка функционального программирования](https://vsavkin.tumblr.com/post/108837493941/better-support-for-functional-programming-in)
  * [Angular: унифицированный Dependency Injection](https://vsavkin.tumblr.com/post/102965317996/angular-2-bits-unified-dependency-injection)
  * [Angular Router](https://vsavkin.com/angular-2-router-d9e30599f9ea)

* AngularClass
  * [Автоматизированное развертывание приложений на Angular и Webpack](https://angularclass.com/blog/automated-angular-2-conventions-with-webpack/)
  * [Angular для AngularJS разработчиков](https://angularclass.com/blog/angular-2-for-angularjs-developers/)
  * [Angular 2 для ReactJS разработчиков](https://angularclass.com/blog/angular-2-for-react-developers/)

* thoughtram
  * [Разработка компонента tabs (вкладки) в Angular](https://blog.thoughtram.io/angular/2015/04/09/developing-a-tabs-component-in-angular-2.html)
  * [Разработка zippy-компонента в Angular](https://blog.thoughtram.io/angular/2015/03/27/building-a-zippy-component-in-angular-2.html)
  * [Введение в сервисы в Angular](https://blog.thoughtram.io/angular/2015/09/17/resolve-service-dependencies-in-angular-2.html)
  * [Forward references в Angular](https://blog.thoughtram.io/angular/2015/09/03/forward-references-in-angular-2.html)
  * [Видимость в DI в Angular 2](https://blog.thoughtram.io/angular/2015/08/20/host-and-visibility-in-angular-2-dependency-injection.html)
  * [Dependency Injection in Angular 2](https://blog.thoughtram.io/angular/2015/05/18/dependency-injection-in-angular-2.html)
  * [Роутинг в Angular](https://blog.thoughtram.io/angular/2016/06/14/routing-in-angular-2-revisited.html)
  * [Angular - синтаксис шаблонов](http://blog.thoughtram.io/angular/2015/08/11/angular-2-template-syntax-demystified-part-1.html)
  * [View Encapsulation в Angular](https://blog.thoughtram.io/angular/2015/06/29/shadow-dom-strategies-in-angular2.html)
  * [Стилизация Angular компонентов](https://blog.thoughtram.io/angular/2015/06/25/styling-angular-2-components.html)
  * [ES5 для Angular](https://blog.thoughtram.io/angular/2015/07/06/even-better-es5-code-for-angular-2.html)
  * [Пишем на JS в Angular](https://blog.thoughtram.io/angular/2015/05/09/writing-angular-2-code-in-es5.html)
  * [Разница между аннотациями и декораторами](https://blog.thoughtram.io/angular/2015/05/03/the-difference-between-annotations-and-decorators.html)

* Hristo Georgiev
  * [Отладка Angular приложений](https://www.pluralsight.com/guides/front-end-javascript/debugging-angular-2-applications)

* Helgevold Consulting
  * [Web Workers в Angular](http://www.syntaxsuccess.com/viewarticle/web-workers-in-angular-2.0)
  * [Создание сетки для Angular](http://www.syntaxsuccess.com/viewarticle/virtualized-spreadsheet-component-in-angular-2.0)
  * [Socket.io с Observables](http://www.syntaxsuccess.com/viewarticle/socket.io-with-rxjs-in-angular-2.0)
  * [Change Detection в Angular](http://www.syntaxsuccess.com/viewarticle/change-detection-in-angular-2.0)

* Burak Tasci (fulls1z3)
  * [Angular - server side rendering (Angular Universal)](https://medium.com/burak-tasci/angular-4-with-server-side-rendering-aka-angular-universal-f6c228ded8b0)
  
---

<h3 id="integrations">Интеграции</h3>

* [FalcorJS + Angular (видео)](https://www.youtube.com/watch?v=z8UgDZ4rXBU&feature=youtu.be)
* [Angular + Meteor](http://angular-meteor.com/angular2)
* [NativeScript + Angular](https://github.com/NativeScript/nativescript-angular)
* [ReactNative + Angular](https://github.com/angular/react-native-renderer)
* [GraphQL + Angular](https://github.com/apollographql/apollo-angular)
* [angularfire2](https://github.com/angular/angularfire2) - Официальная библиотека Angular для Firebase
* [angular-jwt](https://github.com/auth0/angular2-jwt) Библиотека для отправки аутентифицированных HTTP-запросов и декодирования JWT
* [angular-meteor](https://github.com/Urigo/angular-meteor) - Angular + Meteor
* [angulartics2](https://github.com/angulartics/angulartics2) - GoogleAnalytics + Angular
* [perfectedtech-loopback-sdk-builder](https://github.com/mean-expert-official/loopback-sdk-builder) - SDKs LoopBack
* [karma-typescript](https://github.com/monounity/karma-typescript) - Простой стартер для написания юнит тестов с Karma
* [meteor-rxjs](https://github.com/Urigo/mongo-rxjs-observable) - Имплементация Mongo + RxJS Observable
* [wp-api-angular](https://github.com/shprink/wp-api-angular) - Angular сервисы для WordPress WP-API(v2) or WP >= 4.7
* [selfbits-angular-sdk](https://github.com/selfbits/selfbits-angular2-sdk) - Angular SDK  Backend-as-a-Service.
* [ng-wp-api](https://github.com/MurhafSousli/ng2-wp-api) - Angular WordPress модуль
* [angular-disqus](https://github.com/Useful-Software-Solutions-Ltd/angular2-disqus) - DISQUS + Angular
* [@cloudinary/angular](https://github.com/cloudinary/cloudinary_angular) - пользовательская библиотека Cloudinary
* [ng-recaptcha](https://github.com/dethariel/ng2-recaptcha) - Angular + Google reCAPTCHA.
* [angular-recaptcha](https://github.com/xmaestro/angular2-recaptcha) - Angular + Google reCaptcha (еще один компонент)
* [pubnub-angular2](https://github.com/pubnub/pubnub-angular2) - Официальный PubNub для Angular
* [ng-awesome-disqus](https://github.com/MurhafSousli/ng2-disqus) - Модуль для работы с Disqus
* [angular-esri-loader](https://github.com/tomwayson/angular2-esri-loader) - ArcGIS API
* [@ngx-universal/state-transfer](https://github.com/fulls1z3/ngx-universal) - Передача состояния в изоморфных приложениях

---

<h3 id="components-list">Подборка компонентов</h3>

* [Material 2](https://github.com/angular/material2) - Компоненты от Material Design
* [NG ZORRO](https://github.com/NG-ZORRO/ng-zorro-antd) - Enterprise компоненты, основанные на Ant Design
* [Element Angular](https://github.com/eleme/element-angular) - Element Design компоненты
* [ng-bootstrap](https://github.com/valor-software/ngx-bootstrap) Нативный Bootstrap для Angular
* [ng-charts](https://github.com/valor-software/ng2-charts) Компоненты диаграмм основанные на Chart.js
* [ng-dragula](https://github.com/valor-software/ng2-dragula) Drag and Drop
* [ng-file-upload](https://github.com/valor-software/ng2-file-upload) Простая директива для загрузки файлов
* [ng-handsontable](https://github.com/valor-software/ng2-handsontable) Excel-подобная таблица (data grid / spreadsheet)
* [ng-markdown](https://github.com/evanplaice/ng2-markdown) Angular Markdown компонент
* [ng-select](https://github.com/valor-software/ng2-select) Angular компонент для select
* [ng-safe-img](https://github.com/hyzhak/ng2-safe-img) Простая директива для обработки событий ошибки загрузки картинок (img)
* [ng-table](https://github.com/valor-software/ng2-table) Простой компонент таблицы с сортировкой и фильтрацией
* [ng-smart-table](https://github.com/akveo/ng2-smart-table) Smart-компонент таблицы
* [ng-bs](https://github.com/pkozlowski-opensource/ng2-bs) Директивы для Bootstrap
* [ng-lightning](https://github.com/ng-lightning/ng-lightning) Компоненты основанные на Lightning Design System
* [ag-grid](https://www.ag-grid.com/) Улучшенный Datagrid
* [angular-query-builder](https://github.com/zebzhao/Angular-QueryBuilder) Усовершенствованные запросы на основе jquery QueryBuilder
* [angular-grid](https://github.com/BTMorton/angular2-grid) drag/drop/resize сетка
* [angular-cookie](https://github.com/salemdar/angular2-cookie) Библиотека имплеминтирующая из AngularJS 1.x $cookies-сервис в Angular
* [angular-fontawesome](https://github.com/travelist/angular2-fontawesome) Angular компоненты и директивы для Fontawesome
* [angular-safeguard](https://github.com/MikaAK/angular-safeguard) Обертка над cookies/sessionStorage/localStorage
* [angular-google-maps](https://github.com/SebastianM/angular-google-maps) Angular директивы для Google Maps
* [angular-cesium](https://github.com/TGFTech/angular-cesium) Создание map web apps с использованием Cesium
* [ng-radio-group](https://github.com/pleerock/ngx-select-controls) Angular директивы для radio/checkbox
* [ng-dropdown](https://github.com/pleerock/ngx-dropdown) Выпадающее меню на основе bootstrap 3
* [angular-multiselect-dropdown](https://github.com/CuppaLabs/angular2-multiselect-dropdown) Выпадающее меню (multiselect)
* [ng-progress-bar](https://github.com/pleerock/ngx-progress-bar) Простой progress bar
* [ng-tabs](https://github.com/pleerock/ngx-tabs) Tabs control для angular
* [ng-modal](https://github.com/pleerock/ngx-modal) Модальные окна
* [ng-sheet](https://github.com/lexikteam/ng2-sheet) Динамические компоненты меню
* [ng-paginator](https://github.com/pleerock/ngx-paginator) Контроллы пагинации для angular
* [fuel-ui](https://github.com/FuelInteractive/fuel-ui) Bootstrap 4 компоненты и директивы
* [prime-ng](https://www.primefaces.org/primeng/)  Коллекция Primeng-компонентов
* [ng-ace](https://github.com/seiyria/ng2-ace) Ace editor на Angular
* [ng-storage](https://github.com/seiyria/ng2-storage) localStorage и sessionStorage обертки
* [ng-fontawesome](https://github.com/seiyria/ng2-fontawesome) Простая директива для fontawesome
* [ng-sweetalert2](https://github.com/seiyria/ng2-sweetalert2) Обертка над sweetalert2 
* [angular-text-mask](https://github.com/text-mask/text-mask) Angular input маска (директива)
* [angular-imask](https://github.com/uNmAnNeR/imaskjs/tree/gh-pages/plugins/angular) Еще одна input маска (директива)
* [ng-fullpage](https://github.com/meiblorn/ngx-fullpage) Fullpage скролл на основе fullPage.js
* [file-droppa](https://github.com/ptkach/fileDroppa) Простой загрузчик файлов на основе drag and drop
* [ngx-img-fallback](https://github.com/VadimDez/ngx-img-fallback) Placeholder загрузки для image и image error
* [angular-busy](https://github.com/devyumao/angular2-busy) Индекатор загрузки для Promise, Observable's
* [ng-pdf-viewer](https://github.com/VadimDez/ng2-pdf-viewer) PDF viewer на Angular
* [Covalent](https://teradata.github.io/covalent/) - UI набор компонентов на основе Material Design
* [ng2-alfresco-core](https://github.com/Alfresco/alfresco-ng2-components) - Alfresco набор компонентов
* [angular-infinite-scroll](https://www.npmjs.com/package/angular2-infinite-scroll) - Бесконечный скролл на Angular
* [ng-card](https://github.com/c-bata/ng2-card) - Card-компоненты
* [Wijmo 5](http://wijmo.com/products/wijmo-5/) - Набор компонентов пользовательского интерфейса для Angular
* [ng-swipeable-card](https://github.com/JayKan/ng2-swipeable-card) - Перетаскиваемые card-компонентыы
* [ngSemantic](https://github.com/vladotesanovic/ngSemantic) - Компоненты пользовательского интерфейса на основе  Semantic UI
* [vmware clarity](https://github.com/vmware/clarity) - Clarity набор компонентов от VMware
* [Teradata covalent](https://github.com/Teradata/covalent/) - Набор компонентов пользовательского интерфейса на основе materialize
* [ng-quill-editor](https://github.com/surmon-china/ngx-quill-editor) - Quill editor компонент
* [ngx-charts](https://github.com/swimlane/ngx-charts) - Настраиваемый Charting-фреймворк на Angular
* [ngx-datatable](https://github.com/swimlane/ngx-datatable)  Функциональный и легкий компонент таблиц данных
* [ngx-ui](https://github.com/swimlane/ngx-ui) - Библиотека стилей и компонентов ngx-ui
* [Cloudinary](https://github.com/cloudinary/cloudinary_angular/tree/angular_next) - Angular SDK для управления изображениями и видео в облаке
* [angular-simple-countdown](https://github.com/previousdeveloper/angular2-simple-countdown) - Простой countdown
* [ng-http-cache](https://github.com/davguij/angular-http-cache) - Кеширование http-запросов
* [ng-animate](https://github.com/jiayihu/ng-animate) - Коллекция крутых анимаций
* [lottie-angular](https://github.com/chenqingspring/ng-lottie) - After Effects анимации для Angular
* [ngx-restangular](https://github.com/2muchcoffeecom/ngx-restangular) - Restangular сервис
* [ngfb-sortable-table](https://github.com/NodeArt/Angular-Firebase-Sortable-Table) - Angular Firebase Table компоненты
* [angular-split](https://github.com/bertrandg/angular-split) Angular split компонент
* [od-virtualscroll](https://github.com/dinony/od-virtualscroll) Бесконечный скролл на Observable
* [angular-froala-wysiwyg](https://github.com/froala/angular-froala-wysiwyg) WYSIWYG HTML Editor на Angular
* [ngx-meta](https://github.com/fulls1z3/ngx-meta) - Утилита Dynamic page для Angular Universal
* [ngx-config](https://github.com/fulls1z3/ngx-config) - Настройки для Angular (Angular Universal loader)
* [ngx-cache](https://github.com/fulls1z3/ngx-cache) - Кеширование в Angular
* [ngx-i18n-router](https://github.com/fulls1z3/ngx-i18n-router) - Роутинг с учетом локализации
* [ngx-auth](https://github.com/fulls1z3/ngx-auth)  Сервис аутентификации
* [angular-promise-buttons](https://github.com/johannesjo/angular2-promise-buttons) - Кнопка загрузки
* [ng-archwizard](https://github.com/madoar/ng2-archwizard) - Wizard компонент
* [ngx-popper](https://github.com/MrFrankel/ngx-popper) - Tooltip менеджер на основе popper.js(https://popper.js.org/)
* [ngx-avatar](https://github.com/HaithemMosbahi/ngx-avatar) - Компонент аватарок
* [ngx-qrcode2](https://github.com/techiediaries/ngx-qrcode) - Компонент для генерации QR (Quick Response ) кода 
* [ng2-permission](https://github.com/JavadRasouli/ng2-permission) - Полнофункциональный контроль доступа на основе ролей и прав в вашем приложении [`angular-permission`](https://github.com/Narzerus/angular-permission).
* [ng-s-resource](https://github.com/hiyali/ng-s-resource) - Простой RESTful http генератор ресурсов
* [ng-data-picker](https://github.com/hiyali/ng-data-picker) - Data picker
* [ngx-siema](https://github.com/lexzhukov/ngx-siema) - Простая карусель
* [ng-bootstrap](https://ng-bootstrap.github.io) - Angular директивы для Bootstrap 4
* [ng-snotify](https://github.com/artemsky/ng-snotify/) - Angular Notification Center
* [ngx-permissions](https://github.com/AlexKhymenko/ngx-permissions) - Управление доступом и ролями
* [nebular](https://github.com/akveo/nebular) - Фреймворк Nebular основанный на Angular
* [ng-select](https://github.com/ng-select/ng-select) ng-select (Select, Multiselect, Autocomplete)
* [ng-katex](https://github.com/garciparedes/ng-katex) Модуль для математических выражений с синтаксисом TeX
* [ng-fullcalendar](https://github.com/Jamaks/ng-fullcalendar) Jquery календарь для Angular
* [angular-modal](https://github.com/shlomiassaf/angular2-modal) - Angular + нативный Dialog компонент
* [ng-bs3-modal](https://github.com/dougludlow/ng2-bs3-modal) - Angular + Bootstrap3 Компонент модального окна
* [angular-toaster](https://github.com/stabzs/Angular2-Toaster) - Angular компонент асинхронных неблокирующих уведомлений (toaster)
* [ng-toasty](https://github.com/akserg/ng2-toasty) - Angular Toasty компонент
* [ng-notifications](https://github.com/alexcastillo/ng2-notifications) - Angular компонент с поддержкой Push Notifications
* [ngx-toastr](https://github.com/scttcper/ngx-toastr) - Angular toastr
* [@ngrx/notify](https://github.com/ngrx/notify) - Web уведомления на RxJS
* [angular-notifications](https://github.com/flauc/angular2-notifications) - Простой и легкий в использовании компонент нотификаций и уведомлений
* [angular-notifier](https://github.com/dominique-mueller/angular-notifier) - Отличная библиотека нотификаций с крутыми и настраиваемыми анимациями
* [ng-toastr](https://github.com/PointInside/ng2-toastr) - Bootstrap toast
* [angular-confirmation-popover](https://github.com/mattlewis92/angular-confirmation-popover) - Отображает всплывающее подтверждение загрузки (без jQuery или bootstrap)
* [angular-datatable](https://github.com/mariuszfoltak/angular2-datatable) - DataTable компонент для Angular с сортировкой и пагинацией
* [ng-easy-table](https://github.com/ssuperczynski/ng2-easy-table) - Простая таблица для Angular
* [ag-grid-angular](https://github.com/ceolter/ag-grid-angular) - Ag-Grid компонент
* [angular-tree-component](https://github.com/500tech/angular2-tree-component) - Простой компонент отображающий список в виде дерева
* [ng-tree](https://github.com/valor-software/ng2-tree) - Компонент  для визуализации данных, которые могут быть представлены естественным образом в виде дерева
* [ng-slim-loading-bar](https://github.com/akserg/ng2-slim-loading-bar) - компонент элемента загрузки на странице
* [angular-ladda](https://github.com/moff/angular2-ladda) - Angular Ladda модуль
* [ng-spin-kit](https://github.com/WoltersKluwerPL/ng-spin-kit) - SpinKit (спинер)
* [ngx-progressbar](https://github.com/MurhafSousli/ngx-progressbar) - мощный progress bar
* [ng-sidebar](https://github.com/arkon/ng-sidebar) - Angular sidebar компонент
* [angular-highcharts](https://github.com/gevgeny/angular2-highcharts) - Highcharts компонент
* [ng-nvd3](https://github.com/krispo/ng2-nvd3) - Angular компонент для nvd3
* [angular-google-maps](https://github.com/SebastianM/angular2-google-maps) - Angular + Google Maps
* [ng-map](https://github.com/ng2-ui/ng2-map) - Angular + Google Maps (директива)
* [angular-esri4-components](https://github.com/kgs916/angular2-esri4-components) - Angula + ArcGIS API
* [ngx-infinite-scroll](https://github.com/orizens/ngx-infinite-scroll) - Бесконечный скролл (директива)
* [ng-parallax-scroll](https://github.com/ng2-ui/ng2-parallax-scroll) - Angular parallax
* [angular-perfect-scrollbar](https://github.com/zefoy/ngx-perfect-scrollbar) - Angular scrollbar
* [angular-swiper-wrapper](https://github.com/zefoy/ngx-swiper-wrapper) - Angular swiper
* [@ngui/sticky](https://github.com/ng2-ui/sticky) - Angular "position: sticky" директива
* [angular-contextmenu](https://github.com/isaacplmann/angular2-contextmenu) - Компонент контекстного меню
* [angular-moment](https://github.com/urish/angular2-moment) - Moment.js пайпы (pipes)
* [videogular](https://github.com/videogular/videogular2) - HTML5 video player + Angular
* [ng-inline-svg](https://github.com/arkon/ng-inline-svg) - Angular директива для добавления SVG файлов в виде инлайн-элемента
* [ng-sharebuttons](https://github.com/MurhafSousli/ng2-sharebuttons) - Кнопка "поделиться"
* [ng-inline-editor](https://github.com/caballerog/ng2-inline-editor) - Нативный UI редактор
* [ng-markdown-to-html](https://github.com/jfcere/ng2-markdown-to-html) - Markdown компонент
* [ngx-no-animation-for-dinosaur](https://github.com/maxisam/ngx-no-animation-for-dinosaur) - Простое решение для отключения анимации для определенного браузера
* [ng-datepicker](https://github.com/jkuri/ng2-datepicker) - Angular Datepicker
* [mydatepicker](https://github.com/kekeh/mydatepicker) - Angular date picker
* [ng-datetime](https://github.com/nkalinov/ng2-datetime) - Datetime picker
* [ng-date-picker](https://github.com/vlio20/ng2-date-picker) - Крутой и настраиваемый date picker компонент
* [angular-material-datepicker](https://github.com/koleary94/Angular-2-Datepicker) - Angular Datepicker + material design
* [ngx-color-picker](https://github.com/zefoy/ngx-color-picker) - Color picker
* [angular-color-picker](https://github.com/Alberplz/angular2-color-picker) - Angular Color Picker (директива)
* [ng-color-picker](https://github.com/AndyMeps/ng2-color-picker) - Простой color picker
* [ng-slider-component](https://github.com/Bogdan1975/ng2-slider-component) - Angular slider 
* [angular-select](https://github.com/basvandenberg/angular2-select) - Нативный select 
* [ng-completer](https://github.com/oferh/ng2-completer) - Angular autocomplete 
* [ng-auto-complete](https://github.com/ng2-ui/ng2-auto-complete) - AutoComplete.
* [ng-tag-input](https://github.com/Gbuomprisco/ng2-tag-input) - Tag Input 
* [ng-dnd](https://github.com/akserg/ng2-dnd) - Angular 2 Drag-and-Drop without dependencies.
* [ng-drag-drop](https://github.com/ObaidUrRehman/ng-drag-drop) - Drag & Drop
* [angular-sortablejs](https://github.com/SortableJS/angular-sortablejs) - Angular + SortableJS
* [soft-angular-mask](https://github.com/renatosistemasvc/soft-angular-mask) - Директива маски для ввода денежной валюты
* [ng-ckeditor-codemirror](https://github.com/chymz/ng2-ckeditor) - Angular CKEditor 
* [angular-voog-wysihtml](https://github.com/zefoy/ngx-voog-wysihtml) - Voog wysihtml
* [angular-froala-wysiwyg](https://github.com/froala/angular2-froala-wysiwyg) - Froala WYSIWYG
* [ngx-uploader](https://github.com/jkuri/ngx-uploader) - Angular файловый загрузчик
* [angular-dropzone-wrapper](https://github.com/zefoy/ngx-dropzone-wrapper) - Angular  dropzone
* [angular-autosize](https://github.com/stevepapa/angular2-autosize) - Angular-autosize директива для textarea
* [angular-calendar](https://github.com/mattlewis92/angular2-calendar) - flexible календарь
* [angular-fullcalendar](https://github.com/nekken/ng2-fullcalendar) - Angular fullcalendar
* [ng2-img-cropper](https://github.com/cstefanache/angular2-img-cropper) - Angular Image Cropper
* [angular-mdl](https://github.com/mseemann/angular2-mdl) - Angular material design lite
* [igniteui-angular2](https://github.com/IgniteUI/igniteui-angular2) - Ignite UI
* [igniteui-js-blocks](https://github.com/IgniteUI/igniteui-js-blocks) - Mobile-first нативный компонент
* [devextreme-angular](https://github.com/DevExpress/devextreme-angular) - DevExtreme виджеты
* [ng-fullpage](https://github.com/meiblorn/ng2-fullpage) - Angular fullpage скроллинг
* [ngresizable](https://github.com/mgechev/ngresizable) - Растягиваемые компоненты
* [@angular/flex-layout](https://github.com/angular/flex-layout)
* [ng-bootstrap](https://github.com/valor-software/ng2-bootstrap) - Нативные директивы для Bootstrap
* [@ng-bootstrap/ng-bootstrap](https://github.com/ng-bootstrap/ng-bootstrap) - Angular + Bootstrap
* [angular-materialize](https://github.com/InfomediaLtd/angular2-materialize) - Angular + Materialize
* [ng-semantic-ui](https://github.com/edcarroll/ng2-semantic-ui) - Semantic UI
* [clarity-angular](https://github.com/vmware/clarity) - Clarity Design System

---

<h3 id="pipes-seed">Пайпы (pipes)</h3>

* [fuel-ui](https://github.com/FuelInteractive/fuel-ui) - OrderBy и Range, портированные из AngularJS 1.x в Angular
* [ngx-filter-pipe](https://github.com/VadimDez/ngx-filter-pipe) Пайп (pipe) для фильтрации массивов
* [ngx-pipes](https://github.com/danrevah/ngx-pipes) набор полезных пайпов для Angular
* [ngx-order-pipe](https://github.com/VadimDez/ngx-order-pipe) OrderBy - сортировка коллекций
* [angular2-camelcase](https://github.com/previousdeveloper/angular2-camelcase) Пайп для преобразования строк в camelCase
* [angular-pipes](https://github.com/fknop/angular-pipes) - Используем крутые пайпы
* [ngx-pipes](https://github.com/danrevah/ngx-pipes) - Пайпы без единой зависимости
* [ng-pipes](https://github.com/a8m/ng-pipes) -  Набор полезных пайпов
* [angular-linky](https://github.com/dzonatan/angular2-linky) - Linky пайп

---

<h3 id="site-templates">Примеры приложений</h3>

* [NG-Dashboard](https://github.com/YagoLopez/ng-dashboard) - Dashboard для Angular 4+. Компоненты пользовательского интерфейса на основе [Material Light](https://github.com/YagoLopez/material-light?ref=awesome-angular). Компоненты диаграмм на основе [MetricsGraficsJS](https://www.metricsgraphicsjs.org). Map директива на основе [LeafletJS](http://leafletjs.com). [DEMO ONLINE](http://yagolopez.js.org/ng-dashboard/dist/)

<h3 id="generators">Генераторы</h3>

* Node.js
  * Slush
    * [TheVelourFog/slush-angular2](https://github.com/RyanMetin/slush-angular2)
  * Yeoman
    * [swirlycheetah/generator-angular2](https://github.com/chrisdwheatley/generator-angular2)
  * Faristo
    * [majodi/generator-angular2](https://github.com/majodi/Faristo)
  * ngX-Rocket:
    * [ngx-rocket/generator-ngx-rocket](https://github.com/ngx-rocket/generator-ngx-rocket)
    * [ngx-rocket/cli](https://github.com/ngx-rocket/cli)
    * [ngx-rocket/core](https://github.com/ngx-rocket/core)
* Dart
  * Stagehand
    * [google/stagehand](https://github.com/google/stagehand)

---

<h3 id="documentation-tools">Инструменты документации</h3>

* [Storybook](https://github.com/storybooks/storybook): "Cреда разработки, которую вы полюбите"
* [Compodoc](https://github.com/compodoc/compodoc): Отличный инструмент для создания документации вашего приложения
* [AngularDoc](http://angulardoc.io/): Веб-сайт, отображающий "Архитектуру и визуализацию Angular-приложения"
* [NgModule-Viz](https://github.com/politie/ngmodule-viz): Визуализация связей между NgModules и зависимостями в Angular

---

<h3 id="todomvc">TodoMVC</h3>

* [Официальный TodoMVC для Angular](http://todomvc.com/examples/angular2/)

---

<h3 id="angular-in-typescript">TypeScript</h3>

> TypeScript позволяет вам писать код на JavaScript так, как вы этого хотите.

TypeScript является типизированным надмножеством JavaScript, который компилируется в JavaScript.

<h4 id="typescript-general-resources">TypeScript (основные ресурсы)</h4>

* [TypeScript](http://www.typescriptlang.org/) Официальный сайт TypeScript
* [REPL](http://www.typescriptlang.org/play/) Официальная онлайн-среда для компиляции TypeScript в браузере
* [Официальный репозиторий (GitHub)](https://github.com/Microsoft/TypeScript)
* [DefinitelyTyped официальный репозиторий (GitHub)](https://github.com/DefinitelyTyped/DefinitelyTyped) Высококачественные определения типов 

<h4 id="typescript-seed-projects">Основные источники</h4>

* [Angular стартер от @mgechev](https://mgechev.github.io/angular-seed/) Angular стартер (Angular 5+, TypeScript, Gulp, ..)
* [TypeScript](http://www.typescriptlang.org), [Angular Flex Layout](https://github.com/angular/flex-layout), [Material 2](https://material.angular.io), [AOT](https://angular.io/docs/ts/latest/cookbook/aot-compiler.html), unit/e2e тесты [Travis CI](https://travis-ci.org) и [Saucelabs](https://saucelabs.com).
* [Angular подборка примеров](https://github.com/thelgevold/angular-2-samples)
* [Angular, Angular CLI, AngularFire2, OAuth, Immutable - пример](https://github.com/r-park/todo-angular-firebase)
* [Spring Boot и Angular](https://github.com/springboot-angular2-tutorial/angular2-app) Практические примеры от [Rails](https://www.railstutorial.org/).
* [Angular стартер с Gulp и Travis CI](https://github.com/antonybudianto/angular-starter)
* [Angular Leaflet Starter](https://github.com/haoliangyu/ngx-leaflet-starter) - приложение с картами
* [Angular MapboxGL Starter](https://github.com/haoliangyu/ngx-mapboxgl-starter) - Другой стартер с картами, основанный на Angular и MapboxGL JS
* [Angular + websockets](https://github.com/mkusz/ng2_websockets_quickstart) - Простой счетчик с 2-way и 1-way взаимодействием по websockets
* [ng-start](https://github.com/cebor/ng2-start) - Минимально настроенное angular приложение
* [ng-kitchen-sink](https://github.com/born2net/Angular-kitchen-sink) - Пример SPA на Angular
* [ng-skeleton](https://github.com/born2net/ng-skeleton) - Пример SPA на Angular c ngrx, bootstrap и двухфакторной авторизацией
* [angular-demo](https://github.com/amcdnl/angular2-demo) Minimal Angular2 Demo using TypeScript / Sass / Npm Tasks
* [Angular Dashboard Starter](https://github.com/hasanhameed07/angular2-dashboard-starter) - Простая панель управления на Angular 2 и AdminLTE
* [ngx-admin](https://github.com/akveo/ngx-admin) - Панель управления на Nebular
* [Angular стартер от @valor-software](https://github.com/valor-software/angular2-quickstart)
* [Angular webpack стартер от @michaelbazos](https://github.com/michaelbazos/angular2-starter)
* [ng-boiler](https://github.com/amcdnl/ng2-boiler) - Angular, TypeScript, Webpack
* [Angular Webpack Starter](https://github.com/antonybudianto/angular-webpack-starter)
* [Reaper](https://github.com/Xamber/Reaper) - Angular Webpack Starter Boilerplate
* [famn](https://github.com/implustech/famn) - Angular + FeathersJS
* [Angular NPM Module Seed](https://github.com/davguij/angular-npm-module-seed) 
* [Angular2 D3v4 Seed](https://github.com/gp187/angular2-d3v4-graph) - Angular + реализация графиков
* [ng-seed/spa](https://github.com/ng-seed/spa) - Angular, Webpack, dev/prod modes, DLLs, AoT compilation, HMR, SCSS compilation, lazy loading, config, cache, i18n, SEO, and TSLint/codelyzer
* [Reboard](https://github.com/ksiabani/reboard) - Angular, Material 2, ngx-charts от generator-ngx-rocket (Typescript, SASS, Webpack, Jasmine+Karma, Protractor, TSLint, Codelyzer, Stylelint, ngx-translate, Lodash, Angular Flex-Layout)
* [Angular + Redux + Graphql + MySQL quickstart](https://github.com/rafaesc/fullstack-graphql-angular) - Простое приложение совместно с GraphQL, Angular CLI + Redux + Express + GraphQL + Sequelize (MySQL, Postgres, Sqlite, MSSQL).
* [Angular5 + Firebase + Structure](https://github.com/naologic/angular5-starter) - Angular + Firebase 

---

<h3 id="angular-in-dart">Dart</h3>

> Dart — язык программирования, созданный Google. Dart позиционируется в качестве замены/альтернативы JavaScript. Dart - это масштабируемый язык программирования с открытым исходным кодом, с качественными библиотеками и рантаймом, для создания веб-приложений, серверов и мобильных приложений.

<h4 id="dart-seed-projects">Основные источники</h4>

* [Dart](https://www.dartlang.org/) Официальный сайт 
* [Dartpad](https://dartpad.dartlang.org/) Dartpad позволяет вам писать на языке Dart прямо в браузере (аналог Typescript playground)
* [Официальный репозиторий (GitHub)](https://github.com/dart-lang)
* [Pub](https://pub.dartlang.org/) Репозиторий пакетов для Dart (аналог npm registry или любых других)
* [Dartisans](https://plus.google.com/communities/114566943291919232850) Официальное коммьюнити на Google Plus  
* [Dart Slack Channel](https://dartlang-slack.herokuapp.com/) Официальный канал в Slack
* [Angular Dart Quickstart](https://webdev.dartlang.org/angular/tutorial/toh-pt0)

---

<h3 id="angular-in-babel">Babel</h3>

> Babel – предназначен для транспиляции современного JS кода в код работающий на предыдущем стандарте, к примеру ES5. 

<h4 id="babel-general-resources">Babel (основные ресурсы)</h4>

* [Babel](https://babeljs.io/) Официальный сайт Babel
* [REPL](https://babeljs.io/repl/) Официальный REPL, который позволяет вам писать на современном ES6+ языке и видеть его результат
* [Официальный репозиторий Babel (GitHub)](https://github.com/babel/babel)

<h4 id="babel-angular-online-playground">Angular Online Playground</h4>

* [Plunker: Angular + Babel](http://plnkr.co/edit/PxCzCu?p=preview)

<h4 id="babel-seed-projects">Основные источники</h4>

* [babel-angular-app](https://github.com/shuhei/babel-angular2-app) Макет Angular приложения для [Babel](https://babeljs.io/) и [Browserify](http://browserify.org/)
* [angular-fullstack-starter](https://github.com/jgodi/angular2-fullstack-starter) Angular приложение + Webpack/Babel
* [angular-es6-starter](https://github.com/blacksonic/angular2-babel-esnext-starter) Angular приложение на ES6, Babel, Webpack, Gulp
* [angular-babel-seed](https://github.com/rbnlffl/angular-babel-seed) Простое Angular приложение на ES6
* [angular-es6-todomvc](https://github.com/blacksonic/angular2-esnext-todomvc) Angular TodoMVC + ES6
* [ng1-ng2-webpack-lazy-uirouter](https://github.com/swimlane/ng1-ng4-webpack-lazy-uirouter) Гибридное приложение на AngularJS + Angular в связке с UI-Router, Webpack, Babel

<h4 id="babel-plugins">Babel плагины</h4>

* [babel-preset-angular](https://github.com/shuhei/babel-preset-angular2) Babel пресеты (presets) для Angular
* [babel-plugin-type-assertion](https://github.com/shuhei/babel-plugin-type-assertion) Babel плагин для поддержки типизации в JS
* [babel-plugin-angular-annotations](https://github.com/shuhei/babel-plugin-angular2-annotations) - Babel плагин для трансформации декораторов
---

<h3 id="angular-in-es5">ES5</h3>

> ECMAScript включает в себя структурированные, динамические, функциональные и прототипные фичи

<h4 id="es5-seed-projects">Основные источники</h4>

[angular-es5-starter-kit](https://github.com/islam-muhammad/angular2-es5) Пример Angular приложения на ES5 

---

<h3 id="ionic-in-angular">Ionic</h3>

> Ionic - это прекрасный SDK с открытым исходным кодом для разработки гибридных мобильных приложений. 

* [Ionic Framework](http://ionicframework.com) Официальный сайт
* [Ionic Documentation](http://ionicframework.com/docs/) Официальная документация

<h4 id="ionic-general-resources">Ionic (основные ресурсы)</h4>

* [Ionic официальный репозиторий (GitHub)](https://github.com/ionic-team/ionic)
* [Ionic подборка ресурсов](https://github.com/candelibas/awesome-ionic)
* [Angular CLI Admin (Template)](https://github.com/jvitor83/angular-pwa-seed) Кроссплатформенный и кроссбраузерный стартер Angular  (Web/PWA, Mobile, Desktop) + Ionic
* [angular-onsenui](https://github.com/onsenui/onsenui) - Крутой SDK для Angular, Vue, React
---

<h3 id="meteor-in-angular">Meteor</h3>

> Meteor — веб-платформа на языке JavaScript, предназначенная для разработки Web-приложений реального времени.

<h4 id="meteor-general-resources">Meteor (основные ресурсы)</h4>

* [Angular Meteor](http://angular-meteor.com/) Официальный сайт
* [Пример аналога WhatsUp на Angular-Meteor + Ionic](https://www.angular-meteor.com/angular2)

<h4 id="meteor-seed-projects">Основные источники</h4>

* [Angular Meteor стартер](https://github.com/KyneSilverhide/angular2-meteor-seed)

---

<h3 id="angular-in-nativescript">NativeScript</h3>

> Создайвайте действительно нативные iOS, Android приложения на JS (TS) + CSS. NativeScript - кроссплатформенный фреймворк с открытым исходным кодом.

<h4 id="nativescript-general-resources">NativeScript (основные ресурсы)</h4>

* [NativeScript](https://www.nativescript.org/) Официальный сайт NativeScript
* [Примеры использования NativeScript](http://www.syntaxsuccess.com/viewarticle/using-nativescript-with-angular-2.0)

<h4 id="nativescript-seed-projects">Основные источники</h4>

* [Простой пример на Angular](https://github.com/NativeScript/sample-Angular2)
* [Крутой стартер на Angular](https://github.com/NathanWalker/angular-seed-advanced)

---

<h3 id="angular-in-react-native">React Native</h3>

> React Native — это фреймворк для создания нативно отображаемых iOS- и Android-приложений.

* [React Native](https://facebook.github.io/react-native/) Официальный сайт

<h4 id="react-native-general-resources">React Native (основные ресурсы)</h4>

* [Angular + React Native Renderer (GitHub)](https://github.com/angular/react-native-renderer)

---

<h3 id="angular-in-haxe">Haxe</h3>

> Haxe — это высокоуровневый мультиплатформенный язык программирования с открытым исходным кодом, а также компилятор, с помощью которого можно создавать приложения и генерировать исходный код для разных платформ, сохраняя единую кодовую базу. Haxe включает в себя функциональность, поддерживаемую на всех платформах, например: числовые типы данных, строки, массивы, а также поддержку некоторых файловых форматов (xml, zip). Haxe также включает в себя поддержку платформо-специфических API для Adobe Flash, C++, PHP и других языков. Код, написанный на языке Haxe, может быть транслирован в код ActionScript 3, JavaScript, Java, C#, C++, Python, Lua, PHP, Apache CGI, а также в приложение Node.js

<h4 id="haxe-seed-projects">Основные источники</h4>

* [Haxe.org](http://haxe.org)
* [Haxe на Wikipedia](https://en.wikipedia.org/wiki/Haxe)
* [Haxe Playground](https://try.haxe.org/)
* [Haxe compiler](http://haxe.org/documentation/introduction/compiler-targets.html) список того, во что можно компилировать: C++, C#, Java, Python, PHP, ActionScript 3, Flash, Neko bytecode
* [Haxe (результаты опросов)](blog.onthewings.net/2015/11/14/haxe_usage_survey/)
* [Haxe группа](https://groups.google.com/forum/#!forum/haxelang) - коммьюнити
* [Haxe и Node.js](matthijskamstra.github.io/haxenode/)
* [Haxe: работа с JavaScript библиотеками](http://philippe.elsass.me/2014/11/haxe-working-with-javascript-libraries/)
* [Изучаем haxe за Y минут](https://learnxinyminutes.com/docs/haxe/)
* [Успешная история про Haxe](http://nadako.github.io/rants/posts/2015-03-26_haxe-success-russian.html) - рассказ о портировании портирование с JavaScript на Haxe
* [angular2haxe](https://github.com/nweedon/angular2haxe) Разработка на Haxe и Angular

---

<h3 id="angular-in-scala">Scala</h3>

> Scala — мультипарадигмальный язык программирования, спроектированный кратким и типобезопасным для простого и быстрого создания компонентного программного обеспечения, сочетающий возможности функционального и объектно-ориентированного программирования. Язык программирования Scala является «симбиозом» Java и C#.

* [Scala-lang.org](https://www.scala-lang.org/)

<h4 id="scala-seed-projects">Основные источники</h4>

* [play-angular](https://github.com/gdi2290/play-angular2) - серверный рендеринг Angular на Scala

---

<h3 id="angular-components-with-bit">Bit</h3>

> Представьте, что все ваши компоненты доступны вам в облаке, и все это доступно для вашей команды и синхронизировано во всех ваших проектах. Это и есть Bit.

* [Bit](https://bitsrc.io/)
* [Bit официальный репозиторий (Github)](https://github.com/teambit/bit)
* [Bit-Javascript](https://github.com/teambit/bit-javascript)

---

<h3 id="security">NgRx</h3>

* [Введение в @ngrx/store](https://gist.github.com/btroncone/a6e4347326749f938510)
* [Redux + Angular - Часть 1](http://orizens.com/wp/topics/adding-redux-with-ngrxstore-to-angular-2-part-1/)
* [Redux + Angular - Часть 2 (Тестирование Reducers)](http://orizens.com/wp/topics/adding-redux-with-ngrxstore-to-angular2-part-2-testing-reducers/)
* [Redux + Angular: отличия от традиционной модели](http://orizens.com/wp/topics/angular-2-ngrxstore-the-ngmodel-in-between-use-case-from-angular-1/)
* [Angular, Ngrx/Store, Ngrx/Effects – Введение в функциональный подход к разработке приложений](http://orizens.com/wp/topics/angular-2-ngrxstore-ngrxeffects-intro-to-functional-approach-for-a-chain-of-actions/)
* [Создание простых API для @ngrx/Effects](https://gist.github.com/peterbsmith2/ce94c0a5ddceb99bab24a761731d1f07)
* [redux-decorators](https://github.com/KarlPurk/redux-decorators) - Декораторы для работы с Redux
* [@angular-redux/store](https://github.com/angular-redux/store) - Angular + Redux.
* [@ngrx/store](https://github.com/ngrx/store) - RxJS state менеджер на основе концепции Redux
* [mobx-angular](https://github.com/mobxjs/mobx-angular) - MobX + Angular
---

<h3 id="ngrx">Security</h3>

* [Angular.io Security Guide](https://angular.io/guide/security) - краткое руководство по безопасности, включающее информацию о предотвращении межсайтового скриптинга (XSS), политики безопасности и безопасности контента
* [Angular + OpenID](https://damienbod.com/2016/03/02/angular2-openid-connect-implicit-flow-with-identityserver4/)
* [Angular + OAuth2](https://github.com/michaeloryl/angular2-bootstrap4-oauth2-webpack)
* [Angular + OAuth2 OIDC](https://www.softwarearchitekt.at/post/2016/07/03/authentication-in-angular-2-with-oauth2-oidc-and-guards-for-the-newest-new-router-english-version.aspx)
* [Angular пример аутентификации](https://github.com/auth0-blog/angular2-authentication-sample)
* [ng-ui-auth](https://github.com/ronzeidman/ng2-ui-auth) - Аутентификация на основе satellizer
* [angular-token](https://github.com/neroniaky/angular2-token) - Служба аутентификации на основе сервиса токенов в Angular с поддержкой нескольких пользователей
* [angular-oauth2-oidc](https://github.com/manfredsteyer/angular-oauth2-oidc) - OAuth 2 + OpenId Connect (OIDC)
* [@ngx-auth/core](https://github.com/fulls1z3/ngx-auth) - Утилита аутентификации для Angular
